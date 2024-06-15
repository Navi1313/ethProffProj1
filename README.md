# ethProffProj1
Simple overview of use/purpose.
This Solidity program is a simple "productSellProfit" contract that demonstrates the error handling using require, assert and revert methods.

Description
by using an application from e-commerce platform where seller can send products and buyer can buy. we will create two functions one will be for seller to add a product into the map and another buyer can be able to buy that product by using second function . 

# Getting Started
To start you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.
create a contract
```
pragma solidity ^0.8.24;

contract productSellProfit {
    // the standard functions see repo 
    }
}
```
To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to "0.8.24" (or another compatible version), and then click on the "Compile productSellProfit.sol" button.

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "productSellProfit" contract from the dropdown menu, and then click on the "Deploy" button.

Once the contract is deployed, you can interact with it by calling the sellerAddProduct() function . where you can add an product at indexes of a map. you can interact with it by calling the giveYourOrder() function . where you can give an order amout of fees and price would deduced as wei from your account. as well as you can call an product mapping function to check the remaining product count . 


# Authors
Contributors names and contact info

 [@Navjot Singh Sabharwal ]
 (https://github.com/Navi1313)

# License
This project is licensed under the MIT License - see the LICENSE.md file for details
