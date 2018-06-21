# npm-togglehex
Converts hexadecimal color format to rgb.

# usage
Install the npm package.
```
npm install npm-togglehex --save
```

Add this to your JavaScript code.

```js
const hex = require('npm-togglehex');
let result = hex.toggleHex(string));
```
<em>hex</em> and <em>result</em> could be named as you wish and <em>string</em> stands for a string input.<br>
Input could be hexadecimal color format: <strong>#FFFFFF</strong> or RGB in standart CSS notation: <strong>rgb(255,255,255)</strong>.<br>
The toggleHex function will detect the type of input and return the converted value.
