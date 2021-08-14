# Opyn Gamma Automator

|  |  |
| -------- | -------- |
| Status | Draft |
| Author   | Willy Shen  |
| Discussion   | Discord  |
| Labels | |
| Repo   | [https://github.com/shenwilly/opyn-auto](https://github.com/shenwilly/opyn-auto)  |

## Introduction

Automator contracts for redeeming otokens and/or settling vaults on Gamma.

## Details

- Option holders can approve their tokens for automatic redemption on expiry (if ITM).
- Option writers can set us as operator for automatic settlement of vaults.

We use [Gelato](https://github.com/gelatodigital/poke-me) to automate the execution. 
A small percentage of payouts are taken from each successful order to cover for Gelato gas fees.

## Milestones

- App is currently live at [https://autogamma.netlify.app/](https://autogamma.netlify.app/)
- Get feedback and make changes.

### Ideal Launch Date

- Contracts and web app are already live.

## Funding Request and Budget Breakdown
- 0.5 ETH for contract deployment and testing on mainnet.
