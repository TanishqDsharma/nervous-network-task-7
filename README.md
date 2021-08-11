# nervous-network-task-7

## Screenshots or video of your application running on Godwoken:

![alt text](https://github.com/TanishqDsharma/nervous-network-task-7/blob/main/dapp.png)

### Link to the GitHub repository with your application which has been ported to Godwoken. This must be a different application than the one covered in this guide.

Github Repo: https://github.com/TanishqDsharma/nervous-network-task-7/tree/main/Dapp

### If you deployed any smart contracts as part of this tutorial, please provide the transaction hash of the deployment transaction, the deployed contract address, and the ABI of the deployed smart contract. (Provide all in text format.)

Deployed Contract Address: 0x905AF1978e68e2078f62E19c45ca8034109c9098
Deployed transaction hash: 0x0636d3eafc80e659dd02487ba02886ff647f4477d580d15e2b102a5ba948d71a

ABI code:

```
"abi": [
    {
      "inputs": [
        {
          "internalType": "string",
          "name": "name_",
          "type": "string"
        },
        {
          "internalType": "string",
          "name": "symbol_",
          "type": "string"
        }
      ],
      "stateMutability": "nonpayable",
      "type": "constructor"
    },
    {
      "anonymous": false,
      "inputs": [
        {
          "indexed": true,
          "internalType": "address",
          "name": "owner",
          "type": "address"
        },
        {
          "indexed": true,
          "internalType": "address",
          "name": "spender",
          "type": "address"
        },
        {
          "indexed": false,
          "internalType": "uint256",
          "name": "value",
          "type": "uint256"
        }
      ],
      "name": "Approval",
      "type": "event"
    }]
```


