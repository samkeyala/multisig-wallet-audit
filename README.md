# 🔐 MultiSig Wallet - Smart Contract Audit

This repository contains the audit of a `MultiSigWallet` smart contract written in Solidity. It allows multiple owners to manage and approve transactions before execution, ensuring secure fund management in decentralized environments.

## 📜 Contract Summary

- **Contract Name**: `MultiSigWallet`
- **Language**: Solidity ^0.8.0
- **Features**:
  - Multiple owners
  - Submit, confirm, revoke, and execute transactions
  - Minimum confirmation threshold (`required`)
  - On-chain transaction data storage
  - Event logging for all key actions

## 🧠 Audit Overview

The contract was manually reviewed and tested using security analysis tools like **Slither** and **Mythril**. The audit focused on:

- Access control
- Replay protection
- Transaction logic flow
- Reentrancy and external call safety
- Gas optimizations

## 🧪 Tools Used

- [Slither](https://github.com/crytic/slither)
- [Mythril](https://github.com/ConsenSys/mythril)
- Manual review

