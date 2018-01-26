# Async Sleep NodeJS

0x0a0d
## Usage

```javascript
const sleep = require('simple-sleep-async');
async function demoSleep() {
  let _time = Date.now();
  console.log(_time);
  await sleep(5000); // 5s
  console.log(Date.now(), Date.now() - _time);
}

demoSleep();
```