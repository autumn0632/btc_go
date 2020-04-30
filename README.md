# Blockchain in Go
命令行参数
>Usage:\
createblockchain -address ADDRESS - Create a blockchain and send genesis block reward to ADDRESS\
createwallet - Generates a new key-pair and saves it into the wallet file\
getbalance -address ADDRESS - Get balance of ADDRESS\
listaddresses - Lists all addresses from the wallet file\
printchain - Print all the blocks of the blockchain\
reindexutxo - Rebuilds the UTXO set\
send -from FROM -to TO -amount AMOUNT -mine - Send AMOUNT of coins from FROM address to TO. Mine on the same node, when -mine is set.\
startnode -miner ADDRESS - Start a node with ID specified in NODE_ID env. var. -miner enables mining\


快速上手
>1.先使用`createwallet`命令创建多个钱包\
2.通过命令`createblockchain`新建一条blackchain，绑定个一个钱包上\
3.进行转账测试


A blockchain implementation in Go, as described in these articles:

1. [Basic Prototype](https://jeiwan.cc/posts/building-blockchain-in-go-part-1/)
2. [Proof-of-Work](https://jeiwan.cc/posts/building-blockchain-in-go-part-2/)
3. [Persistence and CLI](https://jeiwan.cc/posts/building-blockchain-in-go-part-3/)
4. [Transactions 1](https://jeiwan.cc/posts/building-blockchain-in-go-part-4/)
5. [Addresses](https://jeiwan.cc/posts/building-blockchain-in-go-part-5/)
6. [Transactions 2](https://jeiwan.cc/posts/building-blockchain-in-go-part-6/)
7. [Network](https://jeiwan.cc/posts/building-blockchain-in-go-part-7/)
