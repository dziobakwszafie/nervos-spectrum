1. A screenshot of the console output immediately after you have successfully issued a smart contract call.![callSuccess](https://user-images.githubusercontent.com/51861246/128774056-f7b98924-e20b-49c6-bc5f-64a6f4b9a5ae.PNG)

2. The transaction hash from the console output (in text format).
0xb3ddb1c0603202352a66c7e43a86b906503be24e8e747c9a7954b6a4884e86b4
3. The contract address that you called (in text format).
0x8cbf2253615045625c6F595603708f2d9eFA3f4b
4. The ABI for contract you made a call on (in text format).
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
