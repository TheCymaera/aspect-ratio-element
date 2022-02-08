# Aspect Ratio Element

## Installation
Install via [NPM](https://www.npmjs.com/package/aspect-ratio-element).
```shell
npm install aspect-ratio-element
```

## Information
This library registers `<aspect-ratio>` using the [Custom Elements API](https://developer.mozilla.org/en-US/docs/Web/Web_Components/Using_custom_elements).

```html
<!-- Upright A4 Paper -->
<aspect-ratio style="--aspect-ratio: calc(1/1.4142)">
	<div class="paper"></div>
</aspect-ratio>
```

## Why not just use CSS?
CSS has a new property called `aspect-ratio`, but:
- The element is not constrained on both axes.
- The element's intrinsic size takes priority.
- Safari (incorrectly) requires the element's width or height to be set, preventing its use in layouts that don't use explicit width or height.

## License
MIT License<br/>
<br/>
All files can be used for commercial or non-commercial purposes. Do not resell. Attribution is appreciated but not due.