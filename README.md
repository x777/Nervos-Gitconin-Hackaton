# Nervos-Gitcoin-Hackathon

## Gitcoin hachaton completed tasks:

* ### Gitcoin: 0) Setup A Local CKB Node And CKB Indexer For The Testnet:
CKB NODE: 
![Screenshot of Local Node](https://github.com/x777/Nervos-Gitconin-Hackaton/blob/main/Setup%20a%20Local%20CKB%20Node%20and%20CKB%20Indexer/Local_node.png)

CKB INDEXER:
![Screenshot of Indexer](https://github.com/x777/Nervos-Gitconin-Hackaton/blob/main/Setup%20a%20Local%20CKB%20Node%20and%20CKB%20Indexer/Indexer.png)


* ### Gitcoin: 1) Create A Godwoken Account On The EVM Layer 2 Testnet

* A screenshot of the accounts you created (account list) in ckb-cli:
![Screenshot of account list](https://github.com/x777/Nervos-Gitconin-Hackaton/blob/main/Create%20A%20Godwoken%20Account%20On%20The%20EVM%20Layer%202%20Testnet/account_list.png)

* A link to the Layer 1 address you funded on the:
https://explorer.nervos.org/aggron/address/ckt1qyqz338jvphpp26x3fxfge7hurhzlfsut0xsymemnv

* A screenshot of the console output of successfully submitted a deposit to Layer 2:
![Screenshot of deposit Layer 2](https://github.com/x777/Nervos-Gitconin-Hackaton/blob/main/Create%20A%20Godwoken%20Account%20On%20The%20EVM%20Layer%202%20Testnet/deposit.png)


* ### Gitcoin: 2) Deploy A Simple Ethereum Smart Contract On Polyjuice

* A screenshot of the console output of successfully deployed a smart contract:
![Screenshot of deploy Smart Contract](https://github.com/x777/Nervos-Gitconin-Hackaton/blob/main/Deploy%20A%20Simple%20Ethereum%20Smart%20Contract%20On%20Polyjuice/deploy_contract.png)

* The transaction hash from the contract deployment (in text format):

```Transaction hash: 0x966eb7b0d121b8b438a3fd149172d78231a3b51ca1f0c3d1422c2d63738c358a```

* The deployed contract address from the contract deployment (in text format):

```Deployed contract address: 0xa1ad5F5A30c8acd9A073E15108c0bFC2d28b2690```


* ### Gitcoin: 3) Issue A Smart Contract Call To The Deployed Smart Contract

* A screenshot of the console output of  issued a smart contract call:
![Screenshot of deploy Smart Contract](https://github.com/x777/Nervos-Gitconin-Hackaton/blob/main/Issue%20A%20Smart%20Contract%20Call%20To%20The%20Deployed%20Smart%20Contract/output.png)

* The ```transaction hash```:
```0x44b4d3479f9622112bda52486447a1f65229cd0b12a2bbde9f6e08f07502341```

* The contract address:
```0xa1ad5F5A30c8acd9A073E15108c0bFC2d28b2690```

* ABI:
```[
    {
      "inputs": [],
      "stateMutability": "payable",
      "type": "constructor"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "x",
          "type": "uint256"
        }
      ],
      "name": "set",
      "outputs": [],
      "stateMutability": "payable",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "get",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    }
  ]
  ```


* ### Gitcoin: 4) Issue An SUDT Token On Layer 1 And Deposit It To Layer 2

* A link to the Layer 1 address you funded on the Testnet Explorer:
https://explorer.nervos.org/aggron/address/ckt1qyqz338jvphpp26x3fxfge7hurhzlfsut0xsymemnv

* A screenshot of the console output immediately after using sudt-cli to create your SUDT tokens on Layer 1:
![Screenshot of sudt-cli to create your SUDT](https://github.com/x777/Nervos-Gitconin-Hackaton/blob/main/Issue%20An%20SUDT%20Token%20On%20Layer%201%20And%20Deposit%20It%20To%20Layer%202/SUDT_output.png)

* A link to the transaction ID created by sudt-cli on the Testnet Explorer:
https://explorer.nervos.org/aggron/transaction/0xf1ec6c9eda1213c910053c5c616697fb6729902344148a342f6446da5bbd6f41

* A screenshot of the console output submitted a deposit to Layer 2 using the account-cli tool:
![Screenshot of submitted a deposit to Layer 2. Part 1](https://github.com/x777/Nervos-Gitconin-Hackaton/blob/main/Issue%20An%20SUDT%20Token%20On%20Layer%201%20And%20Deposit%20It%20To%20Layer%202/deposit_output_1.png)
![Screenshot of submitted a deposit to Layer 2. Part 2](https://github.com/x777/Nervos-Gitconin-Hackaton/blob/main/Issue%20An%20SUDT%20Token%20On%20Layer%201%20And%20Deposit%20It%20To%20Layer%202/deposit_output_2.png)



* The SUDT ID from the console output after executing the deposit script:
```Your sudt id: 152```


* ### Gitcoin: 5) Deploy The ERC20 Proxy Contract For The Deposited SUDT

* A screenshot of the console output immediately after deploying smart contract:
![Screenshot of deploying smart contract](https://github.com/x777/Nervos-Gitconin-Hackaton/blob/main/Deploy%20The%20ERC20%20Proxy%20Contract%20For%20The%20Deposited%20SUDT/deploy_SUDT-ERC20_output.png)

* The address of the ERC20 Proxy Contract you deployed:
```0x7Bc720b63ebb2CD72EEb48D3cEE704cc64A97736```

* A screenshot of the console output immediately after checking your SUDT balance:
![Screenshot of SUDT balance](https://github.com/x777/Nervos-Gitconin-Hackaton/blob/main/Deploy%20The%20ERC20%20Proxy%20Contract%20For%20The%20Deposited%20SUDT/balance_output.png)

* The Ethereum address that was checked:
```0x37C2b41ea4a10308d043F790493A3CdEc28585ae```


* ### Gitcoin: 6) Use Force Bridge To Deposit Tokens From Ethereum To Polyjuice

* A screenshot of the console output immediately after you have successfully generated your Deposit Receiver Address:
![Screenshot of generated your Deposit Receiver Address]()

* Your Deposit Receiver Address:
```ckt1q3dz2p4mdrvp5ywu4kk5edl2uc4p03puvx07g7kgqdau3n3dmypkqnxzuefxyp9wdghglncj77k5wt6p59sx6kukyjlwh5s467qgp8m25yqqqqqsqqqqqvqqqqqfjqqqqzafegh3quae5ef05a8xk85m0qtshe73yzk43zs59dx6kgr3slrm76gqqqqpqqqqqqcqqqqqxyqqqqx7asf60w8pqpte2sfcfn90fdfzxue7ff2g8sawe9wacnqat6jmygqngqqqqpxv9ejjvgz2u63w3l839aadguh5rgtqd4devf97a0fpt4uqsz0k5d7zks02fggrprgy8ausfyarehkzskz6uq9rqgqqqqqqcq8td4nj```

* The Ethereum address used to generate the Deposit Receiver Address:
```0x37C2b41ea4a10308d043F790493A3CdEc28585ae```

* A link to the Etherscan explorer for the successful Force Bridge transaction:
https://rinkeby.etherscan.io/tx/0xffc74fed5112ccf39dd6a7c9e1344748cd439407b3d2c760e8e172bbcf2eb6d1

* A link to the Nervos explorer for the successful Force bridge transaction:
https://explorer.nervos.org/aggron/transaction/0xc13e0bd63264e0ccd9fda5acaaa5e7d65b4c0ad4d1b25c59afb38581c94b33bd