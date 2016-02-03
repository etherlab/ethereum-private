# Ethereum Private Blockchain
Deploy and use a private ethereum testnet where you can mine an test your dapps 
## Usage
Put geth on /usr/bin as a standalone in your ~/ folder

```
wget https://github.com/etherlab/ethereum-private/blob/master/genesis.json

```

On windows 
```
geth --rpc --rpccorsdomain="*" --networkid=14567 --maxpeers=3 --genesis genesis.json --datadir "%Appdata%\Roaming\Ethereum2" console

```
On linux 
```
./geth --rpc --rpccorsdomain="*" --networkid=14567 --maxpeers=3 --genesis genesis.json --datadir "~/.ethereum2" console
``` 
You can now mine and put contracts on a fake ethereum testnet

Cheers

