# suaave

[Suaave Demo](https://calchulus.github.io/suaave)

A monitoring tool & Interface for exploring Aave's Lending Pool contracts

Submission for Defi Hackathon


## How I built this
Built using Aave on Kovan, with help from Matic's Dagger.js and XRPTipbot :)

## Problem & Use Case
With Aave's new lending contract offering both fixed and variable rates, users may have a tough time monitoring which one is most advantageous. Using Suaave, and with help from Dagger, users can monitor whether or not their funds have been securely deposited to Aave's Lending Pool contracts, and if they're getting the best deal.

We then introduce the user to a one-click interface to make the most optimal interest rate swap trade (currently WBTC for ETH).

We then do the math to show the maximum possible interest rate swap position that one may take to take advantage of the best interest rates.

Currently, this would entail borrowing any asset (such as WBTC) to buy Ethereum, and then redepositing the Ethereum to borrow more WBTC recursively. This would allow a user to earn a ~36% APY on the initial holdings, provided they are willing to go long Ethereum against BTC. Not a bad return!

## Next Steps
- Fixing cosmetic bugs
- Improving use of web3
- Suggest more additions to the data provided by the Aave API endpoint
- Allow a user to play a game while watching their rewards grow in lending



