[![Build Status](https://travis-ci.org/vaadin/incubator-chat.svg?branch=master)](https://travis-ci.org/vaadin/incubator-chat)
[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/vaadin/web-components?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)
[![Published on Vaadin  Directory](https://img.shields.io/badge/Vaadin%20Directory-published-00b4f0.svg)](https://vaadin.com/directory/component/vaadinincubator-chat)
[![Stars in Vaadin_Directory](https://img.shields.io/vaadin-directory/stars/vaadinincubator-chat.svg)](https://vaadin.com/directory/component/vaadinincubator-chat)
[![Latest Version](https://img.shields.io/vaadin-directory/v/vaadinincubator-chat.svg)](https://vaadin.com/directory/component/vaadinincubator-chat)

# &lt;incubator-chat&gt;

[Live Demo ↗](https://vaadin.com/directory/component/vaadinincubator-element/html-examples)
|
[API documentation ↗](https://vaadin.com/directory/component/vaadinincubator-element/html-api)


[&lt;incubator-chat&gt;](https://vaadin.com/directory/component/vaadinincubator-element) is a Web Component providing an easy way to ask the user to confirm a choice, part of the [Vaadin components](https://vaadin.com/components).

```html
  <incubator-chat header="Unsaved changes" confirm-text="Save" on-confirm="save"
    cancel on-cancel="cancel" reject reject-text="Discard" on-reject="discard">
    Do you want to save or discard your changes before navigating away?
  </incubator-chat>
```

[<img src="https://raw.githubusercontent.com/vaadin/incubator-chat/master/screenshot.png" width="200" alt="Screenshot of incubator-chat">](https://vaadin.com/directory/component/vaadinincubator-element)


## Installation

The Vaadin Incubator components are distributed as Bower packages.

### Polymer 2 and HTML Imports compatible version

Install `incubator-chat`:

```sh
bower i vaadin/incubator-chat --save
```

Once installed, import it in your application:

```html
<link rel="import" href="bower_components/incubator-chat/incubator-chat.html">
```

## Getting Started

Vaadin components use the Lumo theme by default.

## The file structure for Vaadin components

- `src/incubator-chat.html`

  Unstyled component.

- `theme/lumo/incubator-chat.html`

  Component with Lumo theme.

- `incubator-chat.html`

  Alias for theme/lumo/incubator-chat.html


## Running demos and tests in browser

1. Fork the `incubator-chat` repository and clone it locally.

1. Make sure you have [npm](https://www.npmjs.com/) installed.

1. When in the `incubator-chat` directory, run `npm install` and then `bower install` to install dependencies.

1. Run `polymer serve --open`, browser will automatically open the component API documentation.

1. You can also open demo or in-browser tests by adding **demo** or **test** to the URL, for example:

  - http://127.0.0.1:8080/components/incubator-chat/demo
  - http://127.0.0.1:8080/components/incubator-chat/test


## Running tests from the command line

1. When in the `incubator-chat` directory, run `polymer test`


## Following the coding style

We are using [ESLint](http://eslint.org/) for linting JavaScript code. You can check if your code is following our standards by running `gulp lint`, which will automatically lint all `.js` files as well as JavaScript snippets inside `.html` files.


## Contributing

  - Make sure your code is compliant with our code linters: `gulp lint`
  - Check that tests are passing: `polymer test`
  - [Submit a pull request](https://www.digitalocean.com/community/tutorials/how-to-create-a-pull-request-on-github) with detailed title and description
  - Wait for response from one of Vaadin components team members


## License

Commercial Vaadin Add-on License version 3 (CVALv3). For license terms, see LICENSE.

Vaadin collects development time usage statistics to improve this product. For details and to opt-out, see https://github.com/vaadin/vaadin-usage-statistics.
