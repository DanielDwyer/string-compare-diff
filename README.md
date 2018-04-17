# string-compare-diff

**Stable LTS**

![Downloads](https://img.shields.io/npm/dw/string-compare-diff.svg)
![Downloads](https://img.shields.io/npm/dm/string-compare-diff.svg)
![Downloads](https://img.shields.io/npm/dt/string-compare-diff.svg)
![npm version](https://img.shields.io/npm/v/string-compare-diff.svg)
![License](https://img.shields.io/npm/l/string-compare-diff.svg)

What is Levenshtein Distance?
"In information theory, linguistics and computer science, the Levenshtein distance is a string metric for measuring the difference between two sequences. Informally, the Levenshtein distance between two words is the minimum number of single-character edits (insertions, deletions or substitutions) required to change one word into the other. It is named after the Soviet mathematician Vladimir Levenshtein, who considered this distance in 1965.[1]

Levenshtein distance may also be referred to as edit distance, although that term may also denote a larger family of distance metrics.[2]:32 It is closely related to pairwise string alignments."

- I found the above description at: https://en.wikipedia.org/wiki/Levenshtein_distance

The Levenshtein distance algorithm has been used in:

Spell checking
Speech recognition
DNA analysis
Plagiarism detection

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
compareStr.strSimilarity("Dan", "Daniel")
//returns 0.5
```
```js
compareStr.strSimilarity("America The Beautiful", "Canada")
//returns 0.14285714285714285
```
```js
compareStr.strSimilarity("Donald", "Trump")
//returns 0
```
## License

MIT
Copyright 2018 Daniel P. Dwyer

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
