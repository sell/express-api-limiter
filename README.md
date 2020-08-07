# What is this?

`Express-api-limiter, is a package that limits a request to an ip`

# Installation

`npm i express-api-limiter`


Then...

```
const iplimiter = require('express-ip-limiter')
const ip = iplimiter.iplimiter

app.post('/important', ip('1234'), (req, res, next) => {
    res.json({
        message: 'success'
    )}
})
```

## Options

* `ip('<enter an ip>')`

