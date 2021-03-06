# TRC21 Wrapped Token

### 1. What is TRC21  Wrapped Token?

A Wrapped Token is a TRC21 token hosted on the TomoChain public blockchain, issued by TomoBridge Pte. Ltd.  and  backed by an equal amount of the underlying asset or currency. TRC21 Wrapped BTC, for instance, is a token worth the same as one BTC at any given moment. More details about [TRC21 Wrapped Tokens](../trc21-wrapped-token-information/).

TRC21 tokens are issued on TomoZ Protocol to bring users a much more friendly trading experience with a blazing fast speed, and extremely low gas fees that can be paid by the transaction token itself. It will also be supported by TomoP Protocol to enable a bunch of privacy features.

By nature, we can divide TRC21 Tokens into 2 types:  
**Native TRC21 Token**: The tokens that are originally issued on TomoChain blockchain, like TOMO, AIS, TIIM, and etc.  
**TRC21 Wrapped Token**: The tokens that are issued on other blockchains originally, and then reproduced on TomoChain network by locking a same amount of the native asset into a smart contract or multi-signiture wallet, like BTC, ETH, USDT, YFI, and etc.

### 2. Why do I need TRC21 Wrapped Tokens?

The reason you need TRC21 Wrapped Token is to be able to trade other platform's native token like BTC or ETH on decentralized exchange like TomoDEX. Because decentralized platforms running on TomoX use smart contracts to execute trades directly between traders and they need to have the same token standard.

{% hint style="info" %}
All the tokens listed on TomoDEX are TRC21 Tokens.
{% endhint %}

### 3. Can I trade TRC21 Wrapped Tokens on TomoX's DEXs after swapping?

Yes, you can use TRC21 Wrapped Tokens on [TomoDEX](https://dex.tomochain.com) as well as other DEXs built on top of TomoX.

### 4. Which coin/token is supported by TomoBridge?

TomoBridge currently supports converting between BTC, ETH, USDT, FTT, YFI, SRM, FRONT, DEC, DXD, VNDC, PIE, HY, MTA and their corresponding TRC21 tokens. 

###  5. What does it mean by "Wrap/Deposit" and "Unwrap/Withdraw"?

Due to the different token standards, you can only swap your TRC21 Wrapped Token to/from the other blockchain tokens via designated bridging portals.

Swapping other blockchain tokens to TomoChain’s TRC21 Wrapped Tokens is known as to "**Wrap"** or “**Deposit**”.  
Swapping from TomoChain’s TRC21 Wrapped Tokens to other blockchain tokens is known as to “**Unwrap**” or “**Withdraw**”

{% hint style="info" %}
The meaning of “Deposit” here is different from traditional centralized exchanges.  
On TomoDEX, users are always in direct custody of their funds. Which means you trade directly with the funds in your wallet without having to put it into the exchange’s account.  
{% endhint %}

### 6. How can I swap my asset to TRC21 Wrapped Token and vice versa?

You can go to [**TomoBridge**](http://bridge.tomochain.com) and swap between your asset and TRC21 Wrapped Token. Check out this article for details: [_**TomoBridge Tutorial**_](../tutorial/#fda7)_\*\*\*\*_

### _**7.**_ Can I sent my TRC21 token directly to an ERC20 address, or vice versa?

In simple words, NO you shouldn’t.

### 8. What should I do if I mistakenly sent my TRC21 Token to an ERC20 address without wrapping/unwrapping, or vice versa?

There could be a few different scenarios: 

a.\) If the receiving address is your own wallet address

As explained in Q8, these two token standards share the same address and all you have to do is to switch the network.

Let’s say you send your TRC21 Token to an ERC20 address, then you can retrieve your funds by following the steps below \(similar process the other way around\):

1. Log into your ERC20 wallet and export the Private Key. \(It has to be the Private Key, not Mnemonics\)
2. Log into your TomoWallet with the Private Key to recover your fund. \(Instead of TomoWallet, you can also choose to log into TomoDEX or TomoBridge so you can unwrap directly from there\)

{% hint style="info" %}
Some wallets may not come with a Private Key when you created your address, like Trust Wallet. Then you might need to contact the wallet developer to help you export your Private Key.
{% endhint %}

For Trust Wallet users, please follow [this guide](https://community.trustwallet.com/t/how-to-recover-funds-sent-to-a-wrong-public-address/145%20) to export your Private Key: 

b.\) If the receiving address belongs to a third party \(ex. an exchange\)

In this case, the third party team now is holding your funds. You will have to contact them directly to help you look into their account and refund it for you.

Most exchanges are willing to do it for their users for a fee. But each company could be different and it depends on their own policy.

