# Solana Account Model — Quick Notes

- Accounts store state; programs are stateless logic.
- Instructions read/write accounts passed in the transaction.
- Execution is constrained by compute limits and account access rules.

## Why this matters for system design
- You must design workflows around what needs to be stored on-chain vs off-chain.
- Account structure impacts performance, cost, and UX.
