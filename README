# solidityFinalProject

This solidity program is the final submission of ETH:BEGINNER course ,it covers creating public variables, mapping addresses, minting and burning tokens, and using conditionals.
Simple overview of use/purpose. This solidity program acts as a starting point to learn about Solidity and eager to know how it works.

## Description

the program is written in solidity , a programming language to create smart contracts on the Ethereum blockchain, 
the contract has two functions which mint the tokens and burn the tokens

## Getting Started

### Installing

You don't need to install anything ,all you need is internet connection and a supported broweser.you can run this program on remix IDE which is an online solidity IDE,here is the link to the website https://remix.ethereum.org/.

once you are on the Remix website, create a new file by clicking on the "+" icon. Save the file with a .sol extension(solidityFinalProject.sol).

copy, paste and run the following code

### Executing program
- open the Remix ide.
- copy the following code

  contract MyToken {
```
// public variable here
```
   

    string public tokenName = "INIFINITY";
    string public tokenAbbrv = "INIF";
    uint public totalSupply = 0;

```
mapping variable here
```
    
    mapping(address => uint) public balances;  //(key=>value) here we are mapping the balance

```
// mint function
//it will have address and value
```
    function mint (address _address, uint _val) public {
        totalSupply += _val;
        balances[_address]  += _val; //balance of the address + valuw  
    }
```
//burn function
//now we will create a function which destroys the tokens 
```
  
    //now we will create a function which destroys the tokens 

    function burn (address _address, uint _val) public  {
         if(balances[_address] >= _val){  //balance should be greater than or equal to the amount which is supposed to be burned 
        totalSupply -= _val;
        balances[_address] -= _val;
        }
    }
    }



## Authors

Rahul Jain
jainrahul98888@gmail.com



## License

This project is licensed under the MIT License
