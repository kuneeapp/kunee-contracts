# Local test guide

This conceptual checklist covers only an ephemeral local-chain lab session with chain ID `31337`. It includes no deployable contract code, deployment commands, or public-chain instructions.

## Local-only checks

1. Open the project's intended browser lab and confirm that its selected network is the ephemeral local chain, chain ID `31337`.
2. Confirm the configured RPC endpoint is local. Do not substitute a public RPC URL or a production network.
3. Use only fresh throwaway local test accounts and valueless local test assets. Do not import or connect an account holding real funds.
4. Exercise the lab's documented sample flow, observing expected local state changes and error handling.
5. Stop or reset the local session after testing. Discard its ephemeral state.

If the lab presents any other chain ID, a public endpoint, an unfamiliar wallet account, or a public transaction prompt, stop without approving it and report the issue to [support@kunee.app](mailto:support@kunee.app).

## Scope

This is not a guide to deploy or interact with the operator-only Robinhood Chain rehearsal contracts. The local browser lab has no public mainnet access. A successful local exercise does not demonstrate production behavior, public-chain compatibility, privacy between real users, or contract safety. Never add secrets, wallet private material, recovery phrases, private keys, or real user data to the test or its reports.