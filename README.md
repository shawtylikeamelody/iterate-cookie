# Iterate-Cookie

## Example:

```javascript
var Cookie = require('./index.js'),
  cookie = new Cookie('foo=bar;');
  
cookie.value = 'kitty';
console.log(cookie.serialize()); // Outputs foo=kitty;
```

## Parameters:
  - `cookie.domain` **[String][51]?** Domain
