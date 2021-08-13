





# Nervos Hackerthon - Gitcoin 3

1. A screenshot of the console output immediately after you have successfully issued a smart contract call.

   ![Deployed smart contract](https://github.com/my-Gem/ckb/blob/main/call_contract.png)

2. The transaction hash from the console output (in text format).

```3
0x6a55037943aa1aafe5f2af801e25488817a43005e398e5fd73a1fc2fa1ae5a0d
```

3. The contract address that you called (in text format).

```
0x0dEc9CA6022DbA15b10ABaBE1F7A33E397E58E29
```

4.The ABI for contract you made a call on (in text format).

```
[
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



