# nervous-network-task-7

## Screenshots or video of your application running on Godwoken:

1)Deploy contract by clicking on "deploy contract button"

  ![alt text](https://github.com/TanishqDsharma/nervous-network-task-7/blob/main/task7.png)


2)Deployed Contract:

  ![alt text](https://github.com/TanishqDsharma/nervous-network-task-7/blob/main/task7.1.png)


  ![alt text](https://github.com/TanishqDsharma/nervous-network-task-7/blob/main/task7.2.png)


3)Get Music Library:

  ![alt text](https://github.com/TanishqDsharma/nervous-network-task-7/blob/main/task7.3.png)




### Link to the GitHub repository with your application which has been ported to Godwoken. This must be a different application than the one covered in this guide.

Github Repo: https://github.com/TanishqDsharma/Task7dapp
### If you deployed any smart contracts as part of this tutorial, please provide the transaction hash of the deployment transaction, the deployed contract address, and the ABI of the deployed smart contract. (Provide all in text format.)

<b>Deployed Contract Address:</b> 0x714754b096bA8873A24Cc15F8633175d89aB784A
ABI code:

```
[
    {
      "inputs": [],
      "stateMutability": "nonpayable",
      "type": "constructor"
    },
    {
      "anonymous": false,
      "inputs": [
        {
          "indexed": false,
          "internalType": "uint256",
          "name": "id",
          "type": "uint256"
        },
        {
          "indexed": false,
          "internalType": "bool",
          "name": "completed",
          "type": "bool"
        }
      ],
      "name": "musicCompleted",
      "type": "event"
    },
    {
      "anonymous": false,
      "inputs": [
        {
          "indexed": false,
          "internalType": "uint256",
          "name": "id",
          "type": "uint256"
        },
        {
          "indexed": false,
          "internalType": "string",
          "name": "content",
          "type": "string"
        },
        {
          "indexed": false,
          "internalType": "bool",
          "name": "completed",
          "type": "bool"
        }
      ],
      "name": "musicCreated",
      "type": "event"
    },
    {
      "inputs": [],
      "name": "musicCount",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "name": "musics",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "id",
          "type": "uint256"
        },
        {
          "internalType": "string",
          "name": "content",
          "type": "string"
        },
        {
          "internalType": "bool",
          "name": "completed",
          "type": "bool"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    },
    {
      "inputs": [
        {
          "internalType": "string",
          "name": "_content",
          "type": "string"
        }
      ],
      "name": "createMusic",
      "outputs": [],
      "stateMutability": "nonpayable",
      "type": "function"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "_id",
          "type": "uint256"
        }
      ],
      "name": "toggleCompleted",
      "outputs": [],
      "stateMutability": "nonpayable",
      "type": "function"
    }
  ]
```


