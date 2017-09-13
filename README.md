# styled-dialog

A Polymer Element showing a styled modal dialog.

### Example
```html
<styled-dialog>
  <div>Content</div>
</styled-dialog>
```

### Styling

`<styled-dialog>` provides the following custom properties and mixins for styling:

Custom property                      | Description                        | Default
-------------------------------------|------------------------------------|--------
`--primary-text-color`               | Color of the normal and bold text. | inherit
`--secondary-text-color`             | Color of the name and note text.   | inherit
`--styled-dialog-max-width`          | Max width of the dialog.           | none
`--styled-dialog-min-width`          | Min width of the dialog.           | 900px
`--styled-dialog-style-mixin`        | Custom style mixin for the dialog. | none
`--styled-dialog-inside-style-mixin` | Custom style mixin for the inside. | none

`styled-dialog-styles.html` provides the following style classes:

- styled-dialog-bold
- styled-dialog-divider
- styled-dialog-list
- styled-dialog-name
- styled-dialog-note
- styled-dialog-padded
- styled-dialog-right-space
- styled-dialog-text
- styled-dialog-tall

Example Usage:

```html
<link rel="import" href="path/to/styled-dialog/styled-dialog-styles.html">
<dom-module id="my-element">
  <template>
    <style include="styled-dialog-styles"></style>
    <styled-dialog>
      <div class="styled-dialog-text">text</div>
    </styled-dialog>
  </template>
  <script> /* Define my-element */ </script>
</dom-module>
```

### Dependencies

Dependencies are installed using [Bower](http://bower.io/):

    npm install -g bower
    bower install

### Testing

Tests are run using [web-component-tester](https://github.com/Polymer/web-component-tester):

    npm install -g web-component-tester
    wct

### Demonstration & Documentation

Demonstration and documentation are viewed using [polyserve](https://github.com/PolymerLabs/polyserve):

    npm install -g polyserve
    polyserve

