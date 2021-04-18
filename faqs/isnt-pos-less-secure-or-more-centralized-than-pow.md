---
title: How does the decentralization of proof-of-stake (PoS) compare to proof-of-work (PoW)?
weight: 3.1
attribution:
  -
    name:
    link:
---

In addition to improved efficiency, one of the other major motivations for the switch to proof-of-stake (PoS) is the increase in decentralization and censorship resistance that PoS offers.

PoW and PoS do have many similarities. They are both fully permissionless systems where anyone can participate. They both rely on **economic sybil resistance**: the impact you have on the network, and therefore the rewards that you can earn, are proportional to the quantity of economic resources that you put in (computer hardware and electricity in PoW, and coins in PoS). However, there are important differences between the two.

To join as a miner in a PoW network, you need to purchase mining hardware (often specialized hardware called "application-specific integrated circuits" or "ASICs"), have access to a cheap and reliable source of energy, and have a substantial level of technical skill to run and maintain your "mining farm". Small-scale mining is possible, but economies of scale make it difficult to compete with larger and wealthier mining farms. Furthermore, because of their large electricity consumption, **centralized authorities can easily detect mining farms and shut them down** or coerce them into participating in attacks.

PoS, especially the form of proof of stake used in Ethereum, is much friendlier to smaller participants. To join as a validator and start staking, you need to provide 32 ETH (and if you have less than that, [decentralized staking pool tech based on multi-party computation](https://medium.com/coinmonks/eth2-secret-shared-validators-85824df8cbc0) is under development). The only hardware that you need to participate in PoS consensus is any reasonably modern consumer hardware (eg. a laptop) in order to run a node. Staking larger amounts of ETH requires more hardware to process more shards, but this is only expected to be a serious issue if you are staking millions of dollars. You can stake from anywhere, and you do not lose a significant amount of revenue from having an extra few hundred milliseconds of latency.
