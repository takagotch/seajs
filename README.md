### seajs
---
https://github.com/seajs/seajs

```js
seajs.config({
  base: "../sea-modules/",
  alias: {
    "jquery": "jquery/jquery/1.10.1/jquery.js"
  }
})
seajs.use("../static/hello/src/main")

define(function(require, exports, modules){
  var $ = require('jquery');
  var Spinning = require('./spinning');
  exports.doSomeghing = ...
  module.exports = ...
});
```

```
npm instal spm@2.x -g
npm install spm-build -g

cd static/hello
make build
make deploy
```

```
```


