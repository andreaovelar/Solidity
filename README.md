# Solidity

###  Solidity_HW
####  Background
Your new startup has created its own Ethereum-compatible blockchain to help connect financial institutions, and the team wants to build smart contracts to automate some company finances to make everyone's lives easier, increase transparency, and to make accounting and auditing practically automatic!

Fortunately, you've been learning how to program smart contracts with Solidity! What you will be doing this assignment is creating a few 
### ProfitSplitter contracts. These contracts will do several things:
* Pay your Associate-level employees quickly and easily.
* Distribute profits to different tiers of employees.
* Distribute company shares for employees in a "deferred equity incentive plan" automatically.

## Files  
* AssociateProfitSplitter.sol -- 
* TieredProfitSplitter.sol -- 
* DeferredEquityPlan.sol -- 

## Steps  
* Connect Ganache in local network, 
* Open metamask in local network and 
* Deploy contracts using remix.
* Please note that for last file deferred equity plan we are using the kovan network to test and view transactions on etherscan

## File AssociateProfitSplitter

Please find below screenshot in which we show the deployment in remix for Associate file using local network 

![table](https://github.com/andreaovelar/Solidity/blob/master/images/Capture7.PNG "CLOSE")

Please find below screenshot in ganache that shows initial balance of the accounts 

![table](https://github.com/andreaovelar/Solidity/blob/master/images/Capture8.PNG "CLOSE")

Please find below screenshot after we click the deply bottom

![table](https://github.com/andreaovelar/Solidity/blob/master/images/Capture9.PNG "CLOSE")

Please find below screenshot in which we send 6 ETH among the associates as well as initial balances 

![table](https://github.com/andreaovelar/Solidity/blob/master/images/Capture10.PNG "CLOSE")

Please find below screenshot of balance after distributing Ether from first account to second, third, and forth (2 each)

![table](https://github.com/andreaovelar/Solidity/blob/master/images/Capture11.PNG "CLOSE")

## File TieredProfitSplitter

Please find below screenshot for initial balances from account 1 to 4 

![table](https://github.com/andreaovelar/Solidity/blob/master/images/Capture12.PNG "CLOSE")

Please find below screenshot in which we confirm contract deployment  

![table](https://github.com/andreaovelar/Solidity/blob/master/images/Capture13.PNG "CLOSE")

Please find below screenshot that shows the distribution of 10 ETH among employees 2 to 4 

![table](https://github.com/andreaovelar/Solidity/blob/master/images/Capture14.PNG "CLOSE")

Please find below screenshot for balances of the employess. Please note that second address received 6.5 ETH, third 2.5 and forth 1.5 

![table](https://github.com/andreaovelar/Solidity/blob/master/images/Capture15.PNG "CLOSE")

## File DeferredProfitSplitter

Please find below screenshot in which we deploy the contract in the local network 

![table](https://github.com/andreaovelar/Solidity/blob/master/images/Capture16.PNG "CLOSE")

Please find below screenshot for contract interaction in which we test fast_forward function

![table](https://github.com/andreaovelar/Solidity/blob/master/images/Capture17.PNG "CLOSE")

Please find below screenshot for Distribution function output. In this case the equity plan corresponds of a one year worth of stock (250 shares)

![table](https://github.com/andreaovelar/Solidity/blob/master/images/Capture18.PNG "CLOSE")



### Deferred Equity Plan using Kovan Testnet 

Please find below screenshot for of Bitcoin Testnet transactios recorded for our address 2 received and 6 sent 

![table](https://github.com/andreaovelar/Solidity/blob/master/images/Capture19.PNG "CLOSE")

Please find below screenshot for of Bitcoin Testnet transactios recorded for our address 2 received and 6 sent 

![table](https://github.com/andreaovelar/Solidity/blob/master/images/Capture20.PNG "CLOSE")

Please find below screenshot for of Bitcoin Testnet transactios recorded for our address 2 received and 6 sent 

![table](https://github.com/andreaovelar/Solidity/blob/master/images/Capture21.PNG "CLOSE")

Please find below screenshot for of Bitcoin Testnet transactios recorded for our address 2 received and 6 sent 

![table](https://github.com/andreaovelar/Solidity/blob/master/images/Capture22.PNG "CLOSE")

## Useful commands to send ETH and Bitcoin testnet 
* send_tx(BTCTEST,btc_account,'mrwjTLQMeqrbU4eg6WGyL7xCf25ewAHsn2',0.0001)
* send_tx(ETH,eth_account,'0x30B7C972578985dD504Cd6E1846d55faF25CF37E',1)

## Conclusions 
* We were able to use hd wallet derive and python to send ETH and bitcoin testnet 
* We use our network using The Clique Proof of Authority algorithm from previous assignment to send the ETH 
