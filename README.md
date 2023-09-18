# Aptos Web3 Gaming Framework

## Overview

This comprehensive suite of modules has been designed to offer a decentralized and interactive gaming experience on the Aptos blockchain. Leveraging the power of smart contracts, NFTs and decentralised marketplaces, we provide a feature-rich toolkit for game developers to build fully on-chain games.

---

## Table of Contents

- [Overview](#overview)
- [Motivation](#motivation)
- [Features](#features)
  - [NFT Staking and Upgradable NFTs](#nft-staking-and-upgradable-nfts)
  - [In-game Decentralized Marketplace](#in-game-decentralized-marketplace)
  - [On-chain PvE Battles](#on-chain-pve-battles)
- [Use Cases](#use-cases)
- [Additional Resources](#additional-resources)

---

## Motivation

As web3 gaming continues to evolve, the need for secure, transparent, and customizable solutions has never been greater. The Aptos Web3 Gaming Framework aims to meet this demand by providing a robust set of features that enable game developers to:

- Implement NFT staking mechanics and incentivize user engagement.
- Create a decentralized marketplace for in-game resources with many-to-one swaps.
- Integrate on-chain PvE battles for a fully interactive gaming experience.

---

## Features

### NFT Staking and Upgradable NFTs

**Repository**: https://github.com/aptos-gaming/upgradable-nft-staking

**Purpose**: This module allows players to stake their NFTs to earn in-game resources (fungible or semi-fungible assets). Players can also spend the resources to upgrade their NFTs, which increases the yield they receive from staking.

**Key Features**:
- Basic and advanced staking options.
- Ability to spend resources to upgrade NFT "level" to increase staking rewards.
- Event tracking for staking, unstaking, and claiming rewards.

---

### In-game Decentralized Marketplace

**Repository**: https://github.com/aptos-gaming/in-game-coin-swap

**Purpose**: Higly customizable decentralized marketplace for trading and crafting in-game assets. Players can swap multiple resource tokens for a single new item. This is useful for many gaming mechanics such as advanced resource production, recruitment of new units, weapon crafting etc.. For instance, 10 iron coins + 5 wood coins can be swapped to 1 sword coin.

**Key Features**:
- Multi-resource trading.
- Any craftable items like swords, shields, space ships, etc.
- Proportional trading based on set ratios.

---

### On-chain PvE Battles

**Module**: https://github.com/aptos-gaming/on-chain-pve-battles

**Purpose**: This module enables players to engage in PvE (Player vs. Environment) battles. Players can recruit various units and launch attacks against NPCs (Non-Player Characters) to loot their resources.

**Key Features**:
- Recruitment of various unit types.
- On-chain battles against NPC characters.
- Potential for loot and resources from victories (or losses if the player was defeated).

---

## Use Cases

1. **Resource Farming**: Use the NFT staking and upgradable NFTs feature to create an income stream of gaming resources. These can be used in other aspects of the game such as crafting or recruiting units.

2. **Item Crafting**: Utilize the in-game decentralized marketplace to craft unique items. These items could have specialized uses in PvE battles or could be traded/sold to other players.

3. **Battle Mechanics**: Integrate the On-chain PvE Battles feature to provide an action-packed experience. Players could potentially gain unique items, or rare resources from the NPCs they defeat.

---

## Additional Resources

For code examples and implementation details, please refer to the README files in the individual repositories for each module:

- [NFT Staking and Upgradable NFTs](https://github.com/aptos-gaming/upgradable-nft-staking)
- [In-game Decentralized Marketplace](https://github.com/aptos-gaming/in-game-coin-swap)
- [On-chain PvE Battles](https://github.com/aptos-gaming/on-chain-pve-battles)

---

Contributions are welcome! Feel free to submit pull requests or open issues.
