# color

color parse and format util

[![color](https://nodei.co/npm/modulex-color.png)](https://npmjs.org/package/modulex-color)
[![NPM downloads](http://img.shields.io/npm/dm/modulex-color.svg)](https://npmjs.org/package/modulex-color)
[![Build Status](https://secure.travis-ci.org/modulex/color.png?branch=master)](https://travis-ci.org/modulex/color)
[![Coverage Status](https://img.shields.io/coveralls/modulex/color.svg)](https://coveralls.io/r/modulex/color?branch=master)
[![Dependency Status](https://gemnasium.com/modulex/color.png)](https://gemnasium.com/modulex/color)
[![node version](https://img.shields.io/badge/node.js-%3E=_0.10-green.svg?style=flat-square)](http://nodejs.org/download/)


## example

```javascript
var Color = require('modulex-color');
describe('color', function () {
    it('parse rgba right', function () {
        var rgba = Color.parse('rgba(1,2,3,0.4)');
        rgba.getR()//1
        rgba.getG()//2
        rgba.getB()//3
        rgba.getA()//4
    });
});
```