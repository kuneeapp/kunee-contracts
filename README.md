# KUNEE Contracts

This repository is a **sample-only documentation project** for KUNEE contracts. It contains documentation only, not contract source code, application code, or a deployable package. Addresses recorded in the deployment notes are for an operator-controlled rehearsal and must not be mistaken for a public release.

## Important status

The Robinhood Chain rehearsal used chain ID `4663`. The rehearsal pool is operator-only: **only its deployer can call `Shield`**. Its denomination is exactly `294805000000000` wei (`0.000294805 ETH`); this is a test denomination and **is not the intended final denomination of `0.001 ETH`**. Public release is not authorized by this record.

The KUNEE browser lab uses ephemeral chain ID `31337` and has **no public mainnet access**. It is separate from the operator-only chain rehearsal. Do not use either statement as a public-funds instruction.

See [DEPLOYMENTS.md](DEPLOYMENTS.md) for the rehearsal addresses, transaction links, internal release-record basis, and verification caveat.

## Contents

- [Contributing](CONTRIBUTING.md) — scope and contribution practices
- [Security](SECURITY.md) — safe reporting and handling guidance
- [Changelog](CHANGELOG.md) — documentation history and planned preview
- [Deployments](DEPLOYMENTS.md) — operator-only rehearsal record and verification limits
- [Local test guide](LOCAL_TEST.md) — conceptual, local-only chain `31337` walkthrough

## Project links

- [KUNEE](https://github.com/kuneeapp/kunee)
- [KUNEE Wallet Examples](https://github.com/kuneeapp/kunee-wallet-examples)
- [KUNEE Security](https://github.com/kuneeapp/kunee-security)
- [KUNEE Privacy Lab](https://github.com/kuneeapp/kunee-privacy-lab)
- [KUNEE Contracts](https://github.com/kuneeapp/kunee-contracts)

Questions about this sample repository: [support@kunee.app](mailto:support@kunee.app).

## Open-source scope

The material **in this repository** is available under the [MIT License](./LICENSE). Contributions to this repository are licensed the same way. The KUNEE application, unreleased contract source code, private infrastructure, and material outside this repository are **not** included. The license grants no rights to the KUNEE name or logos as trademarks and does not authorize use of any live service or operator-only contract. Licensing these notes does not verify that any deployed bytecode matches source code.

[Licensed documentation preview](https://github.com/kuneeapp/kunee-contracts/releases/tag/v0.1.1-preview) · Not a production software release.