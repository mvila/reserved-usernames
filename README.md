# reserved-usernames [![npm version](https://img.shields.io/npm/v/reserved-usernames.svg)](https://www.npmjs.com/package/reserved-usernames)

List of reserved usernames to prevent URL collision with resource paths.

Credit: [shouldbee/reserved-usernames](https://github.com/shouldbee/reserved-usernames).

## Installation

```
npm install --save reserved-usernames
```

## Example

```javascript
var usernames = require('reserved-usernames');

console.log(usernames.indexOf('admin') !== -1); // => true
```

## License

MIT
