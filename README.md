# Pyjam Registry (Solana)

Официальный открытый реестр адресов и метаданных токена **Pyjam (PJM)**.

## Core
- Mint: `5zUk2q8eHSGG5HeVkCVwjApT8FNyWFNyf8YyTocP916r`
- Decimals: 6
- Metadata URI: `https://pyjam.com/token_metadata_template.json`
- Metadata update authority: revoked (immutable)
- Mint authority: revoked (tx `3G4D6g8CWjd6wrb97HzPd1zDjXkNQaeHf6C8ekGvU9VePDXFr7ErxSrvcHSvthcQ9dpXU4L8cgiHAJ7m1YR1GQfK`)
- Freeze authority: none
- Total supply: 500,000,000 PJM (fixed)

## Liquidity
- Raydium CLMM PJM/USDC AmmID: `2htoaoFQms5SDK1iMjcr38K4h99f4dWxSwu8cGqKgKNN`
- LP holder multisig (Squads Safe): `FJ9kR8S86z4anTjqDwkVRFGbsdBnCcrNCtw1up2osGnm`
- LP mints: `Do3Tg8J5hnoQCbuXufuzDmvd3Ckm3bJw6R79R3sw4XAs`, `82k5cM8z46J9CNtC5whHt7i9wGPrNsVpmYozZNn3eTfp`, `3mbu5PvBVVSpCxJDFZoaw3LSymh9STAP3TeahN42YsUP`
- Stage 1 lock proof (Jupiter Lock, 18m): `proposals/Stage1/lock.md` — escrow `atyrJ9R6hkEFV4TK38ABdM8usaXhbHMZbPREtYsSUQo`, tx `2ZzZZRDfayEcizRyKFdaUQAS6Moj1o9pZ7uJ2DL5FzveTQy4PbeWkPCPeHP6rhCXEd2ASQbzyYX5xuQsuRmsG2XT`, unlock 02 Jun 2027 12:12 UTC.
- Stage 2–4 overrides: owner-held PJM (tx см. owner_holdings в transparency).

## Treasury & Vault
- Payer/Treasury: `9FG74JmFc1vpBsostRaNwTrZfJDrMtC1twfoJ7e1HgDx`
- Treasury secondary: `5PZkTJvWotsmmBS2NNkZG3fwCVTHTweBhbmgcW1Fp6V8`
- Vault PDA: `CnqTkJfYPErHb6XhnKQ53eNg5fFYLXtJxBNb6uZzNGJX`
- Vault ATA (PJM): `2ruNJ9hQndbhMCikHefbSw34mFA3VgGTKpYC8f7FjvXM`

## Oracle
- Oracle pubkey: `4joodcGemJ4bMu8GeCNidzrec3yvYngVUUkgMjFpkffJ`

## Useful links
- Transparency JSON: `https://pyjam.com/pyjam-transparency.json`
- Token metadata JSON: `https://pyjam.com/token_metadata_template.json`
- Swap (Jupiter): https://jup.ag/swap/USDC-PJM?inputMint=EPjFWdd5AufqSSqeM2qN1xzybapC8G4wEGGkZwyTDt1v&outputMint=5zUk2q8eHSGG5HeVkCVwjApT8FNyWFNyf8YyTocP916r
- Dexscreener: https://dexscreener.com/solana/2htoaofqms5sdk1imjcr38k4h99f4dwxswu8cgqkgknn
- Solscan: https://solscan.io/token/5zUk2q8eHSGG5HeVkCVwjApT8FNyWFNyf8YyTocP916r
- Website: https://pyjam.com
- Logo: https://pyjam.com/assets/favicon.png

## Jupiter Verified (fields)
- Name: Pyjam
- Symbol: PJM
- Mint: 5zUk2q8eHSGG5HeVkCVwjApT8FNyWFNyf8YyTocP916r
- Decimals: 6
- Logo: https://pyjam.com/assets/favicon.png (PNG <1MB)
- Website: https://pyjam.com
- Description: Pyjam (PJM) is the utility token of the community-owned Pyjam streaming & freelance app. Earn PJM for live streams, viewer engagement, tips, and gigs; spend it on boosts and donations, or swap via on/off-ramps and DEXs. PJM underpins access to premium features and future community governance.
- Socials: Telegram https://t.me/pyjamcom, Twitter https://twitter.com/pyjamcom
- Contact email: <your-email@pyjam.com>

## Files
- `pyjam-transparency.json` — полный список адресов/ссылок (включая owner_holdings overrides).
- `token_metadata_template.json` — актуальный metadata JSON для on-chain URI.

## Notes
- Metadata immutable; mint authority revoked; freeze authority none; supply fixed at 500M PJM.
- LP удерживаются мультисигом; адрес Safe указан выше.
