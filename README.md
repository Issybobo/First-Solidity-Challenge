FirstChallenge Smart Contract Solution

This repository contains a simple smart contract solution named FirstChallenge written in Solidity. The contract declares four different types of variables and provides getter and setter functions for each variable.

Contract Details
The FirstChallenge contract is designed to showcase the usage of getter and setter functions for various types of variables.

Variables
symbol (string): A public string variable to store a symbol.
number (int): A public integer variable to store a number.
value (uint): A public unsigned integer variable to store a value.
read (string): A public string variable to store a read value.

Functions
For each variable, the contract provides both getter and setter functions.
setsymbol(string memory _symbol): Sets the value of the symbol variable.
getsymbol(): Returns the value of the symbol variable.
setNumber(int _number): Sets the value of the number variable.
getNumber(): Returns the value of the number variable.
setValue(uint _value): Sets the value of the value variable.
getValue(): Returns the value of the value variable.
setRead(string memory _read): Sets the value of the read variable.
getRead(): Returns the value of the read variable.

How to Use

Clone this repository to your local machine.
Make sure you have a development environment set up to compile and deploy Solidity contracts (e.g., Remix, Truffle, Hardhat).
Deploy the FirstChallenge contract to your chosen development network.
Interact with the contract by using the provided getter and setter functions to manipulate the variables.
Example Usage
Deploy the FirstChallenge contract to your chosen development network.
Use the setter functions to set values for the variables.
Use the getter functions to retrieve and verify the stored values.
License
This project is licensed under the MIT License. See the LICENSE file for details.

