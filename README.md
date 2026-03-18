# Torrino Vote Verifier

Simple web tool to independently verify DAO votes using Solana wallet signatures.

Users can input:
- Wallet address
- Signed message
- Signature

The verification happens entirely in the browser using cryptographic checks (no backend, no data collection).

## Features

- Trustless verification
- No server required
- Fully client-side
- Compatible with Torrino DAO voting system

## How it works

Each vote is signed by a wallet.  
This tool verifies that the signature matches the wallet and the message, ensuring the vote is authentic and unmodified.

## Disclaimer

This tool only verifies cryptographic signatures.  
It does not validate NFT ownership, voting rules, or proposal state.

---

Centralized UX, decentralized trust.
