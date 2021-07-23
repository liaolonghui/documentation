# Move ALPACA-wBNB LP from PCSV1 to PCSV2

*** 

Due to PancakeSwap contract upgrade, LPs are required to move from old contracts (PCSV1) to new contracts (PCSV2.) Our staking contract structure does not allow for auto migration so you must do this process manually. 

To migrate your LP, follow the steps below

#### Step 1: Unstake your V1 LP token
* Go to the Alpaca stake page (https://app.Alpacafinance.org/stake)
* Connect to your Web3 wallet (such as MetaMask) and make sure your network is set to Binance Smart Chain. Click [here](https://academy.binance.com/en/articles/connecting-metamask-to-binance-smart-chain) if you do not have the network in your wallet yet.
* Select the ALPACA-wBNB staking pool
  - Specify the amount of tokens you want to unstake
  - Click "**Unstake**"

![](https://pic.imgdb.cn/item/60fa363d5132923bf8a330a4.png)

* After clicking "**Unstake**", you should get a pop-up notification in your MetaMask to accept the transaction
* Wait for the transaction to be processed
* Once the transaction has gone through, you should see the amount of LP tokens in your wallet
* If you don't see LP tokens, Add [0xf3ce6aac24980e6b657926dfc79502ae414d3083](https://bscscan.com/token/0xf3ce6aac24980e6b657926dfc79502ae414d3083) as custom token to your Metmask

#### Step 2: Remove liquidity from ALPACA-wBNB V1 pool
* Go to PancakeSwap Remove Liquidity page (https://v1exchange.pancakeswap.finance/#/pool)
* You should see your ALPACA-wBNB LP
* Click "**Remove**"

<img src="https://pic.imgdb.cn/item/60fa366a5132923bf8a3abd0.png" width="300" height="500" />

* Specify amount you want to remove (max in this case)
* After clicking "**Remove**", you should get a pop-up notification in your MetaMask to accept the transaction
* Wait for the transaction to be processed
* Once the transaction has gone through, you should see the ALPCA and wBNB in your wallet.

#### Step 3: Add Liquidity in V2 pool and Stake
* You can follow the steps here