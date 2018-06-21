# npm-togglehex
Converts hexadecimal color format to rgb.

# usage
```js
const hex = require('npm-togglehex');
let result = hex.toggleHex(string));
```
where <em>hex</em> and <em>result</em> could be named as you will and <em>string</em> stands for a string input.<br>
Input could be hexadecimal color format in the range <strong>#000000 - #FFFFFF</strong> or RGB in standart CSS notation: <strong>rgb(255,255,255)</strong>.<br>
The toggleHex function will detect the type of input and return the converted value.
