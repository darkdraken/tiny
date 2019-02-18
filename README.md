# tiny

The tiniest npm module

## install

```
$ npm install @draken/tiny
```

```js
const tiny = require('@draken/tiny');

tiny('So much space!');
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
