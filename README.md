# Napi Demo

[![npm version](https://badge.fury.io/js/%40hrwg%2Fnapi-demo.svg)](https://badge.fury.io/js/%40hrwg%2Fnapi-demo)

This package serves as a demo on how to build a Node.js addon using C++
and how to publish it to npm.

## Pre-requisites
This package has been built and tested using the following specifications:
* Kali Linux 2022.2 (64-bit) via WSL 2
* Node.js 16.15.0
* npm 8.13.2
* gcc 11.3.0
* node-gyp 9.1.0

## Installation
The package can be installed via:
```bash
npm i @hrwg/napi-demo
```

## Usage
In order to use the package, require it in your JavaScript application:
```js
const demo = require('@hrwg/napi-demo');

console.info(demo); // Output: {}
```

Since the package does not have any actual functionality, the purpose of importing
it, is to test, if the binary file works.

## Testing
JavaScript tests can be executed via:
```bash
npm t
```

## License
MIT
