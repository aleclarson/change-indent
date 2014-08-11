# change-indent [![NPM version](https://badge.fury.io/js/change-indent.png)](http://badge.fury.io/js/change-indent)

> Change the indentation in a string.

## Install
#### Install with [npm](npmjs.org):

```bash
npm i change-indent --save-dev
```

## Usage

```js
var changeIndent = require('change-indent');
change(string, indent);
```

* `string` **{String}** pass the string you want to re-indent
* `indent` **{Number}** the amount of indentation

**Example:**

```js
var changeIndent = require('change-indent');
change('  abc', 4);

//=> '    abc'
```

## Author

**Jon Schlinkert**
 
+ [github/jonschlinkert](https://github.com/jonschlinkert)
+ [twitter/jonschlinkert](http://twitter.com/jonschlinkert) 

## License
Copyright (c) 2014 Jon Schlinkert, contributors.  
Released under the MIT license

***

_This file was generated by [verb-cli](https://github.com/assemble/verb-cli) on August 11, 2014._
