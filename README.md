# &lt;cp-progress-slat&gt;

> CanopyTax progress slat consistent with the CanopyTax style guide.

## Install

[Download as ZIP](https://github.com/CanopyTax/cp-progress-slat/archive/master.zip).

## Usage

1. Import polyfill:

    ```html
    <script src="/scripts/webcomponents.min.js"></script>
    ```

2. Import custom element:

    ```html
    <link rel="import" href="/custom_elements/cp-progress-slat.html">
    ```

3. Start using it!

    ```html
    <cp-progress-slat></cp-progress-slat>
    ```

## Options

Attribute               | Options       | Default             | Description
---                     | ---           | ---                 | ---
`progress-label`        | *string*      | `Progress`          | The text that appears on the left-most side of the progress slat. Generally describes what is in progress.
`progress-percent`      | *integer*     | `0`                 | The value, inclusive between 0 and 100, that indicates the amount complete.
`progress-bar-color`    | *string*      | `"#EDF7ED"`         | The browser-interpretable color that the progress indicator will be.
`progress-amount-color` | *string*      | `"#4CAF50"`         | The browser-interpretable color that the progress indicator's text value will be.


## License

[MIT License](http://opensource.org/licenses/MIT)
