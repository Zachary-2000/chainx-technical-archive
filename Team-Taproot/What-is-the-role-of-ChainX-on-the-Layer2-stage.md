# What is the role of ChainX on the Layer2 stage?

## Layer 2

Layer2 technology, often referred to as an "off the chain" solution, is currently one of the growth and momentum of Bitcoin. By moving some of the data processing from the main chain to Layer2, the entire blockchain network is more scalable. Blockchain is gradually evolving into a multi-tier architecture system, Layer2 can help us create "usable" blockchain systems and extend to other industries, without breaking Layer1, more application scenarios, payment scenarios can be spread across Layer2.

## Lighting Network

![img](https://cdn.nlark.com/yuque/0/2021/png/12795567/1626924413860-a693d7c5-b0d2-44f8-94c7-94eccb095652.png)

Lightning Network is a decentralized system for instant, large amounts of small payments that eliminate the risk of entrusting the custody of funds to a trusted third party. Chain lightning network aims to implement and securely under the deal, its essence is to use a hash time lock intelligence to safely 0 to confirm a mechanism, by setting the clever 'intelligent' contract, allowing users in lightning unconfirmed online transactions, and gold is just as safe (or is just as safe as the currency).

The lightning network provides a scalable network of micropayment channels. If the two parties of the transaction have a payment channel in advance on the blockchain, they can realize the micro-payment with instant confirmation multiple times, high frequency, and two-way. If there is no direct P2P payment channel between the two parties, as long as there is a payment path consisting of multiple payment channels connecting the two parties, the lightning network can also use this payment path to realize the reliable transfer of funds between the two parties. At the same time, because there must be sufficient funds in the payment channel, that is to say, the payment transfer station should make a pre-deposit for each channel, and to realize the timely and effective payment, the deposit needs to reach about 10 times the amount required for the payment. So even if the network is not under attack, such a large amount of money can bring serious security and liquidity problems. At the same time, when people buy and sell in different channels with different amounts of money, numerical asymmetry may occur frequently. The path from one node to another is easy to find, but finding the right jump every time is the hardest part. When more than 50% of transactions fail to find the path, the Lightning network drives more transactions on the Bitcoin chain than on the Lightning network.

The Lightning Network looks great, but if you're using these tokens as a long-term investment, you don't need the Lightning Network at all, as it's not very safe to entrust it with large transfers right now. Of course, if you're looking at Bitcoin as an alternative payment method, then the Lightning Network (if it works) is important to you. Instant micropayments, increased anonymity, virtually no fees -- it does provide a solution for this type of payment scenario.

## Liquid Network

![img](https://cdn.nlark.com/yuque/0/2021/jpeg/12795567/1626924375184-591d3ea8-6fa8-4f50-b1d6-b5d329b13bec.jpeg)

The Liquid Network is a side chain-based settlement network that enables faster and more confidential bitcoin transactions and the issuance of digital assets. As a side chain to Bitcoin, Liquid allows you to move bitcoin between the bitcoin main chain and the Liquid sidechain via verifiable 1-to-1 anchoring. First, users get L-BTC by locking bitcoin on the main chain. This process requires 102 bitcoin blocks to be confirmed. Once confirmed, an equal number of L-BTCs will appear on the Liquid network, and then transfers using L-BTCs will enjoy the convenience of the Liquid network. If you want to solve L-BTC and go back to the Bitcoin network, you only need two liquid network block confirmations.

Block generation for Liquid occurs once per minute. This means that Liquid's block generation is more consistent than bitcoin's (which has a probabilistic generation). Block signers track the height of the block they signed with their parent block and refuse to sign blocks that would result in a reorganization of multiple blocks. Once a block is created, its parent block will never be reorganized from the longest chain, which is why Liquid transactions can be considered final once they have received two confirmations. When the network is up and running, Liquid transactions will be settled in two to three minutes, which largely solves the problem of slow transfers on bitcoin's main network.

Liquid also uses privacy transfer technology developed by Blockstream. This encryption protocol can hide the amount and asset type of each transfer. Specifically, when a user uses a Liquid web browser to view the transfer information, all users can only see a transfer from one address to another. But the exact number of transfers and types of assets are hidden. Thus, by using private transfers, users can trust that their sensitive transfer information has not been compromised and that no one will react in advance because they see the information.

## ChainX

![img](https://cdn.nlark.com/yuque/0/2021/png/12795567/1626924991170-b85dd575-0c60-4522-9f9a-92463e79214d.png)

ChainX is the earliest blockchain developed based on the Substrate framework. It is committed to the research and application of bitcoin Layer2 expansion, digital asset gateway, and Boca level 2 relay chain. At the level of governance and operation, ChainX adopts dynamic asset mining mode to achieve safe and efficient chain governance and consensus; at the level of technical implementation, ChainX realizes the asset cross-chain of mainstream cryptocurrency, and forms a digital asset gateway through decentralized Bitcoin asset trusteeship and mirror asset cross-chain, realizing all cryptocurrency transactions in the same chain. At the same time, as the second layer network of Polkadot, it undertakes the role of splitting multi-chain structures, building parallel transfer bridges, and brokering multi-party transactions. After users connect all kinds of digital assets they hold across chains to ChainX, they can not only complete currency asset transactions on the system-integrated exchange DApp, participate in bitcoin financial derivatives operations, but also generate fair prices for asset market weight mining.

ChainX creatively combines "multi-signature managed assets + light bitcoin" to achieve cross-chain, and the relay scheme based on the light node can realize cross-chain operation between different blockchains. Now Bitcoin cross-chain has been realized. To ensure the security of the cross-chain process and cross-chain assets, several institutions or individuals with strong credit endorsements are selected to form a trust and manage trust accounts in the way of multi-signatures. When the Bitcoin network is cross-linked to ChainX, many institutions or individuals with strong credit endorsements are selected to form a trust. The process is completely decentralized and carried out through smart contracts, while the reverse cross-link from ChainX to the Bitcoin network requires the trust to operate the trust account with multiple signatures (because the Bitcoin network cannot run the complicated smart contract).

At the present stage, the decentralized light node approach is adopted by ChainX to integrate mainstream digital assets across chains. In the future, the cross-chain process will be upgraded using independent trustee, MPC, homomorphic encryption, Bitcoin financial derivatives will be carried out one after another, and the access of mainstream currencies such as ETH, ERC20, EOS, ADA, ZEC, and so on will be accelerated. At the same time, cultivate the community's habit of cross-chain asset transfer and developer ecology, promote the flow of bitcoin value, and incubate DApp using the latest intelligent contract technology.

## The difference among the three

|                | Lightning Network                                            | Liquid Network                                            | ChainX                                                       |
| -------------- | ------------------------------------------------------------ | --------------------------------------------------------- | ------------------------------------------------------------ |
| Transfer scale | Small                                                        | Middle, Large                                             | Middle, Large                                                |
| Startup mode   | Open the two-way payment channel and deposit BTC             | Lock to multi-signature address                           | Lock to multi-signature address，Buy from DEX                |
| Redeem Mode    | Close the two-way payment channel, aggregate the transactions that take place in the channel and confirm on the main network | Unlock L-BTC and change it back to BTC                    | Unlock X-BTC and change it back to BTC                       |
| Transfer speed | Instantaneous confirmation                                   | 2 minutes to confirm                                      | 6 seconds confirmed                                          |
| Storage mode   | Single signature hot wallet                                  | Multi-signature、Hot wallet、Cold Wallet、Hardware wallet | 多Multi-signature、Hot wallet、Cold Wallet、Periodic replacement of trustee |
| Trust model    | P2P                                                          | Trust more than 2/3 of the trusted nodes                  | Trust more than 2/3 of the trusted nodes                     |

Lightning Network was developed for small payments. By finding a lightning network channel between the sender and receiver, money can be transferred to each other. However, for episodic transactions, if there is no established lightning channel between the two, the transaction must be set up by sending the transaction, in which case the fee is higher than that of sending the transaction directly on the Bitcoin network. Therefore, if the established channel is closed immediately after the completion of this transaction, it would be unwise for the user to pay a higher fee to use the Lightning network. Therefore, the Lightning Network expands the use scenarios of Bitcoin to a certain extent, but the use scenarios are limited. Not only that, the amount of payments each lightning network channel can process is limited by the amount of its initial capital, so that as the transaction size increases, the likelihood of finding a full path from buyer to seller decreases, making the Lightning network less suitable for processing large transactions.

Unlike the lightning network, which generates blocks to confirm transactions, the liquid network can transfer money slightly more slowly. Still, transfers are much faster than on bitcoin's main chain. New blocks are created every minute on the liquid network, which is ten times the average bitcoin block rate, and it takes two confirmations before a transfer is considered final, meaning it takes about two minutes.

ChainX also uses blocks to confirm transactions. It doesn't transfer the money instantaneously, but new blocks are created every six seconds, 10 times faster than the liquid network. Moreover, Chainx is optimized for medium and large transfers so that users can lock in as many Bitcoins as they need and start transferring immediately, without the recipient having to participate in setting up any channels, they can receive all the assets that the sender can send.

## 总结

![img](https://cdn.nlark.com/yuque/0/2021/png/12795567/1626925047612-35e7d866-d25e-42cb-addd-eee58b950fb6.png)

Whether it's Lightning, Liquid, or ChainX, the goal is to make bitcoin more widely available, using lightning to make small money transfers quickly and cheaply, and liquid to allow the medium to large bitcoin transfers at a reasonable speed with a high degree of privacy and security. ChainX, as an asset aggregation gateway, can extend bitcoin to Polka ecology and Eth ecology, enabling BTC Layer2 again, further expanding BTC usage scenarios.