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
  ]```

