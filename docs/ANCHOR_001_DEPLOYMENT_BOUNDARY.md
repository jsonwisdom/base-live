# Anchor 001 — Deployment Boundary

## Current State

Anchor 001 is **not** deployed via `jsonwisdom/base-live`.

This repository is currently a reserved namespace for future Base L2 deployment artifacts.

## What Anchor 001 Uses

| Component | Location |
|---|---|
| Merkle pipeline | `jsonwisdom/Welcome-to-JSONWISDOM` |
| Git commit anchor | `13004719dd0c34f765ca95dfe8566b6feb2bf6cf` |
| Merkle Root (SHA-256) | `ff55160908ff41d23f7af0df8873ef7a0dcf8163d1a308f58941e87b5a95bad9` |
| Leaf Keccak-256 | `0xb7e55f9e1f4f27cd96f38d74e6510e184a14772ef3f9f628d5acc68531dd185d` |
| EAS on-chain attestation | Base, UID `0x18b5b00c62c648df2ccf4a746645493fa2a0b0dcda6697052d8c3a3d1586c142` |
| EAS schema | `0x3bab210b4da3faff084e146075caf9168efb5c9c87f18509bca2c07d7f2e49c` |
| ENS | `DEFERRED` |

## Future Deployments

When `RMPAnchor.sol` or other contracts are deployed to Base, their artifacts should be committed here with:

- contract source
- ABI
- deployed address
- deployment transaction hash
- chain/network identifier
- verification status
- signer and owner boundary notes

## Boundary Rule

Until those artifacts exist, this repository must not be treated as deployment truth.

No contract address, EAS schema reference, transaction hash, or ABI should be inferred from this repo.

Rule: no ghost deployment.
