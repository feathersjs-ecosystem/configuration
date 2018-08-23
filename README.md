# @feathersjs/configuration

> __Important:__ The code for this module has been moved into the main Feathers repository at [feathersjs/feathers](https://github.com/feathersjs/feathers) ([package direct link](https://github.com/feathersjs/feathers/tree/master/packages/socketio)). Please open issues and pull requests there.

[![Build Status](https://travis-ci.org/feathersjs/configuration.png?branch=master)](https://travis-ci.org/feathersjs/configuration)

A small configuration module for your Feathers application.

## About

`@feathersjs/configuration` is a module that wraps [node-config](https://github.com/lorenwest/node-config) to configure your Feathers application.

> npm install @feathersjs/configuration

```js
const feathers = require('@feathersjs/feathers');
const configuration = require('@feathersjs/configuration');

// Use the application root and `config/` as the configuration folder
let app = feathers().configure(configuration())
```

See the [Feathers configuration docs](https://docs.feathersjs.com/api/configuration.html) for the full API usage.

## License

Copyright (c) 2018

Licensed under the [MIT license](LICENSE).
