---
title: Do I really need 32 ETH in order to run a validator on the Ethereum network?  That seems like a lot of money.
weight: 5.1
attribution:
  -
    name: takezo
    link: 
---

In short, no. 

32 ETH is a lot of money, but it was an amount chosen with good reason.  It is high enough to keep network participants honest due to the risk of lost ETH if they behave dishonestly, but it is also low enough so that a sufficient number of validators can exist on the network - allowing it to maintain a high level of security.  Although technically you do need 32 ETH to activate and run a validator, a service such as [RocketPool](https://www.rocketpool.net/) allows someone with 17.6 or more ETH (16 ETH + 10% collateral) to be matched with 16 ETH deposited to the RocketPool smart contract by other stakers (who typically also have less than 32 ETH or don't want to run a validator themselves) so that you may run a validator without owning 32 ETH yourself.

Their [guides for setting up your own node](https://docs.rocketpool.net/guides/) are very easy to follow, you can either [run on your own hardware](https://docs.rocketpool.net/guides/node/local/hardware.html) or [on a service like AWS](https://docs.rocketpool.net/guides/node/vps/providers.html). If you'd prefer to have another service manage your node (handling updates, monitoring, etc.), [allnodes](https://www.allnodes.com/rpl/staking) allows for this.
