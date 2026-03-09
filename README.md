# AsterSwap V2 Core

**Original, unmodified** Uniswap V2 Core contracts for AsterSwap on Aster L1.

> ⚠️ Contract code is preserved exactly as audited. Do not modify `contracts/`.

## Contracts

| Contract | Solidity | Description |
|---|---|---|
| `UniswapV2Factory` | 0.5.16 | Deploys pairs via CREATE2 |
| `UniswapV2Pair` | 0.5.16 | AMM pair — swap, mint, burn, skim, sync |
| `UniswapV2ERC20` | 0.5.16 | LP token (ERC20 + EIP-2612 permit) |

## Running Tests (Docker)

The original toolchain (`ethereum-waffle`) requires **Node 12 + Python 3.7**.
Docker handles this automatically.

```bash
# Run tests
docker compose run --rm test

# Compile only
docker compose run --rm compile
```

## Source

Fork of [Uniswap/v2-core](https://github.com/Uniswap/v2-core).
