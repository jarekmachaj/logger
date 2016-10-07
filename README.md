fast logger
=========

Very simple node logger with console colors

## Installation
  ```bash
  $ npm install fast-logger
  ```

## Usage
```javascript
var diff = require('fast-logger');
```

## Examples  
```javascript
var logger = require('../index');
logger.settings.logging = true;
logger.log("Hello from logger");
logger.log("Info message from logger", "INFO");
logger.log("Warning message from logger", "WARN");
logger.log("Error message from logger", "ERROR");
```

## Tests uages (will output few lines of log)
  ```bash
  $ npm test
  ```
