# psy-genesis

Shared genesis configuration and contract artifacts for PsyProtocol projects.

## Contents

- `config.json` — Canonical network configuration (localhost, sepolia, ethereum, bsc)
- `genesis_contracts.json` — Pre-deployed genesis contract definitions (~24MB)

## Usage

This repo is intended to be consumed as a git submodule:

```bash
git submodule add git@github.com:PsyProtocol/psy-genesis.git
```

Referenced by: [psy-node](https://github.com/PsyProtocol/psy-node), [psy-wallet](https://github.com/PsyProtocol/psy-wallet), [psy-sdk](https://github.com/PsyProtocol/psy-sdk)
