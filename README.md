# KAKROSE-BOT

Automation bot for Pharos testnet (chain ID 688688): runs tasks across AquaFlux mint, PrimusLab, FaroSwap, auto-staking, OpenFi, CFD trading, and status checks - with a CLI table summary of results.

## Requirements

- Node.js v18 or above
- A Pharos testnet wallet funded with testnet tokens

## Install

```bash
npm install
```

## Configure

Create `wallets.txt` in the project root with one wallet private key per line. The bot reads each key and runs the configured tasks for that wallet.

## Run

```bash
node main.js
```

Follow the on-screen prompts to pick which task to run.

## Security warning

`wallets.txt` contains full control over your wallets. Never share it, never commit it to a public repository, and only use testnet wallets with no real funds for automation like this.
