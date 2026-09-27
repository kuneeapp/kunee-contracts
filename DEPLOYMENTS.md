# KUNEE Contracts: deployment record

## Status and limitations

The entries below document an **operator-only rehearsal**, not a public release. The recorded network is Robinhood Chain mainnet, chain ID `4663`; its use here does not authorize public deposits or establish production readiness. The test pool allows **only its deployer to call `Shield`**.

The pool's immutable rehearsal denomination is **`294805000000000` wei (`0.000294805 ETH`)**. This is a test value and **is not the intended final denomination of `0.001 ETH`**. Final public-release addresses are not identified by this rehearsal record.

The browser lab is separate: it uses ephemeral local chain ID `31337` and has **no public mainnet access**.

## Record basis

The values on this page were transcribed from KUNEE's internal release record. The relevant chain receipts were independently checked. The internal record is not linked here; this page is a concise record of the rehearsal and its limits.

## Rehearsal contracts

Explorer links use Robinhood Chain Blockscout. They identify on-chain addresses and transactions only; **they do not imply that source code is verified on the explorer, independently audited, or approved for public use**.

| Component | Address | Deployment transaction |
|---|---|---|
| Poseidon(2) hasher | [`0xA8Ed92f55c589eae5863641Cc41c3EAd4341A8B6`](https://robinhoodchain.blockscout.com/address/0xA8Ed92f55c589eae5863641Cc41c3EAd4341A8B6) | [`0x8e5aeb72a535f43c82e095ccc74e8287dfa81037ac53d39bbe1f7dabfc81f5d8`](https://robinhoodchain.blockscout.com/tx/0x8e5aeb72a535f43c82e095ccc74e8287dfa81037ac53d39bbe1f7dabfc81f5d8) |
| Candidate verifier | [`0xcb8d04C884c640C8b954446afd9932b76Bb63A53`](https://robinhoodchain.blockscout.com/address/0xcb8d04C884c640C8b954446afd9932b76Bb63A53) | [`0xe8e197d9fe21e81baa9578dd0b20595b3c5dee964030696e0740e81b2f3f15a5`](https://robinhoodchain.blockscout.com/tx/0xe8e197d9fe21e81baa9578dd0b20595b3c5dee964030696e0740e81b2f3f15a5) |
| **Operator-only test pool** | [`0xc4fE4bf7dC498B3480969EEdDb9D21bAdE742EaE`](https://robinhoodchain.blockscout.com/address/0xc4fE4bf7dC498B3480969EEdDb9D21bAdE742EaE) | [`0xe56d2caaae5ea2453810ec50b66c6fef6280708e57635b66f212d726efbb2daa`](https://robinhoodchain.blockscout.com/tx/0xe56d2caaae5ea2453810ec50b66c6fef6280708e57635b66f212d726efbb2daa) |

## Initial pool rehearsal transactions

The transactions below are for the **initial rehearsal flow only**. They are not a complete list of subsequent operator-only tests; additional rehearsal activity is described in the internal release record.

The internal release record reports successful receipts for an operator Shield and Unshield on the test pool. The pool was subsequently observed with zero wei and zero live notes.

| Action | Transaction |
|---|---|
| Shield | [`0xb3a17c68f61744b922b129bc203289e223655a5d0f619ffbb8bfe8d67c0ad46a`](https://robinhoodchain.blockscout.com/tx/0xb3a17c68f61744b922b129bc203289e223655a5d0f619ffbb8bfe8d67c0ad46a) |
| Unshield | [`0x84898fc87285dda7927fe482cb6cd3ca59b5479fb2791b8e8c9c7ba92042c408`](https://robinhoodchain.blockscout.com/tx/0x84898fc87285dda7927fe482cb6cd3ca59b5479fb2791b8e8c9c7ba92042c408) |

**Verification caveat:** Addresses and transaction hashes are transcribed from the internal release record, and the corresponding receipts were independently checked. This does not assert explorer-verified source, source-code correspondence, an independent source review, audit completion, or release approval. Independently confirm chain ID and transaction details before relying on them.