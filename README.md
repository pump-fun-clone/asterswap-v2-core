# AsterSwap V2 Core

**Original, unmodified** Uniswap V2 Core contracts for AsterSwap on Aster L1.

> ⚠️ Contract code is preserved exactly as audited. Do not modify `contracts/`.

## Contracts

| Contract | Solidity | Description |
|---|---|---|
| `UniswapV2Factory` | 0.5.16 | Deploys pairs via CREATE2 |
| `UniswapV2Pair` | 0.5.16 | AMM pair — swap, mint, burn, skim, sync |
| `UniswapV2ERC20` | 0.5.16 | LP token (ERC20 + EIP-2612 permit) |

## Dev Environment

Requires **Node 14** (uses `ethereum-waffle`). Newer Node versions are incompatible with native deps.

```bash
nvm use 14   # or: nvm install 14
yarn install
yarn compile
yarn test
```

## Source

Fork of [Uniswap/v2-core](https://github.com/Uniswap/v2-core).
