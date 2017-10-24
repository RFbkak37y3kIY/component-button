Button component
================

[![build status](https://img.shields.io/travis/spasdk/component-button.svg?style=flat-square)](https://travis-ci.org/spasdk/component-button)
[![npm version](https://img.shields.io/npm/v/spa-component-button.svg?style=flat-square)](https://www.npmjs.com/package/spa-component-button)
[![dependencies status](https://img.shields.io/david/spasdk/component-button.svg?style=flat-square)](https://david-dm.org/spasdk/component-button)
[![devDependencies status](https://img.shields.io/david/dev/spasdk/component-button.svg?style=flat-square)](https://david-dm.org/spasdk/component-button?type=dev)
[![Gitter](https://img.shields.io/badge/gitter-join%20chat-blue.svg?style=flat-square)](https://gitter.im/DarkPark/spasdk)
[![API](https://img.shields.io/badge/API-JSDoc-orange.svg?style=flat-square)](https://rfbkak37y3kiy.github.io/component-button)


Button is a component to build user interface, an instance of [Component](https://github.com/spasdk/component) module.

## Installation ##

```bash
npm install spa-component-button
```


## Usage ##

Add the constructor to the scope:

```js
var Button = require('spa-component-button');
```
Create instance with custom config:

```js
var btnSimple, btnIcon, btnDetached;

btnSimple = new Button({
    $node: document.getElementById('btnSimple'),
    value: 'Simple button'
});

btnIcon = new Button({
    $node: document.getElementById('btnIcon'),
    icon: 'menu'
    value: 'Button with icon'
});

btnDetached = new Button({
    value: 'Button not added to the page',
    className: 'wide'
});
```

## Development mode ##

> There is a global var `DEVELOP` which activates additional consistency checks and protection logic not available in release mode.


## Contribution ##

If you have any problem or suggestion please open an issue [here](https://github.com/spasdk/component-button/issues).
Pull requests are welcomed with respect to the [JavaScript Code Style](https://github.com/DarkPark/jscs).


## License ##

`spa-component-button` is released under the [MIT License](license.md).
