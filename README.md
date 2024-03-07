# flow1

## Struct Challenge: Smart Contract with Struct

In this project, I have created a smart contract that includes a custom Struct. The smart contract allows adding instances of the Struct to an array and provides a function to add new instances.

## Smart Contract Details

The smart contract is written in Solidity and consists of the following components:

1. **Struct**: I have defined a custom Struct named `Item` inside the contract.

2. **Array**: An array named `itemList` is used to store instances of the `Item` Struct.

3. **Function**: The contract includes a function named `addItem` to add new instances of the `Item` Struct to the `itemList` array.

## How to Use

To interact with the smart contract and test its functionality, follow these steps:

1. Deploy the smart contract to an Ethereum network using a tool like Remix or Truffle.

2. Use a suitable Ethereum wallet (e.g., MetaMask) to connect to the Ethereum network where the contract is deployed.

3. Call the `addItem` function with appropriate parameters to add new instances of the `Item` Struct to the `itemList` array.

4. You can retrieve the list of items stored in the `itemList` array using suitable methods provided by the Ethereum development framework you are using.

## File Structure

- **`StructChallenge.sol`**: Solidity smart contract file containing the definition of the contract with the Struct and function.
  
## Technologies Used

- Solidity: Used to define the smart contract.
- Ethereum: Used for deploying and interacting with the smart contract.
- Ethereum Development Frameworks: Remix, Truffle, etc., for contract deployment and interaction.
- MetaMask: Ethereum wallet for transaction handling.
