# @oriash93/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@oriash93/tiny.svg)](https://www.npmjs.com/package/@oriash93/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@oriash93/tiny.svg)](https://www.npmjs.com/package/@oriash93/tiny)

Removes all spaces from a string.

## Install

```shell
npm install @oriash93/tiny
```

## Usage

```js
const tiny = require("@oriash93/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
