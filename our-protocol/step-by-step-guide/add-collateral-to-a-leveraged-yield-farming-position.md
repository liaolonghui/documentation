# Add collateral to a Leveraged Yield Farming Position
***

To add collateral to your active positions, follow the step below.
* Go to Alpaca's Finance Farm page (https://app.alpacafinance.org/farm)
* Connect to your Web3 wallet (such as MetaMask) and make sure your network is set to Binance Smart Chain. Click [here](https://academy.binance.com/en/articles/connecting-metamask-to-binance-smart-chain) if you do not have the network in your wallet yet.
* You will see your active positions in the "**Your Positions**" section
* Select a position you'd like to add collateral and click "**Add Collateral**"

![](https://pic.imgdb.cn/item/60fa28575132923bf87de11b.png)

* Enter the amount  of collateral you would like to add
  - You may supply any combination of the two assets in the farming pair. Our smart contract optimally converts your deposited assets to get an equal value-split to supply the farming liquidity pool.

<img src="https://pic.imgdb.cn/item/60fa28825132923bf87e589e.png" width="400" height="400" />

* After clicking "**Add Collateral**", you should get a pop-up notification in your MetaMask to accept the transaction
* Wait for the transaction to be processed
* Once the transaction has gone through, you'll see your updated farming position in the "**Your Positions**" section of the Farm page.


> #### Why am I unable to add collateral to my position?
> At the moment, to succeed in adding collateral, it has to be enough to get your position's debt ratio to the maximum allowed when opening a new position for that pool. In other words, you have to add enough to get your leverage back up to where you started. We understand the usability of this isn't great and we're working on making it more flexible. For the time being though, please take a look at the necessary debt ratio you need for your pool which is listed under Work Factor [here](../pool-specific-parameters.md)