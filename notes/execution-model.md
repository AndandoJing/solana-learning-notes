# Solana Execution Model — Notes

- Transactions define instructions and account access upfront.
- Parallel execution depends on non-overlapping account writes.
- Compute limits influence program and system design.

## Implications
- Execution constraints must be considered at design time.
- Off-chain coordination is often required for complex workflows.
