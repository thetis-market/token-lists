# Thetis Market - Revolutionizing DeFi on Aptos
Thetis is a cutting-edge decentralized finance (DeFi) platform designed to provide a seamless, efficient, and user-friendly trading experience on the Aptos blockchain. As a comprehensive DeFi solution, Thetis combines three powerful features: a DEX Aggregator, Perpetual Trading DEX, and Liquidity Bootstrapping Pools (LBPs).

# Our Vision
Thetis aims to revolutionize the DeFi landscape by offering innovative trading solutions that rival centralized exchanges (CEXs) while maintaining the core principles of decentralization. Our mission is to empower users with advanced trading tools, enhanced liquidity options, and a secure trading environment.

# Key Features
Thetis aims to revolutionize the DeFi landscape by offering innovative trading solutions that rival centralized exchanges (CEXs) while maintaining the core principles of decentralization. Our mission is to empower users with advanced trading tools, enhanced liquidity options, and a secure trading environment.
- **DEX Aggregator**: Thetis's optimized aggregation algorithm finds the most optimal paths to deep liquidity pools across DeFi protocols. This ensures the best trade execution, minimizing slippage, and maximizing price efficiency for users.
- **Perpetual Trading DEX**: Unlike traditional perpetual trading platforms that use synthetic models, Thetis allows for unlimited profit per trade without auto-closing positions. Our isolated liquidity pool model enables easy addition of new tokens and supports advanced trading features.
- **Liquidity Bootstrapping Pools (LBPs)**: Inspired by Fjord, Thetis offers a unique feature for new projects to launch fairly. LBPs facilitate fair token distribution, efficient capital raising, and customizable parameters for token issuers.

# Token List
Thetis Token Lists is a specification for lists of token metadata (e.g. address, decimals, ...) that can be used by any dApp interfaces that needs one or more lists of tokens.

Anyone can create and maintain a token list, as long as they follow the specification.

# Open a PR to add your token

## 1. Fork the Repository

Fork the [token-lists](https://github.com/thetis-market/token-lists) repository on GitHub to create your own copy.

## 2. Add Token Icon

Add the symbol.png file for the token in the logos folder in your forked repository. Ensure it's no larger than 256x256 pixels.

## 3. Update `tokenlist.json`

Provide the following details:

- `name`: The name of the token.
- `symbol`: The symbol registered by the token minter on-chain
- `address`: The complete address used to identify the token as per the Aptos core framework
- `decimals`: The number of decimal places for the token
- `logoURI`: The URL for the token's logo (the logo should be added to the logos folder in your repository to get the correct link)

Example:

```typescript
  {
      "name": "Aptos Coin",
      "symbol": "APT",
      "decimals": 8,
      "address": "0x1::aptos_coin::AptosCoin",
      "logoURI": "https://raw.githubusercontent.com/thetis-market/token-lists/main/logos/APT.png"
    }
```


## 4. Commit Changes

Commit your changes with a descriptive message explaining the modifications made.

## 5. Make a Pull Request

Navigate to your forked repository, open a pull request, and submit it for review.


# Have more questions?
Come visit us on discord at our partnership channel. Link: https://discord.com/invite/ErPXJyKmXC