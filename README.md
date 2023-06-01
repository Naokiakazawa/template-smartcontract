# Template for Solidity dev environment

## setup:

```shell
yarn
forge install
git checkout -b develop
```

Create `.env` and set environment variables

```
INFURA_KEY=
MNEMONIC=
PRIVATE_KEY=
ETHERSCAN_KEY=
```

## Test

```shell
yarn test
```

```shell
forge test
```

## Build

```shell
forge build
```

---

## Before setup

This template includes Foundry.

To install Foundry
```
curl -L https://foundry.paradigm.xyz | bash
foundryup
```

To update Foundry
```
foundryup
```