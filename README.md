##  Apus ZKP Market

## Project Structure
<pre>
apus_service/
├── scripts/ :  contract lib 
│   ├── contract_lib.py: call for contract
│   ├── config.py: config.py
│   ├── ...
├── contracts: apus market contracts
├── migrations: truffle migrate scripts
├── truffle-config: truffle config
├── server.py: apus backend server main
├── requirement.txt: python dependencies
...
</pre>

### truffle:
`truffle migrate`

##  Usage:
export PYTHONPATH=$PYTHONPATH:.
python scripts/contract_lib.py


### contract config

> rpc_url https://sepolia-rpc.scroll.io

> chain_id 534351

> explore https://sepolia.scrollscan.com

|contract_name|contract_address||
|-|-|-|
|token|0xD104F12dD31066E0748A484f85A813CbFDd7aF6A||
|market|0x31C7d368cF5c1a0beC09bE18186C1465781a2D46||
|task|0xEbD34C9d02182161dADE02b480E68f94F6e8Da59||

### Token contract:
 https://sepolia.scrollscan.com/address/0xD104F12dD31066E0748A484f85A813CbFDd7aF6A

### market contract:
https://sepolia.scrollscan.com/address/0x31C7d368cF5c1a0beC09bE18186C1465781a2D46

### task contract:
https://sepolia.scrollscan.com/address/0xEbD34C9d02182161dADE02b480E68f94F6e8Da59

