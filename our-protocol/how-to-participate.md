# 📈 How to Participate
***  
### How you can participate in Alpaca Finance
As a user, you can participate in Alpaca Finance in three different ways:    
     
**Lender**: You can earn safe and stable returns on your base assets by depositing them into our lending vaults. These assets are then offered to yield farmers for leveraging up their positions.
    
**Yield farmer**: You can borrow base assets from our lending vaults, allowing you to open a leveraged farming position, multiplying your farming APR by up to 6x(minus borrowing interest). Of course, these higher yields come with larger risks than lending: liquidation, impermanent loss, etc.
   
**Liquidator**: Monitors the pool for underwater leveraged farming positions(when equity collateral becomes too low, thus approaching risk of default) and liquidates them. (Bots only)   
   
We currently support the following base assets : BNB, BUSD, USDT, ETH, ALPACA, and BTCB. Our available leveraged farming is integrated with PancakeSwap & WaultSwap.   
   

In this example below, we show how each participant works together in our ecosystem:   
   
* **Alice the lender** deposits her BNB into our lending vault, and receives ibBNB: an interest-bearing asset representing her shares of BNB in the lending vault. Her BNB then becomes available for a yield farmer to borrow. Meanwhile, Alice's ibBNB accrues interest internally, which she can withdraw for more BNB than the amount she deposited (representing principal BNB + interest).
   
* **Bob the yield farmer** wants to open a leveraged yield farming position on the BTC/BNB pair; he borrows BNB from the vault and enjoys higher yield farming rewards. Alpaca Finance's smart contract takes care of all the mechanics behind the scenes : optimally switching assets to the right ratio, providing liquidity to the pool, and staking the LP tokens for Pancake Rewards.
   
* **Erin the liquidator bot** monitors the health of each leveraged position, and when it goes beyond designated parameters, she helps liquidate the position, making sure lenders such as Alice do not lose their capital. For this service, she takes a 5% reward from the liquidated position. At Alpaca, we also have an in-house bot for this which uses 100% of this fee for a buyback and burn of the ALPACA token. So even if you're unfortunate and have your position liquidated, if you're an ALPACA holder, you can feel relieved knowing your token is going up in value as a result.
   
![](https://pic.imgdb.cn/item/60f790e45132923bf89319aa.jpg)