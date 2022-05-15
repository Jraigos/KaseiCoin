# KaseiCoin

The KaseiCoin project is an example of how to develop a monetary system based on blockchain technology, creating a fungible token that’s ERC-20 compliant and deploying it using smart contracts.

The files created for the project are:
- KaseiCoin.sol
- KaseiCoinCrowdsale.sol


The steps for its development are divided into the following subsections:


1. Create the KaseiCoin Token Contract


2. Create the KaseiCoin Crowdsale Contract


3. Create the KaseiCoin Deployer Contract


4. Deploy and Test the Crowdsale on a Local Blockchain


This token will be minted by using a Crowdsale contract from the OpenZeppelin Solidity library. The created crowdsale contract will manage the entire crowdsale process. This process will allow users to send ether to the contract and receive KaseiCoin tokens, or KC, in return. The contract will automatically mint the tokens and distribute them to a buyer in one transaction.

In the next part it is explained the development process of KaseiCoin:


1. The KaseiCoin Token Contract:

</br>
  1.1 Compilation of the contract by using compiler version 0.5.0.
  
![KaseiCoin token compilation](Execution_Results/token1.png)
</br>
</br>
  1.2 Deployment
  
![KaseiCoin token deployment](Execution_Results/token2.png)
</br>
</br>
  1.3 Generate the Token 
  
![KaseiCoin token transaction](Execution_Results/token3.png)
</br>
</br>
1.4 Transaction

![KaseiCoin token transaction](Execution_Results/token4.png)
</br>
</br>

2. The KaseiCoin Crowdsale Contract:

</br>
  2.1 Compilation of the contract by using compiler version 0.5.0.
  
![KaseiCoin token compilation](Execution_Results/crowdsale1.png)
</br>
</br>

  2.2 Once the contract is deployed, it is entered the name and symbol of the token, and the wallet address that will receive the payment.
  
![KaseiCoin token compilation](Execution_Results/crowdsale2.png)
</br>
</br>

  2.3 The transaction has been succesfulled mined. 
  
![KaseiCoin token transaction](Execution_Results/crowdsale4.png)
</br>
</br>

  2.4 A new addresses for the crowdsale and the token contracts are created where the payment and the token are going to be located until all the transaction process is finished. 
  
![KaseiCoin token deployment](Execution_Results/crowdsale5.png)
</br>
</br>

  2.5 Afte the address of the beneficiary or buyer of the token, is entered, it is also entered the amount to buy in ETH of the token. In this example it is 3 ETH.
  
![KaseiCoin token transaction](Execution_Results/crowdsale6.png)
</br>
</br>

  2.6 Finally it is displayed the amount in wei raised, the address of the account that receive this amount, and the address of the token.
  
![KaseiCoin token transaction](Execution_Results/crowdsale7.png)
</br>
</br>


Here there is a link to a short video for a better understanding of all the developing process of the KaseiCoin project:

https://github.com/Jraigos/KaseiCoin/blob/main/KaseiCoin.mov



