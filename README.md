# psy-genesis

Shared genesis configuration and contract artifacts for PsyProtocol projects.

## Contents

- `config.json` — Canonical network configuration (localhost, sepolia, ethereum, bsc)
- `genesis_contracts.json` — Zstd-compressed pre-deployed genesis contract definitions
  (`9,409,903` bytes)
- `genesis_abi/` — Canonical sidecar ABIs and `abi_list.json` for the six
  predeployed contracts

## Usage

This repo is intended to be consumed as a git submodule:

```bash
git submodule add git@github.com:PsyProtocol/psy-genesis.git
```

Referenced by: [psy-node](https://github.com/PsyProtocol/psy-node), [psy-wallet](https://github.com/PsyProtocol/psy-wallet), [psy-sdk](https://github.com/PsyProtocol/psy-sdk)
