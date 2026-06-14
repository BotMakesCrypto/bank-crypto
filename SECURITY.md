# Security Policy

## Supported Versions

| Version | Supported          |
| ------- | ------------------ |
| 1.4.x   | :white_check_mark: |
| < 1.4   | :x:                |

## Smart Contract Security

### Contract Details

- **Address**: `0xa593decc9100f0014ff8ee07735f7b8eefb7e055`
- **Network**: Ethereum Mainnet
- **Standard**: ERC-20
- **Compiler**: Solidity 0.8.24
- **Verified**: Yes ([Etherscan](https://etherscan.io/token/0xa593decc9100f0014ff8ee07735f7b8eefb7e055))

### Protective Features

The contract includes standard DeFi protective mechanisms:

- **Anti-Bot**: Prevents automated sniping and MEV attacks
- **Anti-Whale**: Limits large single-transaction price manipulation
- **Blacklist**: Allows blocking known exploit/scam addresses
- **Pause**: Emergency stop function for critical situations

### Verification

Always verify you are trading the correct token:

1. Check [Etherscan](https://etherscan.io/token/0xa593decc9100f0014ff8ee07735f7b8eefb7e055) for verified source code
2. Confirm total supply is 25,000,000 BANKC
3. Verify active trading on [DEXScreener](https://dexscreener.com/ethereum/0xf0b694cfee0ab11f3d1497dae6e7ee9251b885d1)

## Reporting a Vulnerability

If you discover a security vulnerability, please report it via:

- GitHub Security Advisories
- Email: secure@bankcrypto.com

Please include:
- Description of the vulnerability
- Steps to reproduce
- Potential impact
- Suggested fix (if any)

We aim to respond to security reports within 48 hours.
