# Web3_PyStorage_Application
## A python script that deploys a smart contract to a blockchain (utilising Ganache to create a local blockchain) working more with private keys, creating transactions, signing transactions and sending transactions.

###### - Deploying to our own local blockchain (either using Ganache with the UI or ganache-cli)
###### - Deploying to a testnet (Utilising Infura)
###### - Deploying to a mainnet working more with private keys, creating transactions, signing transactions and sending transactions verifying the transactions using a tool such as Etherscan.

###### - Added the .env as an example of how it would be integrated in a smart contract deployed to an active blockchain on the mainnet. In an actual mainnet smart contract, the .gitignore would keep the .env file out which would store sensitive information such as the private_keys of wallets connected to the smart contract such as the contract owners private key. Never reveal your private key or upload it onto a platform where it can be read in the source code (hence why we don't hardcode it into the script but put it into a .env file).
