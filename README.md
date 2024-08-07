# DEGEN GAMING TOKEN

This is a smart contract in the form of Token for Degen Gaming where several functionalities can be performed.

## Description

With the help of Smart Contracts, we can mint tokens, transfer them from one address to another, burn them, and buy certain Degen Gaming merchandise over the Decentralised Network. The workings of the contract are verified over the Avalanche Fuji Test Network. The verification is done on Snowtrace Testnet.

## Getting Started

### Installing

You can download the DegenToken.sol file and then compile it in Remix and then choose Environment as Injected Provider - Metamask and after that deploy the contract.

### Executing program

Steps to be followed to run the contract seamlessly:

1. First we have to take test credit in the form of AVAX tokens in the Avalanche Fuji C-Chain.

   *The following steps are to be followed to create a Test Network in Metamask:*
   *Network Name*: Avalanche Fuji C-Chain
   *New RPC URL*: https://api.avax-test.network/ext/bc/C/rpc
   *ChainID*: 43113
   *Symbol*: AVAX
   *Explorer*: https://testnet.snowtrace.io/

2. Now we will go to the core web app to request for Tokens and there we have to enter the coupon code that we will get after we join the Get Avax for free guild.
   
3. Now we can generate the secret code and enter it in the coupon code address and after that, we will enter the address of the Account in the Test net of Avalanche.
   
4. We will get 0.5 AVAX per day and after that, we can use those to test our contract.

5. Now we will go back to Remix and then choose Environment as Injected Provider - Metamask and after that deploy the contract.

6. After that we will flatten the solidity file and then download the new file that is generated.

7. Now we will copy the address of the deployed contract and then paste it into Snowtrace Testnet and then click on verify and publish contracts.

8. Then we will click on verify, select chain as Fuji, enter the address of the new contract, and select the compiler version mentioned in the solidity file. Then, we will upload the flattened solidity file in it and click on verify.

9. After all is done we will now perform transactions in the contract and those will be logged in the Snowtrace.


## Working

After the Contract is deployed we can perform the following operations in it:

1. Minting Tokens: Allows the owner to create new tokens and assign them to a specified address.
2. Redeeming Tokens: Enables users to redeem tokens for specified merchandise items.
3. Burning Tokens: Allows users to destroy a specified amount of their tokens.
4. Pausing Transfers: Pauses all token transfers (only by the owner).
5. Unpausing Transfers: Resumes all token transfers (only by the owner).
6. Checking Paused State: Returns the current paused state of token transfers.
7. Withdrawing ETH: Transfers the contract's ETH balance to the owner's address.
8. Adding Merchandise: Adds new merchandise items to the inventory (only by the owner).
9. Getting Merchandise List: Retrieves the list of all merchandise items.
10. Checking Inventory: Returns the redeemed items and quantities for a specified account.
11. Transferring Tokens: Transfers tokens to a specified recipient if transfers are not paused.
12. Transferring Tokens from Another Address: Allows a spender to transfer tokens from a specified sender if transfers are not paused.
13. Approving Spender: Approves a spender to spend a specified amount of the caller's tokens.
14. Receiving ETH: Allows the contract to receive ETH.

## Help

Certain errors may occur while verification of the contract for that we have to keep in mind that the solidity version specified in the contract, the version in the solidity compiler, and the one chosen while verifying should be the same.

Apart from it we also have to flatten the file because the JSON format has to be adaptable as normal import statements are not compatible with the verification portal.

## Authors

Contributors names and contact info

Yukta
[@Yukta](https://www.linkedin.com/in/yukta-/)


## License

This project is licensed under the MIT License - see the LICENSE.md file for details
