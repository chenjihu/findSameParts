# findSameParts
Find the same parts from two given strings

## Install

```bash
$ npm install find-same-parts
```

## Usage

```javascript
var findSameParts = require('find-same-parts');

findSameParts('hello world', 'Hello world'); //  ['ello world']
findSameParts('hello world', 'Hello world', {ignoreCase: true});  //  ['hello world']

findSameParts('hello world, bot', 'hello somebody, bot'); // ['hello', 'bot']
findSameParts('hello world, bot', 'hello somebody, bot', {minStrLength: 4}); ['hello']
```
