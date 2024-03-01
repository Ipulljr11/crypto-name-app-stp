# Crypto Name App

Crypto Name App is a Node.js module that utilizes the `crypto-name-generator-stp` module to generate unique names related to cryptocurrency.

## Installation

To use Crypto Name App in your Node.js project, simply install it via npm:

```bash
npm install crypto-name-app-stp
```

## Usage

Once installed, you can use Crypto Name App in your project like this:

```javascript
const cryptoNameGenerator = require('crypto-name-app-stp');

// Generate a unique crypto name
const name = cryptoNameGenerator();
console.log('My unique crypto name is:', name);
```

The `cryptoNameGenerator()` function internally uses the `crypto-name-generator-stp` module to generate a unique name related to cryptocurrency.

