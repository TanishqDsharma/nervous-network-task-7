# nervous-network-task-7

## Screenshots or video of your application running on Godwoken:

1)Deploy contract by clicking on "deploy contract button"

![alt text](https://github.com/TanishqDsharma/nervous-network-task-7/blob/main/task7.png)

2) Deployed contract:

![alt text](https://github.com/TanishqDsharma/nervous-network-task-7/blob/main/task7.1.png)

3)List Tasks:

![alt text](https://github.com/TanishqDsharma/nervous-network-task-7/blob/main/task7.2.png)


### Link to the GitHub repository with your application which has been ported to Godwoken. This must be a different application than the one covered in this guide.

Github Repo: https://github.com/TanishqDsharma/nervous-network-task-7/tree/main/Dapp

### If you deployed any smart contracts as part of this tutorial, please provide the transaction hash of the deployment transaction, the deployed contract address, and the ABI of the deployed smart contract. (Provide all in text format.)

<b>Deployed Contract Address:</b> 0x0C90DEdAe155C09c07Adb8d86ef88eAA3fd2e796

<b>Deployed transaction hash:</b> 

ABI code:

```
"abi": [
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
      "name": "TaskCompleted",
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
      "name": "TaskCreated",
      "type": "event"
    },
    {
      "inputs": [],
      "name": "taskCount",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    }]
```


