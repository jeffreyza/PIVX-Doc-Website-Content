---
title: 'Getting Started with PIVX'
date: '01-08-2014 00:00'
slug: getting-started
description: 'Your journey with PIVX starts here'
image: getting-started.png
taxonomy:
    category:
        - 'Getting Started'
    author:
        - 'The PIVX Team'
---

### Getting Started with PIVX


PIVX creates a new block every 60 seconds. Each of these blocks create 5 new PIV, and allocates 1 new PIV for any treasury proposals:
2 PIV per block is created and paid to the staker that wrote the block.
3 PIV per block is created and paid to the next masternode in the payment queue.
1 PIV per block is allocated to the Treasury Budget and [may be] created with the Super Block and paid to a funded proposal.

Refer to the PIVX Economics Whitepaper available on the [PIVX Economics](https://pivx.org/economics?target=_blank) page.



### What is PoS (Proof of Stake)


So what is PoS? To understand how PoS works we have to look at some terms first to understand the underlying technology.

The PIVX staking mechanism is based

Refer to the PIVX Economics Whitepaper available on the [PIVX Economics](https://pivx.org/economics?target=_blank) page.

### Consensus Algorithm

The first-term we need to cover is the “Consensus Algorithm”. A consensus algorithm is a mechanism that allows users or machines to coordinate in a distributed setting. It needs to ensure that all agents in the system can agree on a single source of truth, even if some agents fail. In other words, the system must be fault-tolerant. In a centralized setup, a single entity has power over the system. In most cases, they can make changes as they please – there isn’t some complex governance system for reaching consensus amongst many administrators. 
But in a decentralized setup, it’s a whole other story. Say we’re working with a distributed database – how do we reach an agreement on what entries get added?

Overcoming this challenge in an environment where strangers don’t trust each other was perhaps the most crucial development paving the way for blockchains.

So in cryptocurrencies, our balances are recorded in a database which we call the “Blockchain” And for the system to work every node has the same identical database also known as a blockchain. Otherwise, you’d soon end up with conflicting information, undermining the entire purpose of the cryptocurrency network.

Public-key cryptography (Public-key cryptography (PKC), also known as asymmetric cryptography, is a framework that uses both a private and a public key, as opposed to the single key used in symmetric cryptography. The use of key pairs gives PKC a unique set of characteristics and capabilities that can be utilized to solve challenges inherent in other cryptographic techniques. This form of cryptography has become an important element of modern computer security, as well as a critical component of the growing cryptocurrency ecosystem.) ensures that users cannot spend each other’s coins. But there still needs to be a single source of truth that network participants rely on, to be able to determine whether funds have already been spent.

Firstly, we require that users that want to add blocks (we’ll call them validators) provide a stake. The stake is some kind of value that a validator must put forward, which discourages them from acting dishonestly. If they cheat, they’ll lose their stake. Examples include computing power, cryptocurrency, or even reputation. 

Why would they bother risking their own resources? Well, there’s also a reward available. This usually consists of the protocol’s native cryptocurrency and is made up of fees paid by other users, freshly-generated cryptocurrency units, or both.

### Proof of Stake

Proof of Stake (PoS) was proposed in the early days of Bitcoin as an alternative to Proof of Work. In a PoS system, there’s no concept of miners, specialized hardware, or massive energy consumption. All you need is a regular PC, or a Pi even works.

However, you still need to put some skin in the game. In PoS, you don’t put forward an external resource (like electricity or hardware), but an internal one – cryptocurrency. Rules differ with every protocol, but there’s generally a minimum amount of funds you must hold to be eligible for staking.

From there, you lock up your funds in a wallet (they can’t be moved while you’re staking). You’ll typically agree with other validators on what transactions will go into the next block. In a sense, you’re betting on the block that will be selected, and the protocol will choose one.

If your block is selected, you’ll receive a proportion of the transaction fees, depending on your stake. The more funds you have locked up, the more you stand to gain. But if you attempt to cheat by proposing invalid transactions, you’ll lose a portion (or all) of your stake. Therefore, we have a similar mechanism to PoW – acting honestly is more profitable than acting dishonestly.

[link to article proposing PoS on bitcointalk](https://bitcointalk.org/index.php?topic=27787.0)



### So how is PIVX System in regard to PoS

So now you know a little about how PoS work in general but let's implement what we learned on PIVX. 

PIVX has a Blockchain which is the same for all of its users. The chain remembers how many coins everyone has in their wallets; it is the database of the system. When we download the wallet it will automatically start downloading the PIVX blockchain to get ur wallet up to date. When it is set and done we now have access to the network, if we had an old wallet it can now show our balance. Everything is set. When we make our first transaction in the network it has something called TX which is the fee we pay for using the network, you remember we were told that people who have the Masternodes or staking their coin was putting their coins at risk but to get a reward in return? This is what the TX is covering so when the transaction is processed the protocol will go and find a random block on the chain and use it to validate the transaction. the person who is helping us to validate our block to make the transaction complete will get rewarded by the system in his wallet as thanks for using his coins to contribute to our transaction. Now we have our transaction done and we spent our PIV’s and someone whose wallet we choose received them. 