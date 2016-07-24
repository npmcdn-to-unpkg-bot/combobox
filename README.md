# Combobox

Combobox is a JavaScript plugin that will automatically turn a regular ol‘ `select` element into an autocomplete. It is only 6KB minified and doesn‘t have any dependencies. It comes with some default styles, but provides markup that can be easily customized if needed. It was built with accesibility in mind and makes full use of ARIA attributes and roles to be friendly to screen readers.

## Getting started

1. Include the styles in the head of your document `<link rel="stylesheet" href="https://s3.amazonaws.com/combobox/combobox.css">`
2. Include the script at the bottom of the body `<script src="https://s3.amazonaws.com/combobox/combobox.js"></script>`
3. Add a new `<select>` element with the class `autocomplete`

Make sure your select is wrapped in a container and it has a label within that container.

### Example:
```
<div>
  <label for="example">Example</label>
  <select id="example" class="autocomplete">
    <option value="1">Option one</option>
    <option value="2">Option two</option>
    <option value="3">Option three</option>
  </select>
</div>
```

[View on CodePen](http://codepen.io/dfmcphee/pen/EyLbgB)

## Development
`npm install && gulp`