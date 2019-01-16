### node-graceful-fs
---
https://github.com/isaacs/node-graceful-fs

```
var fs = require('graceful-fs')
fs.readFileSync('some-file-ro-whatever')

var realFs = require('fs')
var gracefulFs = require('graceful-fs')
gracefulFs.gracefulify(realFs)


```

```
```

```
```


