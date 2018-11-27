### bacon.js
---
https://github.com/baconjs/bacon.js

```
npm install baconjs
bower install bacon

npm run dist
script/dist flatmap combine takeutil
scripts/runtests flatmap combine takeutil
./test
./test core _ frompromise
./test-individually.js
npm install
npm install -g testem
testem
npm install
browsertest/browserify
open browsertest/mocha.runner.html
performance/PerformanceTest.coffee
performance/PerformanceTest.coffee flatmap
coffee --nodejs '--expose-gc' performanc/MemoryTest.coffee

npm install baconjs
```

```js
var clicks = $().asEventStream()






Bacon = require().Bacon
Bacon.sequentially().log()

define(function (require){
  var $ = require('jquery'),
      Bacon = require('Bacon');
  $.fn.asEventStream = Bacon.$.asEventStream;
  $(document).asEventStream('click').onValue(function (e){
    console.log(e.clientX + ', ' + e.clientY);
  });
});
```

```
```

