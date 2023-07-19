# Project: Create-a-Token
A sample Token created in Solidity on Remix IDE  , made for Solidity Beginners Assesment on the Metacrafters learning platform.

## Description

This program is a simple contract written in Solidity, a programming language used for developing smart contracts on the Ethereum blockchain. The contract has
the following functions :-

(1) Public variables that store the details of my sample coin.

(2) A mapping of addresses to balance.

(3) A mint function that takes two parameters: an address and a value. The function then increases the total supply by that number and increases the balance of the address by that amount.

(4) A burn function, which works the opposite of the mint function, as it will destroy tokens.

(5) Lastly, burn function has conditionals to make sure the balance of account is greater than or equal to the amount that is supposed to be burned.

## Getting Started

### Executing program

To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., HelloWorld.sol). Copy and paste the code from solidity-project.sol file into your file:

```javascript
pragma solidity ^0.8.18;

contract SampleCode {
    function sayJustSampleCode() public pure returns (string memory) {
        return "Sample!";
    }
}

```

To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to latest solidity version (or another compatible version), and then click on the "Compile" button.

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the your contract from the dropdown menu, and then click on the "Deploy" button.

Once the contract is deployed, you can interact with it by calling the mint, burn function and much more.

## Authors

Tanishq

## License

This project is licensed under the MIT License - see the LICENSE.md file for details
