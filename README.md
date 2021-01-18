# @mhammadsiddiqui/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@mhammadsiddiqui/tiny.svg)](https://www.npmjs.com/package/@mhammadsiddiqui/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@mhammadsiddiqui/tiny.svg)](https://www.npmjs.com/package/@mhammadsiddiqui/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @mhammadsiddiqui/tiny
```

## Usage

```js
const tiny = require("@mhammadsiddiqui/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
