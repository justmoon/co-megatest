This package wraps [megatest](https://github.com/floby/megatest) in order to allow you to use it with the yield keyword and co:

# Usage

```
const megatest = require('co-megatest')
let result = yield megatest(app).get(url).end()
```

# Install

```
npm install --save-dev co-megatest megatest
```

# Acknowledgement

This wrapper was originally created by [avbel](https://github.com/avbel) for the [supertest](https://github.com/visionmedia/supertest) package. Thanks to [Floby](https://github.com/Floby) for creating the supertest fork [megatest](https://github.com/floby/megatest).
