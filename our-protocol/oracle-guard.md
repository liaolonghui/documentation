# 💂‍♂️ Oracle Guard
Protecting our herd from price divergence

***

![](https://pic.imgdb.cn/item/60f794ae5132923bf89f74c1.png)

Financial markets can be dangerous, my fellow Alpacas, which is why we’ve introduced something to protect you in the worst of times, from potential price manipulation, flash liquidation, and market failure. You may get nervous with other farms, but **at Alpaca, you’ll never have anything to be nervous about,** because this is much more than a new feature; this, is your new protector — the **Oracle Guard.**

Some of you who used our platform may have noticed that certain functions were temporarily grayed-out such as opening positions on certain pairs. This was the Oracle Guard in Protection Mode, **keeping you safe from the dangers of the market.**

To be specific, when the price of an asset in your farming pair has its on-chain price from the exchange that pair is on(PancakeSwap) differ more than 5% from Chainlink price feeds, the Oracle Guard enters Protection Mode; This consists of disabling liquidations, opening and closing positions, and adding collateral; all in order to protect you from trading at bad prices and taking an unjust loss.

This is also why the Guard turns off adding collateral; After all, Since the LP tokens need their paired assets to be in a 50:50 ratio, the protocol would have to swap some of that added collateral to achieve this even ratio, which would happen at a bad price. So this too is a situation where the Guard is protecting you. In fact, **the Oracle Guard saved a lot of users’ funds during the May 20th, 2021 market crash.**

![](https://pic.imgdb.cn/item/60f7aae45132923bf8ee6e11.png)

When the entire market flash crashed, the Oracle Guard went into action, protecting many users’ positions from flash liquidations, allowing them to stay safe and keep farming once prices realigned and the Guard lifted Protection Mode. During this chaotic time, many users were prevented from losing their positions and trading at bad prices.

Feeling safer already? You should. 😄 The Oracle Guard’s Protection Mode acts as an oracle delay, verifying price feeds consistently after activation(verification frequency varies depending on overall market volatility), which prevents large market orders from engaging in price manipulation(such as flash loans or margin orders). When the on-chain price moves far off from where it should be, this delay gives enough time for arb bots to push back that price to realignment either with other exchanges or a peg in the case of stablecoins and other pegged tokens.

**In summary, the Oracle Guard is watching your back.** Yet, when he does activate Protection Mode, you don’t have to be worried either, because it’s also unlikely to stay on for long. Inevitably, arb bots will soon close the price divergence, letting the Oracle Guard remove his protections and you to return to customizing your position, if you’d like.

### The Oracle Guard sounds great, but what if I get liquidated because I can’t add collateral due to Protection Mode being activated?
It’s important to remember that when Protection Mode is on, liquidations are off, so adding collateral is not necessary. Of course, it is possible that Protection Mode lifts and your position still gets liquidated. This is because **the Oracle Guard doesn’t protect against liquidations when prices are correct. He only protects you from trading at bad prices or being unfairly liquidated by the market, like what happened at some other protocols.**

There’s even a small chance that Oracle Guard may enter Protection Mode, blocking you from adding collateral that could have saved your position. However, it’s important to remember that without the Oracle Guard, if your position was to get liquidated, chances are it would’ve happened much faster, before you ever got a chance to add collateral, because the Guard only activates when a flash liquidation is a genuine threat.

The Oracle Guard is like the police. Often facing difficult situations, they’re not perfect, and can even make a mistake on occasion. However, we need them. Without them, there would be crime everywhere and the world would be chaos. Oracle Guard is the same. Is he perfect? No, but your assets are much safer with him than without him.

***

### The Venus Incident vs. Oracle Guard
On 5/18/21, Venus had a major incident that created $200M+ USD in liquidations and $100M in bad debt. We won’t go into the details and there are differing accounts of what happened but you can read about it here and here. In any case, what we do know is that the ultimate culprit that caused the market dump on XVS was a series of cascading liquidations. Integrating Chainlink wasn’t enough to protect them. So it’s interesting to note that, in fact, **if Venus had the Oracle Guard, he would’ve blocked this incident from ever happening!**

The Oracle Guard would’ve frozen the system when price took the first drop, blocking this chain of liquidations from the start! What’s more is he may have even stopped the original price pump that allowed several users(attackers depending on who you ask) to over-borrow against an inflated XVS price.
How about PancakeBunny’s exploit on 5/19/21 for 200M? A flash loan attack. As it stands, that wouldn’t have gotten past the Oracle Guard either! Not only does Alpaca Finance not work with flash loans, but the Oracle Guard would’ve frozen the attack as soon as price made a drastic movement!

Well, it’s very unfortunate he wasn’t at either of those platforms, but that’s because he’s dedicated to his current job and thus, can **only guarantee that one place is safe— Alpaca Finance.**

So luckily for us, **we don’t have to worry about any of these dangers,** because the Oracle Guard is also an Alpaca that lives on the farm, and he’ll never let the Llamas hurt you! 😄

Yet, even though the Oracle Guard has demonstrated his strength, he never stops going to the gym and becoming stronger, so that he can protect us even better. In reality, you could say our devs are his personal trainers.

By that I mean, our team is working on adding even more mechanisms to his program, making his supreme defense all-powerful. One of these boosts is a debt cap on farming pools, one that varies per pool depending on liquidity, which would further block someone trying to manipulate price by opening a huge position. In the future, we’re even considering adding trailing debt caps. Ok, so what would that mean for Oracle Guard? Imagine Arnold Schwarzenegger + Bruce Lee + Optimus Prime…

Yea, you can feel safe.

***

In summary, we hope you’ve enjoyed meeting your new Alpaca bodyguard, protecting your assets from external threats.‌ Hence, if you ever find the Oracle Guard in Protection Mode, you can rest assured that your assets are secured from any external factors until the markets realign, because that’s the Oracle Guard’s job: standing guard over the herd, watching, and protecting all you young Alpacas.