# pause
sleep – блокирующий код для экспериментов

```JavaScript
module.exports = (y = 10000, x = Date.now()) => { while (Date.now() - x < y) ;};
// pause(5000)
// const pause = require('goss_pause');
```
