# Idea

Implement a User retention tool(cohort analysis and funnel analysis) for Opyn V1 and V2 protocol.

## Introduction

Implement User retention tool(cohort analysis and funnel analysis) for Opyn V1 and V2 protocol.

![cohort analysis](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/b206d675-eb7c-4947-9ee0-7d0ac99c1fae/Screen_Shot_2021-04-25_at_5.30.53_PM.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAT73L2G45O3KS52Y5%2F20210430%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20210430T063659Z&X-Amz-Expires=86400&X-Amz-Signature=1d71da0698e4e4e7437027216b8abbda4ba5804a8f1893cf04330dad15ca1073&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22Screen_Shot_2021-04-25_at_5.30.53_PM.png%22)

## Details

**Team Size** : 3

### Importance of User Retention Analysis

- Cohort analysis will help measure the user engagement of Opyn users over time. It will help track repeat users on Opyn platform and understand what makes them happy.
- The tool will help understand vital metrics such as churn, users lifecycle and customer lifetime value.
- The analysis can be used to identify the success of the feature adoption rate.
- A funnel report gives information on how Opyn users progress through different stages and where they drop off. Funnel analysis help identify barriers that cause users to leave before reaching a conversion point.

### Features

- Display aggregated metrics e.g. total Deposit transactions, Total unique users doing deposit
- Monthly Cohort analysis of unique user DepositCollateral transactions.
- Monthly Cohort analysis of unique user WithdrawCollateral transactions.
- Monthly Cohort analysis of the total Deposit Collateral amount.
- Monthly Cohort analysis of the total withdrawn Collateral amount.
- DepositCollateral Funnel analysis and graph.
- WithdrawCollateral Funnel analysis and graph.

Please see the user retention tool implemented for AAVE protocol.
https://github.com/dappquery/aave-user-retention-analytics

## Milestones

- Data will be pulled from Opyn V1 and V2 protocol subgraph and after transformation, data will be populated in SQL tables in the Postgres database.
- SQL queries will be written to query data from the Postgres database.
- Graph will be displayed on the SQL query result.
- DepositCollateralAction subgraph entity will be used for tracking the user's deposit on a month-by-month basis.
- WithdrawCollateralAction subgraph entity will be used for tracking the user's deposit on a month-by-month basis.
- The dashboard/tool will be hosted on a subdomain e.g. opyn.dappquery.com.

### Ideal Launch Date

2-3 weeks

## Funding Request and Budget Breakdown

12k USDT

Grant will cover below features:

- Development efforts for the above-mentioned features.
- Infrastructure cost for running and maintaining the dashboard on the AWS cloud.
- Hosting the project on remote servers.
- Postgres database cost.
- Maintenance and support for a year.
- Dappquery is TheGraph Indexer. We will be indexing Opyn V2 subgraph
