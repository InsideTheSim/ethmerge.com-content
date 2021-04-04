---
title: How does 2.0 reduce the energy consumption of the Ethereum blockchain?
weight: 6.0
attribution:
  -
    name: Lamboshi
    link: https://twitter.com/L_Nakaghini
---
In Proof of Work mining, whoever solves the block first gets the reward. Simply put, it is a race and if you have more hash rate than someone else you are more likely to win. The end result of the race mechanism is that miners are running as many GPUs as they can get at 100% load, 24 hours a day and the power usage will [continue to scale](https://www.iea.org/commentaries/bitcoin-energy-use-mined-the-gap) with the price of the block rewards they earn. In Proof of Stake, the block proposers are [randomly selected](https://benjaminion.xyz/eth2-annotated-spec/phase0/beacon-chain/#compute_proposer_index) which removes the race condition. There is no way to increase the likelihood that you get chosen to produce a block, so there is no need to consume more and more energy to improve your chances.
