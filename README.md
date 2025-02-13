## BITCOIN WALLET

This project is a **Bitcoin wallet manager** that allows users to **create and manage their wallets** on the Bitcoin testnet network, as well as **send and receive bitcoins** through the Bitcoin blockchain. The system provides real-time balance tracking, secure transaction handling, and integrates with AWS services for enhanced security and scalability.

## Getting Started

- Access the system at: **[JVWallet](https://front.jvwallet.site)**
- After creating your wallets, you can get free Bitcoins for transactions from this faucet: **[Bitcoin Testnet Faucet](https://coinfaucet.eu/en/btc-testnet/)**
- You can also check your created wallet and transactions on the **[Blockchain Testnet Explorer](https://blockstream.info/testnet/)**

## Table of Contents

- [Bitcoin Wallet](#bitcoin-wallet)
- [Getting Started](#getting-started)
- [Features](#features)
  - [Functional Requirements](#functional-requirements)
- [Proposed Architecture](#proposed-architecture)
- [Technologies](#technologies)
- [Deployment](#deployment)
- [Development Environment](#development-environment)

## Features

- **Amazon KMS Integration**: Encrypts wallet seed phrases using AWS Key Management Service.
- **Real-time Balance Tracking**: Synchronizes transaction data from the Bitcoin blockchain to keep wallet balances up to date.
- **Asynchronous Processing with Amazon SQS**: Uses AWS Simple Queue Service for scalable background job processing.

### Functional Requirements

- **Wallet Creation**: Allows users to create a new Bitcoin wallet on the network.
- **Transaction Tracking**: Automatically detects and stores all transactions related to managed wallets.
- **Balance Updates**: Updates wallet balances based on incoming and outgoing transactions.
- **Bitcoin Transfers**: Enables users to send Bitcoin transactions to other wallets within the network.

## Proposed Architecture

Below is the proposed architecture for the Bitcoin Wallet system:

![Bitcoin Wallet Architecture](/imgs/system-design.png)

## Technologies

- :star: **Node.js** - Backend runtime
- :star: **NestJS** - Backend framework
- :star: **Angular** - Frontend framework
- :star: **Prisma** - ORM for PostgreSQL
- :star: **Amazon SQS** - Message queue for async processing
- :star: **Amazon KMS** - Key management service for encryption
- :star: **PostgreSQL** - Relational database

## Deployment

- :rocket: **Amazon EC2** - Hosting the backend API
- :rocket: **Amazon S3** - Hosting the frontend application
- :rocket: **Render DB** - Cloud database provider for PostgreSQL
- :rocket: **Nginx** - Reverse proxy for API routing

## Development Environment

- :desktop_computer: **Visual Studio Code** - Code editor
- :desktop_computer: **DBeaver** - Database management tool
- :desktop_computer: **Insomnia** - API testing tool
- :desktop_computer: **Git** - Version control system
- :musical_note: **Spotify** - Music for better focus 🎵
- :nerd_face: **ChatGPT & Stack Overflow** - Debugging and problem-solving resources
