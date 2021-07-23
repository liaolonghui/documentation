# Close a Leveraged Yield Farming Position

*** 

To close a leveraged yield farming position, follow the steps below.
* Go to Alpaca's Finance Farm page (https://app.alpacafinance.org/farm)
* Connect to your Web3 wallet (such as MetaMask) and make sure your network is set to Binance Smart Chain. Click [here](https://academy.binance.com/en/articles/connecting-metamask-to-binance-smart-chain) if you do not have the network in your wallet yet.
* You will see your active positions in the "**Your Positions**" section
* Select a position you'd like to close and click "**Close Position**"

![](https://pic.imgdb.cn/item/60fa2cac5132923bf88a1303.png)

* After clicking "**Close position**", you will see two methods you can select:
  - **Minimize Trading**:  We will convert the minimum required amount of tokens into ALPACA to pay back the debt and return the remaining assets to you. This can potentially save on slippage and trading fees.
  - **Convert to [Base Token]**: Your position value will all be converted to Base Token (the tokens your borrowed) and returned to you after paying back the debt.
* You can review all the relevant information such as price impact and the approximate value you will receive.
* Once you are happy with your selected method, you can click on "**Close Position**"

<img src="https://pic.imgdb.cn/item/60fa2d365132923bf88bb31e.png" width="400" height="400" />

* After clicking "**Close Position**", you should get a pop-up notification in your MetaMask to accept the transaction
* Wait for the transaction to be processed
* Once the transaction has gone through, you should receive the base tokens back in your wallet

> Please note that when you close a position, the position value will be converted into base tokens (BUSD or BNB). Part of it will pay back your **debt and accrued interest**. Then, you'll receive the remaining tokens in your wallet.

*** 

##### Liquidated positions

In the event that your position's debt size goes above the allowed risk threshold, it can be liquidated. Once that happens, the liquidated position will be moved into the "**Graveyard**" tab. You can also select "Click to view" to see the TX details on BSCscan.

![](https://pic.imgdb.cn/item/60fa2e1e5132923bf88e73a7.jpg)

The liquidation fees from our bot go to buyback and token burn of ALPACA. So if you're holding ALPACA, you can feel better knowing at least your tokens are becoming more valuable if you happen to get unlucky that one time. 😆

> Please note that if your position is liquidation, the position value will be converted into base tokens (BUSD or BNB). Part of it will pay back your **debt, accrued interest, and the liquidation fee.** Then, you'll receive the remaining tokens in your wallet.