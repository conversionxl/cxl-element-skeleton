# &lt;cxl-element&gt;

[&lt;cxl-element&gt;](https://github.com/conversionxl/cxl-element) is a Web Component providing &lt;element-functionality&gt;, part of the [CXL components](https://github.com/orgs/conversionxl/teams/web-components/repositories).

<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="cxl-element.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<cxl-element>
  ...
</cxl-element>
```

[<img src="https://raw.githubusercontent.com/conversionxl/cxl-element/master/screenshot.png" width="200" alt="Screenshot of cxl-element">](https://github.com/conversionxl/cxl-element)


## Installation

CXL/Vaadin components are distributed as npm packages.
Please note that the version range is the same, as the API has not changed.
You should not mix Bower and npm versions in the same application, though.

Unlike the official Polymer Elements, the converted Polymer 3 compatible CXL/Vaadin components
are only published on npm, not pushed to GitHub repositories.

### Polymer 2 and HTML Imports compatible version

Install `cxl-element`:

```sh
bower i cxl/cxl-element --save
```

Once installed, import it in your application:

```html
<link rel="import" href="bower_components/cxl-element/cxl-element.html">
```
### Polymer 3 and ES Modules compatible version


Install `cxl-element`:

```sh
npm i @cxl/cxl-element --save
```

Once installed, import it in your application:

```js
import '@cxl/cxl-element/cxl-element.js';
```

## Getting started

CXL/Vaadin components use the Lumo theme by default.


## Entry points

- The component with the Lumo theme:

  `theme/lumo/cxl-element.html`

- Alias for `theme/lumo/cxl-element.html`:

  `cxl-element.html`


## Running demos and tests in a browser

1. Fork the `cxl-element` repository and clone it locally.

1. Make sure you have [npm](https://www.npmjs.com/) and [Bower](https://bower.io) installed.

1. When in the `cxl-element` directory, run `npm install` and then `bower install` to install dependencies.

1. Make sure you have [polymer-cli](https://www.npmjs.com/package/polymer-cli) installed globally: `npm i -g polymer-cli`.

1. Run `npm start`, browser will automatically open the component API documentation.

1. You can also open demo or in-browser tests by adding **demo** or **test** to the URL, for example:

  - http://127.0.0.1:3000/components/cxl-element/demo
  - http://127.0.0.1:3000/components/cxl-element/test


## Running tests from the command line

1. When in the `cxl-element` directory, run `npm test`


## Following the coding style

We are using [ESLint](http://eslint.org/) for linting JavaScript code. You can check if your code is following our standards by running `npm run lint`, which will automatically lint all `.js` files as well as JavaScript snippets inside `.html` files.


## Big Thanks

Cross-browser Testing Platform and Open Source <3 Provided by [Sauce Labs](https://saucelabs.com).


## Contributing

  To contribute to the component, please read [the guideline](https://github.com/vaadin/vaadin-core/blob/master/CONTRIBUTING.md) first.


## License

Apache License 2.0

Vaadin collects development time usage statistics to improve this product. For details and to opt-out, see https://github.com/vaadin/vaadin-usage-statistics.
