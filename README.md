# Blockchain Truth Machine

**Portfolio case study: a Web3 prototype for writing, reading, and verifying data across Bitcoin, Ethereum, and IPFS.**

## Overview

Blockchain Truth Machine explored how application data can be anchored in decentralized networks and verified through transaction hashes. The prototype combined a Django backend with wallet-based browser interactions, REST endpoints, and IPFS file storage.

## What I built

- Django and Django REST Framework API for wallet addresses, transaction metadata, and IPFS records
- Ethereum browser-wallet integration with MetaMask and Web3
- IPFS upload workflow with content-hash persistence
- Data models for blockchain transactions, wallet accounts, and stored files
- Docker-based local environment and PostgreSQL support
- Research and technical documentation covering Bitcoin data-recording approaches

## Architecture

1. The browser connects a wallet and submits transaction or file metadata.
2. Django validates and stores application state through REST endpoints.
3. Web3 components interact with Ethereum-compatible wallets and transaction hashes.
4. Files are uploaded to IPFS and referenced by immutable content identifiers.

## Technology

Python, Django, Django REST Framework, web3.py, Web3Auth, JavaScript, MetaMask, Bitcoin, Ethereum, IPFS, PostgreSQL, Docker.

## Engineering focus

- Connecting conventional web backends with decentralized infrastructure
- Designing data models around transaction hashes and content identifiers
- Separating on-chain references from off-chain application state
- Exploring verification, immutability, and censorship-resistant publishing

## Project status

This repository is a public portfolio case study. The historical prototype source remains private because it targets legacy dependencies and requires security modernization before reuse.

## Key takeaway

The project gave me hands-on experience integrating Django applications with wallets, blockchain transactions, and decentralized storage while documenting the security and architecture trade-offs of Web3 systems.
