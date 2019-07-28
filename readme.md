# Desmos

#### a social networking ecosystem of the users, by the users, for the users

Kwun Yeung (kwun@forbole.com) <br>
Terence Lam (terence@forbole.com) <br>

NOTE: This document is a work-in-progress and we are still actively developing it. Your feedback is highly appreciated. Please check our update regularly.

## Table of Contents

- [Summary](#summary)
- [Background](#background)
- [Problem Statement](#problem-statement)
- [Desmos](#desmos)
  - [The blockchain](#the-blockchain)
    - [Inflation](#inflation)
    - [GINI-sensitive sublinear voting power](#gini-sensitive-sublinear-voting-power)
    - [Minimum commission rate](#minimum-commission-rate)
  - [The token](#the-token)
- [Organization](#organization)
  - [Forbole Limited](#forbole-limited)
  - [Big Dipper](#big-dipper)
  - [Team](#team)
- [Roadmap](#roadmap)

## Summary

Desmos [ˈdɛsmɒs] is a public blockchain for social media applications built with Cosmos SDK and Tendermint. It is similar to Cosmos Hub with different staking and minting modules. The first module of Desmos is Magpie, which provides identity and accountability to validators, delegators and other types of stakeholders with a novel and generalizable temporary key pair using browser-based WASM. Desmos will gradually include more modules specifically designed for decentralized social networking and digital advertising applications. It will also serve as a regional Hub in South China and Southeast Asia and a testbed of different interesting parameters and governance method.

Initially, we will bootstrap early users by building a decentralized microblogging platform on top of Big Dipper to solve one pain point: the existing and new Cosmonauts do not have a way to know each other through a decentralized and verifiable manner. As Big Dipper is one of the most popular block explorers for Cosmos ecosystem chains, many people who are interested in Cosmos will definitely visit Big Dipper. A decentralized microblogging platform secured by validators is an interesting way for Cosmonauts to connect. 

After experiencing various blockchain projects, we hope to make Desmos a “validators first” project. We believe engaging validators are crucial to the success of Desmos, as they are not only our security guards but also our community builders. This is particularly important to a social network-specific chain like Desmos. We will design our incentivized program and fundraiser to reflect this “validators first” philosophy.

## Background

In mid of 2017, after nearly 8 years of partnership in running a digital agency, Kwun and Terence would like to apply blockchain technology to change social networks which are monopolized by centralized powers who abuse users’ privacy to maximize their own benefits. They come up with an idea of a decentralized business network to encourage people to help other to succeed by referring suitable business and career opportunities with each other. They then cofounded Forbole Limited in Oct 2017 to pursue this goal. 

In late 2017, while searching for the suitable technology to build this decentralized business network, they stopped at Tendermint. They further discovered Cosmos project and were fascinated by its vision. They started to use Cosmos SDK, which was still in its early stage, to build a testnet.

They knew that they needed some validators to run the testnet. So they started to learn how to become a validator by participating in the testnet of Cosmos Hub and the [validators community](https://blog.cosmos.network/q-a-session-three-cosmos-validators-share-their-experience-ce6501a5d61c). 

At the same time, they also needed a blockchain explorer for Forbole’s testnet. They were not satisfied with the official explorer and hence they decided to build one. In August 2018, HackAtom 3 was announced. So they improved the UI design of their explorer and gave it a name to participate the competition. This was how [Big Dipper](http://cosmos.bigdipper.live) was born. It earned a prize in [HackAtom 3](https://blog.cosmos.network/hackatom3-winners-announced-95933b6e23b5).

In Feb 2019, Forbole completed the famous [Game of Stakes](https://blog.cosmos.network/game-of-stakes-closing-ceremonies-eddb71d3b114) as a named winner in the Never Jailed category. 

Forbole is recognized through its works in Cosmos ecosystem. With this worldwide traction, now is the right time to resume the development of decentralized social network. We start with Desmos, which will be a Cosmos ecosystem chain specific for social media. Its first application will be a microblogging platform to be integrated to Big Dipper. With the working prototype of this concept, we have won a prize in [HackAtom Seoul](https://blog.cosmos.network/cosmos-hackatom-seoul-winners-d6badbd0629b) in Jul 2019. 

## Problem Statement

## Desmos

The name Desmos was inspired from Ancient Greek desmós (δεσμός) which means “bond, relationship”. We use Desmos for both the names of the blockchain and its staking tokens. 

### The blockchain

#### Inflation

[]

#### GINI-sensitive sublinear voting power

[]

#### Minimum commission rate

There has been much debate about the impact that validators charging very low commission has on the Cosmos Hub, particularly with respect to the decentralization of the Cosmos Hub and the sustainability for validator operations [(see Proposal 12 on Cosmos Hub)](https://cosmos.bigdipper.live/proposals/12). While we think that imposing a minimum commission rate in the protocol will set a dangerous precedent of planned economy, we would like to use Desmos as a testbed for a minimum commission rate.  Our proposed minimum commission rate is 15%. 

### The token

It is the native staking token which serves as a license for its holders to contribute to the security and governance in exchange for the incentives

## Organization and projects

### Forbole Limited

Forbole Limited (“Forbole”) is a for-profit company limited incorporated in Hong Kong in Oct 2017. The main businesses of Forbole will be technology solution service and digital asset management. Forbole is the team to build Desmos and Big Dipper.

### Big Dipper

Big Dipper, is an award-winning open-source block explorer and delegator tool for Cosmos ecosystem chains used by people from over 130 countries. It is currently exploring [Cosmos Hub](https://cosmos.bigdipper.live/validators?sort=votingPower&dir=-1_), [Iris Hub](https://iris.bigdipper.live/validators?sort=votingPower&dir=-1), [Terra Money](https://terra.bigdipper.live/validators?sort=votingPower&dir=-1), [Kava](https://testnet-1.kava.bigdipper.live/validators?sort=votingPower&dir=-1), [BitSongs](https://testnet-1.bitsong.bigdipper.live/validators?sort=votingPower&dir=-1), [Sentinel](https://explorer.sentinel.co/validators?sort=votingPower&dir=-1), [Cyber Congress](https://cyberd.ai/validators), [LikeChain](http://35.226.174.222/) and [Regen Network](http://bigdipper.regen.network). You can check the repo of Big Dipper [here](https://github.com/forbole/big_dipper).

Another related project is a Bot that monitor the chain when something happened to a specific validator, and send alert through Telegram. It sends alert every 15 seconds, if there is something happened during that time. You may check this [repo](https://github.com/forbole/gaia_bot_monitor).

### Team

We are expanding our distributed team across the globe. If you share the same vision with us to disrupt the status quo in social network, come to join us! Please refer to this [repo](https://github.com/forbole/careers) for the job openings of Forbole.

## Roadmap
