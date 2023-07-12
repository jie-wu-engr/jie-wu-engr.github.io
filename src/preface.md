## How to embed a drawio file(html)
e.g. If you want to embed `./assets/drawiofile.html` into markdown, write like this:
```js
<div data-include="./assets/drawiofile"></div>
```
PS: No need to add the suffix `.html`.

<div data-include="./assets/drawiofile"></div>

## How to embed a pdf file
e.g. If you want to embed `./assets/tech_overview.pdf` into markdown, write like this:
```js
<embed src="./assets/tech_overview.pdf#page=5" width="100%" height="600">
```
PS: The current page and width & height setting are optional

<embed src="./assets/tech_overview.pdf#page=5" width="100%" height="600">