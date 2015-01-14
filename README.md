# Supports

Modular feature detection library for CommonJS environments.

## Usage

```js
var supports = require('supports');

if (supports.touch) {
  // Touch device
} else {
  // No touch support :(
}

// Modular way
var supportsTouch = require('supports/touch');

if (supportsTouch) {
  // Touch device
} else {
  // No touch support :(
}
```
