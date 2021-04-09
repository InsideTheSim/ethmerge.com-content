---
title: Isn't proof-of-stake (PoS) less secure/decentralized than proof-of-work (PoW)?
weight: 3.1
attribution:
  -
    name: Yule Andrade
    link: https://twitter.com/yulesa
---

In PoW, if miners act maliciously, they lose the block reward and the operational cost of running the rigs like electricity bills and capital cost. The blockchain is safer the more the malicious player has to lose. That way rig operational cost and the block reward has to be higher as possible in order to the network to be safer. That’s the reason PoW is so wasteful in electricity resources. Also, the network security is drastically reduced if the block rewards is suddenly decreased.

PoS operational cost is very low. Instead, if you act maliciously, aside of losing the rewards (a positive reinforcement), your stake is also burned (a negative reinforcement).

This has three advantages:

First, it better aligns incentives to the participants in the network considering that the stake is now denominated in the network currency.

Second, since you lose your stake acting badly, if you try it be dishonest again, your next attack is less effective because your stake is now lower and so is your voting power.

Third, since bad actors now have a negative reinforcement, participants have less wiliness to be malicious and the network positive reinforcement can be lowered to keep the same level of security. Thus, the network can reduce block rewards even increasing it security.

Also, since operational cost are low, more people can participate in the network consensus. You don't need to be close to mining rig distribution channels or have access to lower electricity cost. All resources to run a node in PoS are more easily available which make more affordable to anyone, thus more decentralized. The beacon chain has today over 100K validators.

PoS bigger security risk is its engineering complexity. It relies on new ways of using cryptography, much more network communication and strong randomness assumptions. However, this work is already done in the form of “Eth2 node and validators clients” and a user has only to keep it running, connected and updated. Also, that's why it was safer to do that it in a new chain (the beacon chain), because if anything when wrong, nothing happens to the ETH1 chain. This new chain has been running without issues since its launch in December 2020, is securing millions of ETH and is now considered safe to be merged to Ethereum network.
