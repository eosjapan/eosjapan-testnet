# eosjapan-testnet

This is JEDA EOS testnet of EOSIO Dawn3.0

Telegram: https://t.me/eosjapan

### How to join JEDA testnet
#### Run node on your server
Create a key pair for your node
```console
~$ cleos create key
Private key: <your_private_key>
Public key: <your_public_key>
```

Then run:
```console
nodeos --producer-name <your_producer_name> --plugin eosio::chain_api_plugin 
\ --plugin eosio::net_api_plugin 
\ --http-server-address 127.0.0.1:8880 --p2p-listen-endpoint 127.0.0.1:9870 
\ --p2p-peer-address 52.69.51.158:9876 
\ --config-dir <your_producer_name> --data-dir <your_producer_name> 
\ --private-key [\"<your_public_key>\",\"<your_private_key>\"]
```
Please choose your producer name from Japanese goldfish catagory(http://www.samurai-goldfish.net)

Now you are connected to JEDA testnet. you will see something like this:
```console
push block #815446 from goldfish 2018-04-19T21:55:58.500  000c71560edee5f525ef84b6bf7c9f460f672284e4fd8be335faf14ba3e54266 lib: 815439 success
push block #815447 from goldfish 2018-04-19T21:55:59.000  000c7157d5c6780173ddcc853d4f494a98ec38303988d1190157a7e7c445dc6b lib: 815439 success
push block #815448 from goldfish 2018-04-19T21:55:59.500  000c71580a4e8ef58344e8bec7655a620f9768c2c890be498ee6a5a71c0be157 lib: 815439 success
push block #815449 from goldfish 2018-04-19T21:56:00.000  000c71595fdd8d580d2c1d45545dc71bc2191c15e41e14525025c2d9b25930f0 lib: 815439 success
push block #815450 from goldfish 2018-04-19T21:56:00.500  000c715a5d1376987b9cff16ccb6e32b1cf620c79b28895fa5bf92a6f3a3b42a lib: 815439 success
push block #815451 from goldfish 2018-04-19T21:56:01.000  000c715ba1ce752ce960bb45a3da6af7a0131725751e8946498c6def5beebf24 lib: 815439 success
```

Wait until synchronized the data as a full node.

#### Submit your node
Submit a issue or contact us on telegram with following information:
 * Organization name
 * Server location
 * Producer name
 * IP/DOMAIN:PORT
 * Your public key
 
After receving your requst, we will add your node as a block producer.

