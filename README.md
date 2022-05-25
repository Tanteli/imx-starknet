# Immutable X StarkNet Contracts

<p align="center"><img src="https://cdn.dribbble.com/users/1299339/screenshots/7133657/media/837237d447d36581ebd59ec36d30daea.gif" width="280"/></p>

Immutable X is the first liquidity protocol for NFTs on Layer 2. The platform is built on StarkWare's [StarkEx](https://starkware.co/starkex/), a layer 2 scalability engine, leveraging zero-knowledge STARK technology to achieve significant scalability on top of Ethereum without compromising on security.

With the launch of [StarkNet](https://starkware.co/starknet/), StarkWare's permissionless, decentralized, layer 2 ZK-Rollup, Immutable X is adopting a multi-settlement strategy starting with StarkEx and StarkNet. As part of Phase 1 of our rollout plan, we are releasing a set of contracts with the core NFT primitives necessary to launch a project on StarkNet, which projects can permissionlessly build on. Find out more in our [StarkNet strategy blog post](\<TODO: insert link to blog post>).

In this repository, you will find Cairo implementations of:

- ERC20
- ERC721
- Metadata standards
- Royalties
- Payment Splitter
- Asset Bridging (L1 ↔︎ L2) (coming soon)

These contracts were designed to be feature-rich recommended standards on StarkNet, generalizable for current and future partner use cases as well as the wider ecosystem. This helps advance the necessary StarkNet primitives for Immutable X's StarkNet strategy and provides easy onboarding with out-of-the-box Cairo contracts to help developers build on StarkNet.

## Setup

### StarkNet:

See [starknet/README.md](starknet/README.md) for an in-depth setup guide for a Cairo development environment.

The StarkNet package includes all Cairo contracts for the above implementations. It uses some community-developed tools for Javascript/Typescript development on StarkNet:

- [`@shardlabs/starknet-hardhat-plugin`](https://github.com/Shard-Labs/starknet-hardhat-plugin)
- [`@shardlabs/starknet-devnet`](https://github.com/Shard-Labs/starknet-devnet)
- [`starknet.js`](https://github.com/0xs34n/starknet.js)

### Ethereum:

See [ethereum/README.md](ethereum/README.md) for an in-depth setup guide for a Solidity development environment.

The Ethereum package includes the Solidity contracts required for the L1 Ethereum side of the asset bridging primitive. It was bootstrapped using [hardhat](https://hardhat.org/getting-started/).

## Contribution

We aim to build robust and feature-rich standards to help all developers onboard and build their projects on StarkNet, and we welcome any and all feedback and contributions to this repository! See our [contribution guideline](CONTRIBUTING.md) for more details on opening Github issues, pull requests, reporting security issues, requesting features, and providing general feedback.

## Disclaimers

These Cairo contracts are in a very experimental stage and are subject to change without notice. The code has not yet been formally audited or reviewed and may have security vulnerabilities. Do not use in production.

## License

Immutable X StarkNet contracts are released under the Apache-2.0 license. See [LICENSE.md](LICENSE.md) for more details.

## Links

### Socials

- [Twitter](https://twitter.com/Immutable)
- [Discord](https://discord.gg/6GjgPkp464)
- [Telegram](https://t.me/immutablex)
- [Reddit](https://www.reddit.com/r/ImmutableX/)

### We’re hiring! [Apply now](bit.ly/1MTBL)