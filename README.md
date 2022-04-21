# @queen-esther/test

![npm (scoped)](https://img.shields.io/npm/v/@queen-esther/test)

Removes all spaces from a string.

## Install

```
npm install @queen-esther/test
```
## Usage

```
const tiny = require("@queen-esther/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```