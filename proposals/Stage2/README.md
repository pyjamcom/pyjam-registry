# Stage 2 – PJM Supply Increase (Completed via owner override)

- Mint amount: **100,000,000 PJM**
- Recipient: **5PZkTJvWotsmmBS2NNkZG3fwCVTHTweBhbmgcW1Fp6V8** (treasury/rewards wallet; ATA `33sbQjKT1CHS1YG6cWsDjo595W3iCXeXk9oBqjY4t74X`)
- Tx mint: `4982FSw5iBYF6CeVhjF3i8DByqB3cYhkiB2YFEXK4Jt5H5xLxNQ4HqAgvmMPQAdExiDJgj11dUK2xHovhNtG9fZ`
- Additional USDC liquidity: **0** (USDC cap already used in Stage 1)
- Triggers: owner override of volume/DAU; tokens under sole owner control (no timelock/vesting), free to circulate at owner discretion.
- Circulation cap policy kept: Stage2 ≤60M; LP ≥1% circ; price drawdown <20% before advancing to next stage.
- Execution: mint signed by mint authority (7a81UVC…); no new LP actions.
- Post-mint: monitor LP share; rebalance CLMM if needed; any release of these tokens should be publicly announced.
