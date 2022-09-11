# **tiny** ⚛️

![npm (scoped)](https://img.shields.io/badge/npm-v1.0.0-blue?style=plastic&logo=npm)

**tiny** - My very first **npm package**.

tiny removes all spaces from a string, using the `tiny` function.

## **Install**

```
$ npm install @tyler.engineer/tiny
```

## **Usage**

```js
const tiny = require('@tyler.engineer/tiny');

tiny('So much space!');
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```

## **Dev**

```
Tyler Nilsson
```
