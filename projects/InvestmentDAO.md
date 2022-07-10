---
layout: default
title: Investment DAO Manager
parent: Projects
nav_order: 1
---

# Investment DAO Manager

## Overview

Investment DAO Manager is a DAO Governance Portal aimed at crypto investment DAO's and Hedge Funds. It provides a simple mobile app allowing your organization to conduct governance votes and manage investment funds from one simple interface.

## Features

1. DAO Multi-Sig Treasurery
    * To begin with we will only support Multi-Sig Treasureys on the Flow Blockchain. However we plan to expand to support other blockchains in future releases.
2. DAO Multi-Sig Exchange Controls
    * Setup your exchange accounts to be managed by DAO Manager to ensure no one person has access to your exchange accounts. We will support KuCoin at launch with Binance and other exchanges to come in the future.
2. DAO Governance Votes
    1. General Votes - This type of ballot can be used as a cache all for any type of organizational policies or off-chain actons.
    2. Create Fund - This type of ballot is used to vote on the create of a new investment fund and trading bot.
    3. Disolve Fund - This type of ballot is used to vote on selling all assets in a fund and returning the funds to the respective DAO members.

## Status

We are currently developing the smart conctract for DAO Governance as well as the iOS App. As majority of the world operates from their phones, we have decided to not build a website management portal at this time. However, if you are interested in helping port the iOS app to Android, please reach out to us at help@boisesfinest.com.

## Current Issues

1. FCL-Swift needs updates - FCL-Swift currently does not support account proofs which are needed to properly secure access to the backend and access the trading bots. The FCL-Swift project has received a bounty from the Flow Development Fund and it is expected to be fully compliant with standard FCL by the end of the year.
    * Until this is resolved we will not be able to move beyond a private beta phase as we must tightly control who has access to the backend.
2. V1 of the Governance Contract will not support adding additional funds to investment funds. There are some complexities that need to be be worked out between the bot platform's current inabbility to save state between reboots and tracking contributions/evaluation in the smart contract.

## Related Projects

1. Project Toucans from Emerald City DAO.
    * We are huge supportors of Emerald City DAO and the work they are doing with Project Toucans. Our project is specefic to a much more limited set of DAO Governance models and voting options. As both projects evolve we hope to work with Project Toucans to ensure investment DAOs utilziing Project Toucans can also use the addtional features avaiable within our project.