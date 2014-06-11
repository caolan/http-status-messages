Maps HTTP status codes to human-readable short descriptons. Data taken from
Wikipedia: http://en.wikipedia.org/wiki/HTTP_status_codes

```js
var msgs = require('http-status-messages');
var assert = require('assert');

assert.equal(msgs[200], "OK");
assert.equal(msgs[404], "Not Found");
assert.equal(msgs[502], "Bad Gateway");
```
