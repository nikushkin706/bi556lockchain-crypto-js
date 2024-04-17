```
# Blockchain and Cryptography Package

This package provides a basic implementation of a blockchain and cryptography functionalities in JavaScript.

## Installation

You can install the package via npm:

```bash
npm install bi556lockchain-crypto-js
```

## Usage

```javascript
const { Blockchain, Block } = require('bi556lockchain-crypto-js');

// Create a new blockchain
const myBlockchain = new Blockchain();

// Add a new block to the blockchain
myBlockchain.addBlock(new Block(1, "02/01/2022", { amount: 4 }));

// Check if the blockchain is valid
console.log("Is blockchain valid?", myBlockchain.isChainValid());
```

## Features

- **Blockchain**: Implements a basic blockchain structure with blocks linked through cryptographic hashes.
- **Block**: Represents an individual block in the blockchain with data and timestamps.
- **Cryptography**: Utilizes SHA-256 hashing algorithm for block validation and security.

## Contributing

Contributions are welcome! Please feel free to submit issues or pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```
