

## Installation

```
git clone https://github.com/sthnaqvi/explorer
npm install
bower install
npm start
```

Make sure to install geth as well for the ETH explorer to be able to function. Then run:
```
geth --rpc --rpcaddr localhost --rpcport 8545 --rpcapi "web3,eth" --rpccorsdomain "http://localhost:8000"
```

Then visit http://localhost:8000 in your browser of choice after you npm start the explorer

