# Dummy say

> Tell The dummy what to say

Made from [yosay](https://github.com/yeoman/yosay)


## Install

```
$ npm install --save dummysay
```


## Usage

```js
var dummysay = require('dummysay');

console.log(dummysay('Hello, and welcome to my fantastic generator full of whimsy and bubble gum!'));

/*

|¯¨´  `¨¯|    .-----------------------.
\ `    ´ /    |      This script      |
 \ `  ´ /     |      will output      |
  ' `´ '      |  something like this  |
 / ´  ` \     | dummy-team.github.io  |
| dummy `|    '-----------------------'
`~------~´


*/
```

*You can style your text with [chalk](https://github.com/sindresorhus/chalk) before passing it to `dummysay`.*


## CLI

```
$ npm install --global dummysay
```

```
$ dummysay --help

  Usage
    dummysay <string>
    dummysay <string> --maxLength 8
    echo <string> | dummysay

```


## License

[BSD license](http://opensource.org/licenses/bsd-license.php)
Copyright (c) Google
