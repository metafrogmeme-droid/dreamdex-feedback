# dreamDEX feedback (RUNECLAW)

Feedback-track submission for the [dreamDEX Perps Builder Bounty](https://dorahacks.io/hackathon/dreamdex-perps-bounty/detail).

Found on Somnia Tokyo testnet while building Claw Guard Perps, an operator-key firewall for AI perps agents
(by [@RUNECLAW_AI](https://x.com/RUNECLAW_AI)). One reproducible item per file in [`feedback/`](feedback/),
in the bounty template.

| Issue | Severity | Area |
| --- | --- | --- |
| [Docs say any address can claim paper USDso, but claim() reverts SelfClaimDisabled](feedback/voucher-docs-any-address-can-claim.md) | major | docs |
| [getPerpVoucherEligibility returns eligible: true while every claim reverts](feedback/sdk-voucher-eligibility-ignores-self-claim.md) | major | SDK |
| [SDK error ABI has no SelfClaimDisabled](feedback/sdk-error-abi-missing-self-claim-disabled.md) | normal | SDK |
| [SignerRequiredError hint: an account address still fails](feedback/sdk-signer-required-account-hint.md) | normal | SDK |

Environment: `@somnia-chain/markets-sdk` 0.32.1, Somnia Tokyo testnet (chain 50383), 1 Nov 2026.

MIT licensed.
