# Sushi Onsen rewards snapshot

This repo contains dataset of VSP rewards to VSP-ETH LP token holders who stakes their LP tokens in Sushi Onsen.

Rewards will be distributed weekly, as announced, via Merkle Claim and dataset will be published in this repo for each distribution.

## What is dataset?
A Merkle tree will be created using user `address` and rewards `amount`. Dataset contains user's address, rewards amount and Merkle proof. This information will be used to claim rewards.

## How to claim?
- Head over to [pure.finance](https://pure.finance/)
- Choose `Merkle Claims` options
- Connect your wallet using Metamask or WalletConnect.
- Input `claimId` and now you should see balance available to claim.
- Click `Claim` button and submit the transaction via Metamask/WalletConnect.
> PS: **ClaimId** will be provided once Merkle claim is setup.