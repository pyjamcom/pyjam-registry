# Stage 2 – PJM Supply Increase (Draft)

- Mint amount: **100,000,000 PJM**
- Recipient: **5PZkTJvWotsmmBS2NNkZG3fwCVTHTweBhbmgcW1Fp6V8** (treasury/rewards wallet; mint to its PJM ATA)
- Additional USDC liquidity: **0** (USDC cap already used in Stage 1)
- Triggers: DAU ≥ 50,000 OR daily DEX volume ≥ $50,000; LP share ≥1% of circulating PJM; price drawdown <20% vs pre-stage; circulation cap before execution ≤60M PJM. *Override allowed by owner: tokens remain non-circulating on treasury until further decision.*
- Execution: Anchor/DAO proposal; multisig 3/5 (or DAO majority); log all tx hashes in Reports/full_history.md and registry.
- Post-mint: monitor LP share; rebalance CLMM if needed; keep emissions paced to maintain LP ≥1% circ. No timelock/vesting is applied if override is used; state this publicly.
- References: see `docs/proposals/stage2-anchor-proposal.json` in main repo for parameter template.
