# string-compare-diff

**Stable LTS**

![Downloads](https://img.shields.io/npm/dw/string-compare-diff.svg)
![Downloads](https://img.shields.io/npm/dm/string-compare-diff.svg)
![Downloads](https://img.shields.io/npm/dt/string-compare-diff.svg)
![npm version](https://img.shields.io/npm/v/string-compare-diff.svg)
![License](https://img.shields.io/npm/l/string-compare-diff.svg)

This simple and fast module provides the capability to easily compare two strings. Returned is a number between 0 and 1 that represents exactly how much the strings appeared alike/different.

## Getting Started

#### Install it via npm:

```shell
npm i string-compare-diff
```

#### Require the Module:
```shell
const compareStr = require('string-compare-diff')
```

#### Example Useage
```js
compareStrings.strSimilarity("Dan", "Daniel")
//returns 0.5
```
```js
compareStrings.strSimilarity("America The Beautiful", "Canada")
//returns 0.14285714285714285
```
```js
compareStrings.strSimilarity("Donald", "Trump")
//returns 0
```
## License

MIT
Copyright 2018 Daniel P. Dwyer

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
