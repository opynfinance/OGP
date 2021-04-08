# Project Ideas

## Introduction

Many of the best community ideas we’ve supported have been ones that surprised us, not ones we were waiting for.

There are, however, some developer projects that we’re very interested in seeing. Below are our updated developer community project ideas, which outline some of those ideas in general terms.

Please don’t feel that you need to work on one of these ideas in order to apply for, or receive, an Opyn developer grant. The developer community project ideas mostly exist to encourage you to apply if you’re already working on an idea in DeFi that could integrate with options.

## Ideas

### Simplified interface for options beginners (interactive interface)

- **Tags:** Front end
- **Description:** Options can be intimidating. Create an interface that breaks down options into simple steps (i.e. Do you want to earn income or speculate? → 2 Do you think the price of ETH will be higher or lower on X date, etc.) to help new options traders better understand how to trade options. This could also be a beginner options interface that has more educational content displaying on the front end. The purpose of this interface will be to make options trading more approachable.

### More advanced interface for quant traders

- **Tags:** Front end
- **Description:** Advanced options traders need access to calculations, figures, and charts that might be too confusing for beginner or intermediate traders. Examples of more advanced trading platforms are [Deribit](https://www.deribit.com/), [DyDx](https://dydx.exchange/), [LedgerX](https://www.ledgerx.com/options) or more traditional options trading platforms such as [ThinkorSwim](https://www.tdameritrade.com/tools-and-platforms/thinkorswim/desktop.page).

### Contract that autos-sends settlement back to users (auto redeem) using operator

- **Tags:** Contract, (Front-end)
- **Description:** Currently, Opyn users must return to [Opyn.co](http://opyn.co/) to redeem their collateral after an option expires. Using Opyn's unique operator function, build a smart contract that automatically redeems oTokens for users after expiration. Users will need to pre-approve the contract to interact with their address, however the purpose of this contact is to eliminate the need for users to manually redeem their collateral or their options proceeds.

### Something similar to a capital protected investment, where the contract use the income stream from interest bearing token to buy call options. (or use that interest to sell put options)

- **Tags:** Contract, Front-end
- **Description:** A Capital Protected Investment (CPI) provide upward profit potential, and also guarantee the protection of your capital investment (fully or partially) (e.g. [Investopedia Example](https://www.investopedia.com/articles/investing/073115/how-create-capital-protected-investment-using-options.asp)). In essence this contract would invest the yield earned from other DeFi protocols into income generating OTM options, increasing the overall yield that a DeFi investor would earn over a period of time.

### Position builder

- **Tags:** Front-end
- **Description:** To help users better understand options, create an options "position builder," by asking basic questions (e.g. do you think ETH will be above $2000 on March 18). Once a user has gone through the position builder steps, allow the trader to buy or sell the option by directly linking them to that option options on [Opyn.co](http://opyn.co/)

### Gain & loss calculator

- **Tags:** Front-end
- **Description:** To help users better understand options' potential gain / loss under various market conditions, create a gain loss calculator / simulator for each option position on [Opyn.co](http://opyn.co/). This can be in the form of a widget or an integration with Opyn's front end.

### An options trading leaderboard (e.g. [gamified leaderboards](https://matcha.xyz/moolah))

- **Tags:** Front-end
- **Description:** To add a gamification element to Opyn's options platform, create a leaderboard that ranks users' addresses by trading volume, # of contracts traded, or another metric.

### Support improving gammaportal.xyz

- **Tags:** Front-end
- **Description:** [gammaportal.xyz](http://gammaportal.xyz/) is a community project that serves as an alternative to the [Opyn.co](http://opyn.co/) front end and trading interface. Support Opyn developers by working with the team to add new features to the trading dashboard.

### Dashboard that shows basic KPIs

- **Tags:** Front-end
- **Description:** Create a public facing dashboard that provides viewers with protocol metrics, charts, and analyses of both v1 and v2 metrics.

### Sdk for Gamma protocol

- **Tags:** SDK
- **Description:** Create a python / js / rust library to interact with our protocol. This includes setting up some basic architecture, testing framework, and having wrapping functions to batch actions to help other developers integrating with opyn

### Integrate with [zerion's defi sdk](https://github.com/zeriontech/defi-sdk)

- **Tags:** SDK
- **Description:** Write **an Gamma** adaptor to connect to Zerion's sdk, so other apps using Zerion sdk can easily pull account state in Opyn.

### Vault saver function (Defi Saver)

- **Tags:** Integration
- **Description:** A vault saver function that can be used when we have liquidations. The vault saver can deposit collateral to save the vault from getting liquidated, or buy back options using collateral with an atomic transaction, withdrawal collateral do a trade on 0x and burn oTokens all in the same transaction)