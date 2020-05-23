# Beacon Chain — Ethereum 2.0

*The Beacon Chain is a proposal for a combined Sharding and Proof-of-Stake architecture.*

## OVERVIEW

Prior to [the eth2.0 proposal](https://github.com/ethereum/eth2.0-specs/blob/master/specs/casper_sharding_v2.1.md), plans for scaling Ethereum were seperated into two projects. [Casper FFG](1) and [Sharding](https://github.com/ethereum/sharding/blob/develop/docs/doc.md).

The foundation has decided to combine the teams scaling efforts around this new spec.

Ethereum Serenity is a WW3-proof unbiasable randomness which favors livelyness.

> The Ethereum 2.0 blockchain consists of 1,025 proof-of-stake blockchains; the "beacon chain" and 1,024 "shard chains". — [lighthouse](https://github.com/sigp/lighthouse/#what-is-ethereum-20)

### Casper FFG

1500 Eth would be staked in a contract by someone wishing to be a block validator...

Slashing conditions

Need 2 blocks attested before –– 

### Sharding

### RANDAO

`17m, 128 slots –––`

*Each slot has a beacon proposer -- which releaves a secret which is the source of local entropy and it creates a pool of entropy...*

Guaranteed delay of 1 epoch,

- Comit Reval: Attack / Last revealer can influence the randomness
- Threshold Crypto: Stops the whole blockchain
- A source of entropy for the base layer protocol --
- Weak guantees as it's biasable
- Verifiable delay functions 
- Reorgs -- If you know ahead of time that you will be able to mine 30 blocks ahead you can perform a reorg.

### Validator

Serialisation set may need to be in a tree foramt if it gets to large –– currently it's only being held in SSZ.

##### Prysmatic Labs

Implementing Validator clients to be multi tenant –– to allow multiple validator clients can utilise one stake, opens up Validator as a service.

Storage, using BoltDB

###### Possible Contributions:

- Dashboard to monitor validator syncing
- Testnet Cluster of Validator nodes with

###### Loadstar

- Validator on a phone

### Difinity

- Whole blockchain will stall if ––– ??
- Why add centralised hardware vs just having 10% of people won't go offline –– ?? 
- Strong livelness and hardware or Less livelyness but needs to be online

### Applicaiton Layer

- A shard...

### The Stake — Why 32 Eth?

- *"so that if all eth was staked...?"*

### Migration

- A token contract could be created to handle the migration to beacon using a merkle proof utility -- a EthPrize could be proposed for this.

###### USEFUL LINKS

1. [Beacon Chain Repository](http://github.com/ethereum/beacon_chain)
2. Difinity @TODO RESEARCH

###### References

[1]: https://eips.ethereum.org/EIPS/eip-1011	"Casper the Friendly Finality Gadget"
[2]: https://www.youtube.com/watch?v=GhuWWShfqBI	"2. Ethereum and Scalability Technology（Sharding）-Hsiao-wei Wang"

# TODO

- Difinity Research
- Cryptoeconomic Study

