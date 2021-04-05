---
title: Why is Ethereum (ETH) switching to Proof of Stake (Pos)?
weight: 2.0
attribution:
  -
    name: /u/Chapo_Rouge
    link: https://reddit.com/u/chapo_rouge
---

Ethereum in its current state is using [proof-of-work (PoW)](https://www.youtube.com/watch?v=3EUAcxhuoU4) to ensure consensus amongst the thousands of nodes in the network. While proof-of-work (PoW) is reliable and secure, it is also _extremely_ energy intensive. To produce each block on the network participants are required to use powerful and energy-hungry GPUs to solve a complex mathematical problem.

Alternatively, [proof-of-stake (PoS)](https://www.youtube.com/watch?v=psKDXvXdr7k) guarantees the security of the network in a different way. In proof-of-stake (PoS), anyone with 32 ETH can _deposit_ that ETH to become a _validator_, a node that participates in the network's consensus algorithm. Finalizing a block requires 2/3 of all active validators to sign off on it. Should a malicious actor try to tamper with the underlying protocol by using a large number of validators to revert a finalized block (the equivalent of a "51% attack" in PoW) their funds are slashed — meaning they lose a portion of their staked ETH. This makes attacks extremely expensive; it would be like a PoW system where if you use your mining hardware to attack the network then your hardware catches fire and is destroyed.

Proof-of-stake (PoS) does not require the same energy-intensive hardware as proof-of-work (PoW). Any relatively recent consumer hardware should be capable of running the software required to operate a 32 ETH staking node. If you deposit more than 32 ETH, you will be assigned multiple "validator slots" by the protocol, but you will still be able to run them from a single computer, though hardware requirements go up the more you stake. Most estimates put the expected energy savings from the switch to proof-of-stake (PoS) to be around 99%. [[source1](https://spectrum.ieee.org/computing/networks/ethereum-plans-to-cut-its-absurd-energy-consumption-by-99-percent)] [[source2](https://twitter.com/sigp_io/status/1374979655782989824)]

See also:

* [A Proof of Stake Design Philosophy](https://medium.com/@VitalikButerin/a-proof-of-stake-design-philosophy-506585978d51)
* [Why Proof of Stake (Nov 2020)](https://vitalik.ca/general/2020/11/06/pos2020.html)
