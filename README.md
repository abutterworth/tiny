# @abutterworth/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@abutterworth/tiny.svg)](https://www.npmjs.com/package/@abutterworth/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@abutterworth/tiny.svg)](https://www.npmjs.com/package/@abutterworth/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @abutterworth/tiny
```

## Usage

```js
const tiny = require("@abutterworth/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```