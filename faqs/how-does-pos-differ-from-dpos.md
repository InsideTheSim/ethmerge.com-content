---
title: How does proof-of-stake (PoS) differ from delegated-proof-of-stake (DPoS) used in other blockchain projects?
weight: 4.0
attribution:
  -
    name:
    link:
---

**Delegated-proof-of-stake (DPoS)** is a consensus mechanism, and often also a governance mechanism, that was originally [pioneered by Bitshares](https://how.bitshares.works/en/master/technology/dpos.html) and has since been adopted in many blockchains. A DPoS chain's consensus is run by a small number of nodes, called **block producers** (eg. EOS has 21 [block producers](https://coincentral.com/what-is-an-eos-delegate/)). To become a block producer, one must first sign up as a **delegate**, and invite coin holders to vote for you. The delegates with the most coins voting for them become the block producers.

The main challenges with DPoS are twofold:

1. The concentration of block producing rights into 21 delegates is a large centralization risk; even after being elected, the delegates could seize power, start censoring transactions that they dislike including those that vote against them, etc.
2. Coin voting is vulnerable to collusion and bribe attacks

These issues are discussed in greater length in these posts:

* [Notes on Blockchain Governance](https://vitalik.ca/general/2017/12/17/voting.html)
* [Governance Part 2: Plutocracy Is Still Bad](https://vitalik.ca/general/2018/03/28/plutocracy.html)
* [On Collusion](https://vitalik.ca/general/2019/04/03/collusion.html)

These concerns are not mere theory; wealthy EOS ecosystem participants [have been caught making agreements to vote for each other](https://twitter.com/MapleLeafCap/status/1044958643731533825) or in exchange for compensation.

**Proof-of-stake (PoS)** as implemented in Ethereum does not have this notion of coin voting; instead, users run their own nodes and stake their coins directly. Of course, users are free to "vote for" other participants by joining their staking pools instead of staking by themselves. However, the key difference is that this is not vulnerable to bribes and collusion in the same way because _the incentives pass through_: if you join a staking pool that performs well, you get a higher reward, and if you join a staking pool that attacks the network and gets [slashed](https://www.linkedin.com/pulse/slashing-penalties-explained-2-minutes-ethereum-20-andreas-vlachos?trk=read_related_article-card_title), you will not be able to get all of your money back. This is different from coin voting, where someone who votes for a bad delegate does not suffer any personal penalties that someone who did not vote for that delegate does not suffer as well. This creates a very different and much safer set of incentives, and decentralization is boosted further by the very large number of stakers who avoid staking pools and instead stake by themselves.
