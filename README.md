# Luckiton - Raffle application based on Ton ecosystem

## Overview

We propose introducing a **high-interactivity** application, specifically a raffle, into the TON ecosystem. Traditional raffles often rely on server-side calculations for number generation and prize distribution, which **lack transparency** as the code and numbers are not publicly accessible. This opacity increases the **risk of potential cheating**. By migrating the **calculation process** to the TON network, we can effectively mitigate these cheating concerns and ensure a more transparent and secure raffle experience.

## Use Case

- KOLs / Creators can launch a raffle campaign to increase subscribers and followers engagement.
- Crypto projects can launch a raffle campaign to incentive users to promote their projects.
- Groups of users can participate for fun and entertainment.

## Feature

- Users have the ability to create raffle campaigns.
    - Supports various **raffle methods**: time-based raffle, manual raffle, raffle based on the number of participants.
    - Allows the **configuration of prizes:** FT, NFT.
    - Supports setting **entry requirements**: such as following a **channel**, tweeting, and more.
    - Provides convenient **sharing options** through links and QR codes.
- Users can actively participate in raffle campaigns and have the opportunity to win rewards.
- Users can easily access their participation history and view records of past raffles.

## Benefits for Ton Ecosystem

In the context of the entire TON ecosystem, the provision of interactive tools based on TON for Telegram has the potential to boost the adoption of TON and wallets. This applies to both the existing user base within Telegram and the external traffic that can be converted through referral links. Moving forward, the plan is to abstract this functionality into an **SDK**, allowing for **seamless integration into TON SocialFi and GameFi projects**. Furthermore, there are plans to explore additional **gameplay options** and expand the range of **interactive experiences**.

## Team

The team has a strong background as one of the **early developers** for WeChat Mini Programs and has received recognition as **excellent cases** in WeChat's public courses. Building upon this experience, we have expanded our focus to the web3 domain for more than 3 years, with a particular emphasis on Ethereum's DeFi and Infrastructure sectors. As a result, we have developed a **deep understanding of both web2 and web3 ecosystems**.

## Overview of the technology stack to be used

- Ton **Smart Contract**: Implementing raffle functionality and distributing rewards.
- **Backend Service**: Implementing verification for participation requirements in lottery entries and managing meta-information for raffle campaigns.
- **TWA**: Enabling initiation and participation in raffle interactions.
- **Bots**: Pushing raffle results.

## How does your project implement the TON blockchain and which parts will be on-chain?

The lottery logic is implemented on the TON network through **smart contracts**.

- **Raffle Rules**: Raffles can be conducted based on the number of participants, specific time, or manual selection.
- **Raffle Rewards**: FT and NFT can be chosen as rewards.
- **Reward Distribution**: FT and NFT tokens are transferred to the winners.

The determination of participation requirements and lottery metadata is implemented off-chain.

- **Participation Threshold**: Verification of whether a user meets the participation requirements.
- **Raffle Configuration Information**: Includes the raffle’s name, creation time, creator, and other relevant details.
