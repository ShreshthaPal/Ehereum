# create my own Token in solidity 
This repository is made for ethereum beginner project which is used to create MY TOKEN using contracts

## Problem Statement

create a contract together to fulfill the following requirements:

1. Your contract will have public variables that store the details about your coin (Token Name, Token Abbrv., Total Supply)
2. Your contract will have a mapping of addresses to balances (address => uint)
3. You will have a mint function that takes two parameters: an address and a value. The function then increases the total supply by that number and increases the balance of the address by that amount.
4. Your contract will have a burn function, which works the opposite of the mint function, as it will destroy tokens. It will take an address and value just like the mint functions. It will then deduct the value from the total supply and from the balance of the address.
5. Lastly,  burn function should have conditionals to make sure the balance of account is greater than or equal to the amount that is supposed to be burned.

## Description
This program  written in Solidity by using a simple contract, solidity is a programming language used for developing smart contracts on the Ethereum blockchain.

1) For the first step we will create a contract with public variable that stores the details of the coins, it has 3 public access variable that contain
(Token Name,Token Abbreviation and Total supply).
2) The Token Name,Token Abbreviation will be string type and the total supply witll be unsigned integer type.
3) Now for the second step we will create a mapping of address to balances and make it public type, the working of the mpping is - if we pss an
   address it will return a token amount that the address has i.e. their balance.
4) Next we wil create a mint fuction with parameters address and value, Now we will increase the total supply by the amount provided using += operator.
5) Lastly we will create aburn function whose working is the total opposite of the mint function  i.e. it will detroy the tokens.
6) It will take address and value and deduct the value from the totalsuplly and the balance of the address.
           We should ensure that our burn function has a conditional statement ti ensure that the balnce of the account is greater than or equal
           to the amount that is supposed to be burned.
 



## Getting Started

### Executing Program

To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at (https://remix.ethereum.org/.)

Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., error.sol). Copy and paste the following code written by me into the file.

To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set heigher to "0.8.1" (or another compatible version), and then click on the "Compile error.sol" button.

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "MyToken1" contract from the dropdown menu, and then click on the "Deploy" button.

Once the contract is deployed, you can interact with it by passing the address. call any of the three function and set the value, and you can burn, mint or check the balance of your NFT.

## Author

SHRESHTHA PAL

## License

This project is licensed under the MIT License - see the LICENSE file for details
