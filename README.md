# etherchain-node
Node JS api for the Ethereum blockchain to get all the blocks and transactions done under etherium.

### Installation

```
npm install etherchain
```

### Instance

```
var etherchain = require('etherchain');
```
### Usage

```
etherchain.method(<args>).then(function(response) {
		//Results here
	});
```

### Methods
Refer to the [Etherchain API](https://etherchain.org/apidoc) to know about each output and explanation
```
getBasicStats()
getBlocks(offset, count)
getBlock(id)
getBlockTransaction(id)
getTransaction(id)
getAccount(id)
getAccountTransaction(id, offset)
```

### Run project
``` 
To run the project go to command prompt and run 'node app.js' command.
```
