# @ameemarks/tiny

Removes all spaces from a string.

## Install

```
$ npm install @ameemarks/tiny
```

## Usage

```
const tiny = require("@ameemarks/tiny");

tiny("Too many spaces here!");
// => "Toomanyspaceshere!"

tiny(1357);
// => Uncaught TypeError: Tiny wants a string!
//  at tiny (<anonymous>: 2:41)
//  at (<anonymous>: 1:1)
```
