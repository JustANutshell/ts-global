# ts-global
A easy way to use global variables in Typescript.

### Usage
-----
File 1:
```js
const glo = require("ts-global");
glo.test = 1234;
```
File 2:
```js
const glo = require("ts-global");
console.log( glo.test ); // 1234
```
