# Defi Staking App

## Overview
This is a decentralized finance (DeFi) staking application built using Solidity, React, and Truffle. The application allows users to stake Tether (USDT) tokens and earn rewards in RWD tokens.

## Features
- **Staking**: Stake your Tether tokens to earn rewards.
- **Airdrop**: Special airdrop feature for token holders.
- **Decentralized Bank**: Smart contract acting as a decentralized bank.

## File Structure
### Migrations
- `1_initial_migration.js`: Initial migration script.
- `2_deploy_contracts.js`: Script for deploying smart contracts.

### Components
- `Airdrop.js`: Airdrop component.
- `App.js`: Main App component.
- `Main.js`: Main component.
- `Navbar.js`: Navigation bar component.
- `ParticleSettings.js`: Particle settings component.

### Smart Contracts
- `DecentralBank.sol`: Decentralized bank contract.
- `Migrations.sol`: Migrations contract.
- `RWD.sol`: RWD token contract.
- `Tether.sol`: Tether token contract.

### Scripts
- `issue-tokens.js`: Script for issuing tokens.

### Tests
- `decentralBank.tests.js`: Tests for the DecentralBank contract.

