# Stage 2 – PJM Supply Increase (Completed via owner override)

- Mint amount: **100,000,000 PJM**
- Recipient (now allocated to multisigs; see transparency JSON): initial mint to treasury `5PZkTJvWotsmmBS2NNkZG3fwCVTHTweBhbmgcW1Fp6V8` (ATA `33sbQjKT1CHS1YG6cWsDjo595W3iCXeXk9oBqjY4t74X`), later redistributed:
  - Team 60M → multisig `4aFcoHku9LD1w5C5Pz7QfCevPWnamUva5Kxw4GJmsEGV`, ATA `GtzimNuWfc5oGvUzmK2vaP5FWHTjxQGDg5PcvaSQV4tv`, tx `4Ab1v37UA8jRQk2Dh4wPZqL24YXDzgJ5CDNiWv2ZVz197srDobkMYGnvP3uSP5vEvPoBVydJdxRMufoNArXQXAzt`
  - Community 140M → multisig `EVFn68Dr2oUihTVso8X93uCquB3G92RCdSCrsz3f6Nf6`, ATA `2pWcgvoBJUrXRpLN2YdTnFDGK5MbPwwHw2BC8paguVWQ`, tx `54fyoQBraD4gpJjPHnU6oS3tcyXxoD3BhLLnBUiAy2261nU6pCqLx7NHRFV88fYQzskNxD9vW8c8fXYRDMbg7znt`
  - Treasury/MM 60M → multisig `C5vkhSn3o2skMyc6wB1f74hgJEXdH8rD596G6c16MvQK`, ATA `BuCPcaXdK7RHsokGGacEwgob7sbpjh8c2BybrqhqG8bS`, tx `JEovVhSZoTdYiwsprn3rZFGRpk7v6VCuM5FCZo7TM9iPGMrYxy4goMDrn3NTieUuYVwGqhWnhDodvZ7t6MtMumv`
  - Reserve 160M → multisig `E9Xikh33mU4jPbrrGhjGzC3GLC6qtmRR7CUCS189RgWK`, ATA `6FTSvEmfGF9c4t7T5z2KDeA3D4CHycApirXABtiQUFMg`, tx `3J8ZMYLuvbaPrQd5BzPKTxEh3qFKBRJn4wVQH1BJ6mD1f1Eys3qBHTS3jLfPyXc2FGYBp3o3QZsw4vnh6RdFRjVb`
  - Owner buffer ~78.7M remains on treasury ATA `33sbQjKT1CHS1YG6cWsDjo595W3iCXeXk9oBqjY4t74X`
- Tx mint: `4982FSw5iBYF6CeVhjF3i8DByqB3cYhkiB2YFEXK4Jt5H5xLxNQ4HqAgvmMPQAdExiDJgj11dUK2xHovhNtG9fZ`
- Additional USDC liquidity: **0** (USDC cap already used in Stage 1)
- Triggers: owner override of volume/DAU; tokens under sole owner control (no timelock/vesting), free to circulate at owner discretion.
- Circulation cap policy kept: Stage2 ≤60M; LP ≥1% circ; price drawdown <20% before advancing to next stage.
- Execution: mint signed by mint authority (7a81UVC…); no new LP actions.
- Post-mint: monitor LP share; rebalance CLMM if needed; any release of these tokens should be publicly announced.
