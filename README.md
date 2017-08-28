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

Custom property              | Description               | Default
-----------------------------|---------------------------|--------
`--styled-dialog-max-height` | Max height of the dialog. | none
`--styled-dialog-min-height` | Min height of the dialog. | none
`--styled-dialog-max-width`  | Max width of the dialog.  | none
`--styled-dialog-min-width`  | Min width of the dialog.  | 900px

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

