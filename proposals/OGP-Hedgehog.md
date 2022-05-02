# Hedgehog strategy 🦔

|  |  |
| -------- | -------- |
| Status | Research is completed, smart contracts are being developed |
| Author   | [Liqui](https://twitter.com/liqui_space)  |
| Discussion   | Medium  |
| Labels | LP-strategy |
| Repo   | https://github.com/leooos33/HDL-strategy-/tree/dev |

## Introduction

An automated strategy that creates a yield-bearing synthetic ETH portfolio by providing liquidity for the ETH-USDC pool on Uniswap V3 and hedging its impermanent losses with LP for the oSQTH-ETH pool.

## Details

The strategy will be implemented as a one-click deposit LP-vault.

* The mathematical model provided in this post: https://medium.com/@yevhenx/hedging-uniswap-v3-with-squeeth-c6c0a8fc5572
* The post that explained rebalance auction: https://medium.com/@yevhenx/on-rebalance-auction-e43c80d8b1ec
* Already implemented as an automated trading strategy: https://github.com/leooos33/HDL-strategy-/tree/dev
* As well as rebalancing bot (keeper).
* The only part that is left is a front end. (On one of the hackathons we have built [DEX](https://app.liqui.space/swap) on Ropsten - contracts + front-end, so this part will not be a problem).

## Milestones

* Prepare the front-end (~2 weeks - 15.05) 
* Post an educational article on the Hedgehog strategy.
* Deploy to mainnet and open deposits with a limited capacity of $100k by the 20th of May.
* Increase capacity
* Develop a delta-neutral UniCrab strategy (LP for ETH-USDC and hedge it with short squeeth).
* Develop a long-vol strategy (long squeeth + 2x ETH short).

### Ideal Launch Date

20.05.2022

## Funding Request and Budget Breakdown

12 ETH

* Design + front-end integration, contract deployment + dev infrastructure, community engagement.
* Development of 2 other strategies.
