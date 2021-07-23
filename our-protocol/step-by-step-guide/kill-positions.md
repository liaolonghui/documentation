# Liquidate Positions

*** 

Anyone can build a bot to call a contract to liquidate underwater positions. The party calling the contract, aka liquidator, **receives 5% of the liquidated position value as the liquidation fee.**

At Alpaca, we have an in-house bot to do this, which uses **100% of the fee on buyback and burn of the ALPACA token.** However, anyone is free to do this as well, which we've allowed to avoid single-point of failure and centralization.

To liquidate positions, your bot needs to be an EOA bot, and what it has to do is call the kill method in the vault contract.