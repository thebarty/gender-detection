# Gender Detection

## Description
A node.js module to determine a person's gender based on his/her first name.
It works also for many languages other than english.

## Installation

    $ npm install gender-detection

Or using github:

    $ npm install git+https://git@github.com/davidemiceli/gender-detection.git

## Example
```javascript
// Require gender detection module
var gender = require('gender-detection');

// Use it to detect the gender:
g = gender.detect('Tim Johnson');
// "male"

g = gender.detect('Holly');
// "female"

g = gender.detect('GhJGhgj')
// "unknown"
```
