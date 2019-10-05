# blockchain

This project is a simple blockchain application written in the Go programming language.

Functionalities:

* Create a wallet for your coins (which generates a new address)
* List the addresses on the machine
* Create blockchain with the rewards of mining the genesis block going to the specified address
* Get balance of an address
* Print the blockchain
* Transfer coins from one account to another (the transaction gets mined into a block either at the local node or the miner node)
* Reindex the UTXO structure (i.e. reload the unspent transactions)
* Start a node to connect to the blockchain network (thus updating the blockchain and potentially serving as a miner/central node)

See usage info by running `go run main.go`

This project is based on the tutorial found [here](https://github.com/tensor-programming/golang-blockchain)
