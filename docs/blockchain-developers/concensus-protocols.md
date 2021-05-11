---
layout: default
---

# Concensus Protocols

Some good articles on concensus protocols.

1. [https://files.osf.io/v1/resources/8jxaq/providers/osfstorage/5c9ca949e0a7de001994abac?action=download&direct&version=1](https://files.osf.io/v1/resources/8jxaq/providers/osfstorage/5c9ca949e0a7de001994abac?action=download&direct&version=1)
2. [https://res.mdpi.com/d_attachment/mathematics/mathematics-08-01782/article_deploy/mathematics-08-01782-v2.pdf](https://res.mdpi.com/d_attachment/mathematics/mathematics-08-01782/article_deploy/mathematics-08-01782-v2.pdf)




# 1. A Non Comprehensive table of comparison amongst concensus protocols


| PoWork          | PoStake | PoSpace | PoElapsed Time   | PoHistory  |
|:------------------|:------|:------------|:-------------|:-----------|
|computing the hash values and validating the transactions until a specified number of trailing zeros are found in the hash value.The number that generates the hash with the specified number of trailing zeros is known as a nonce. A nonce is defined as a random number that generates the specified number of trailing zeros in the hash function. | The miner has to allocate a particular part of his cryptocurrency to start validating. If the miner succeeds in invalidating the transaction, then the award is the stake they had pledged initially, along with certain transaction fees   | PoSpace consumes disk space and incentivizes miners with the most considerable disk space allocated to a block. Implemented using the hard-to-pebble graphs, it's used to solve the [pebbling game](https://math.mit.edu/research/highschool/primes/materials/2016/conf/10-2%20Bhupatiraju-Kuszmaul-Vale.pdf). Once the solutions are computed, the miners compare their solutions, and the solution with the best time and space complexity is rewarded with the next block.         | Each node in the network is assigned a random waiting time. The first node to complete the randomly chosen period validates the new block. The specialized hardware puts the processor to sleep during the wait time—this repeats over all the blocks in the network. | High frequency [Verifiable Delay Function](https://www.youtube.com/watch?v=_-feyaZZjEw&t=11s). A Verifiable Delay Function requires a specific number of sequential steps to evaluate, yet produces a unique output that can be efficiently and publicly verified. |
| bitcoint, litecoint            | ethereum       | Burstcoin, SpaceMint  | Sawtooth (IBM)  | Solana |
| power hungry, resource incentive            | env friendly, no special hw required       | resource biased  | specialised hw  | env friendly |
| hacker needs 51% control            | hacker needs 50%       | -  | -  | - |
| Probabilistic-finality            | Probabilistic-finality       | -  | -  | - |



# Other interesting Concensus Algorithms

1. [PoAuthority](https://academy.binance.com/en/articles/proof-of-authority-explained)
2. [Delegated PoStake](https://academy.binance.com/en/articles/delegated-proof-of-stake-explained)
3. Byzantine Fault Tolerance
4. Practical Byzantine Fault Tolerance
5. Ripple
6. [Delayed PoWork](https://academy.binance.com/en/articles/delayed-proof-of-work-explained)
7. [Leased PoStake](https://academy.binance.com/en/articles/leased-proof-of-stake-consensus-explained)
8. [PoBurn](https://academy.binance.com/en/articles/proof-of-burn-explained)
9. [Hybrid PoW/PoS](https://academy.binance.com/en/articles/hybrid-pow-pos-consensus-explained)
10. Sieve
11. PoWeight
12. [Proof of Person](https://docs.idena.io/docs/wp/technology#proof-of-personhood), [Wikipedia](https://en.wikipedia.org/wiki/Proof_of_personhood), [Other notes](https://gist.github.com/resilience-me/f690d50eecb6ca7b5fdf1e4c49cca0e1)
13. [Proof of Person Work](https://eprint.iacr.org/2016/145.pdf)