# WBTC/BANKC — Why Bank Crypto Pairs with Wrapped Bitcoin

## Overview

Bank Crypto (BANKC) is adding a **WBTC/BANKC liquidity pool** on Uniswap V3. This creates a direct on-chain path between Bitcoin holders and the BANKC ecosystem.

## Why WBTC/BANKC?

The Vault by Bank Crypto issues **BTC Allocation NFTs** — each representing real Bitcoin held in institutional cold storage. A native WBTC/BANKC pool means:

1. **Direct swaps** — BTC holders can enter BANKC without routing through ETH or stablecoins
2. **Lower slippage** — Single-hop trades instead of multi-hop (WBTC → WETH → BANKC)
3. **Narrative alignment** — Bank Crypto is a Bitcoin custody product; WBTC is tokenized Bitcoin
4. **Aggregator routing** — 1inch, 0x, KyberSwap will pick up the direct path

## How It Works

```
Bitcoin holder wants BANKC:
  Old route: WBTC → WETH → BANKC (2 hops, 2x fees, 2x slippage)
  New route: WBTC → BANKC (1 hop, 1x fee, minimal slippage)
```

## Pool Details (Planned)

| Parameter | Value |
|-----------|-------|
| Pair | WBTC/BANKC |
| DEX | Uniswap V3 |
| Fee tier | 0.3% |
| Chain | Ethereum mainnet |
| Status | Coming soon |

## Related

- [Bank Crypto Website](https://bankcrypto.com)
- [The Vault — BTC Allocation NFTs](https://bankcrypto.com/vault)
- [BANKC Token](https://bankcrypto.com/token)
- [Current pools (BANKC/WETH, BANKC/USDC)](https://github.com/BotMakesCrypto/bank-crypto#liquidity-pools)
