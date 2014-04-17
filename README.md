crc32
===
CRC-32 C++ module for Node.js

### Installation
    node-gyp configure build

### Usage

```javascript

var crc32 = require('./crc32');

//create
crc32.new('Hello world');  //=> 461707669

//update
var a = crc32.new('Hello ');  //=> 3928882368
crc32.new('world', a);  //=> 461707669

```
