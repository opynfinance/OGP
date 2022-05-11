# Pegasus Finance

|            |                               |
| ---------- | ----------------------------- |
| Status     | Draft                         |
| Author     | {Andy Wang}                   |
| Discussion | {Discord}                     |
| Labels     |                               |
| Repo       | {https://pegasusfinance.xyz/} |

## Introduction

We are building a perpetual protocol to allow traders to speculate on DeFI yields & interest rates. (e.g. Squeeth Funding Rate).

Each market consists of a synthetic token that tracks the value of the underlying interest rate it represents. For the Squeeth Funding market, if the current funding is 3.6%, the value for each synthetic token to track is 0.036 WETH. This tracking is done via funding rates as in other perp markets (e.g. dydx).

Our motivations for this project are that we believe perpetual contracts are the superior form of derivative swaps and thus products that leverage them will find the greatest product market fit in DeFi derivatives. Squeeth funding rates are particularly interesting as they are an indication of the implied volatility of ETH. So, the more volatile the market expects ETH to be, the higher squeeth funding rates are. The less volatile the market expects ETH to be, the lower squeeth funding rates will be.

## Details

Pegasus Finance has already implemented a V1 version of the squeeth funding rate market. To date it has had 271 ETH in volume and has continued to grow. Moreover, our community has created educational content on Squeeth via twitter threads and medium posts. See: https://twitter.com/drismegistus/status/1518062419163107328, https://twitter.com/saintnapa/status/1498490372493774850, https://twitter.com/googrish/status/1496982104353042433. By creating a powerful speculation market on top of Squeeth we help increase retail exposure to Squeeth. Pegasus Finance has not raised any capital and so we are requesting this grant to help fund further development and educational content on the Squeeth market. The initial market can be used here: https://trade.pegasusfinance.xyz/.

We think the two products have a strong alignment. Pegasus Finance introduces an integration on top of Squeeth and can help increase retail awareness of the product. Trading the squeeth funding rate can also be a means for users to hedge the high funding rates which has been one criticism of Squeeth. Ie. when they open a long and the funding rates rise, they can offset the costs by longing the rate on Pegasus Finance.

## Milestones

1. Running simulations to ensure fair AMM parameters
2. Eng work to set up liquidation bots and price feeds for new market
3. Marketing work

### Ideal Launch Date

By early June

## Funding Request and Budget Breakdown

30k

1. Eng work for markets
2. Infra costs for price feeds
3. Marketing spend for new market
4. Some capital to seed the AMM liquidity pool
