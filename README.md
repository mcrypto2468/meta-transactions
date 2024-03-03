# Metatransactions and Signature Replay Fix

This repository contains contracts and tests for Using metatransaction to pay for your users' gas Lesson by **LearnWEB3**.

## Overview

The repository is structured as follows:

- `contracts/`: Contains the smart contract files.
  - `MetaTokenSender.sol`: Contract for Metatransactions.
  - `SignatureReplayFix.sol`: Contract with a fix for the Signature Replay vulnerability.
- `test/`: Contains the test files.
  - `metatxn-test.js`: Test file for `MetaTokenSender.sol`.
  - `signaturereplay-test.js`: Test file for `SignatureReplayFix.sol`.

## Getting Started

1. Clone the repository:

```bash
git clone https://github.com/mcrypto2468/meta-transactions
cd meta-transactions
```

2. Install dependencies:

```bash
pnpm install
```

3. Run tests:

```bash
npx hardhat test
```
