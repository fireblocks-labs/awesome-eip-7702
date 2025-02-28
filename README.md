# Awesome EIP-7702 [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](https://makeapullrequest.com)

**A curated list of content related to EIP-7702 account abstraction for Ethereum and EVM Blockcahins - standards, guides, tools and more.**

## Standards
### Core EIP
- [EIP-7702: Set EOA account code](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-7702.md)
- [EIP-7702: Set EOA account code - Ethereum Magicians Thread](https://ethereum-magicians.org/t/eip-7702-set-eoa-account-code/19923)

### Related suggested EIPs/RIPs (not live/final)
- [EIP-7851: Deactivate/Reactivate a Delegated EOA's Key](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-7851.md)
- [ERC-7779: Interoperable Delegated Accounts](https://eips.ethereum.org/EIPS/eip-7779)
- [ERC-7821: Minimal Batch Executor Interface](https://eips.ethereum.org/EIPS/eip-7821)

## Guides
- [Safe: EIP-7702 A Win for Smart Accounts in Ethereum’s Pectra Upgrade?](https://safe.global/blog/eip-7702-smart-accounts-ethereum-pectra-upgrade) - An overview of how EIP-7702 powers more flexible and secure smart accounts through the Ethereum PECTRA upgrade.
- [ZeroDev: What does EIP-7702 mean for YOU? Part 1](https://docs.zerodev.app/blog/7702-adoption) - A concise guide to the growing adoption of EIP-7702 and its impact on the future of account abstraction.
- [Alchemy: EIP-7702 and How You Should Prepare for the Pectra Hardfork](https://www.alchemy.com/blog/eip-7702-ethereum-pectra-hardfork?utm_source=what_is_7702) - Consideration towards choosing tech stack with 7702 and 4337 as options.
- [Alchemy: What EIP-7702 Means for MetaMask and Other Wallets](https://www.alchemy.com/blog/eip-7702-metamask-and-wallets) - A look at how EIP-7702 changes the landscape for MetaMask and other wallets by introducing smart account capabilities.
- [Rhinestone: Getting Smart Accounts EIP-7702 Ready](https://blog.rhinestone.wtf/getting-smart-accounts-eip-7702-ready-27bf028a21c9) - Practical insights on preparing smart account implementations for EIP-7702 compatibility.
- [Rhinestone: Using EIP-7702 with ERC-7579 modular smart accounts](https://docs.rhinestone.wtf/module-sdk/account-guides/eip-7702) - A walkthrough of implementing EIP-7702 in code
- [EIP-7702: A Deep Dive into Smart EOAs with Implementation Examples
 by Colin](https://hackmd.io/@colinlyguo/SyAZWMmr1x) - A technical deep dive into the technical considerations and potential use cases around EIP-7702.
- [Tenderly: EIP-7702 How Ethereum’s New Upgrade Brings EOAs Closer to Smart Contracts](https://blog.tenderly.co/how-eip-7702-gives-eoas-smart-contract-functionalities/) - A detailed exploration of how EIP-7702 bridges the gap between externally owned accounts and smart contracts.
- [Ambire: EIP-7702 Opening the Door to Account Abstraction](https://blog.ambire.com/eip-7702-allowing-account-abstraction/) - EIP-7702 and its practical implications for account abstraction adoption
- [Sending gaslsss transactions from an EOA with EIP7702](https://raylac.notion.site/eoa-gasless-transactions) - Looking into the nuances of combining 7702 and 4337 for gasless transactions
- [QuickNode: EIP-7702 Implementation Guide: Build and Test Smart Accounts](https://www.quicknode.com/guides/ethereum-development/smart-contracts/eip-7702-smart-accounts) - A practical tutorial explaining EIP-7702, its benefits, and how to implement it using smart contracts. Includes code examples and deployment instructions.


## Videos

- [EIP-7702: a technical deep dive by lightclient | Devcon SEA](https://www.youtube.com/watch?v=_k5fKlKBWV4)
- [Age of Account Collaboration: EOA and SCA make friends again by Arik Galansky | EthCC[8] ](https://ethcc.io/archives/age-of-account-collaboration-eoa-and-sca-make-friends-again)
- [EIP 7702: High level overview + walkthrough of every line of code in the evm (using revm codebase) that changes with it](https://youtube.com/playlist?list=PLYYidDLT5Dd-7s3rbuAy3vJxAjz17bSEE&si=7RGnFDoBQ57i5yII)
- [Cantina TV: How EIP-7702 Changes Everything](https://x.com/i/broadcasts/1djGXVBvdvVxZ) - lightclient (Geth & EIP co-author), Tony & Hari (Cantina), Adam & Usman (Alchemy) Terence (Offchain Labs), Mark (OP Labs)


## Code
> [!CAUTION]
> All of this repo contributors and authors do not take responsbility for any of the code examples in here.
> Many of them are not audited and should not be used in production code.
> This is for educational and inspirational purposes only!

### EIP-7702 Proxies
- https://github.com/Vectorized/solady/blob/main/src/accounts/EIP7702Proxy.sol
- https://github.com/base/eip-7702-proxy
- https://github.com/openfort-xyz/openfort-contracts/blob/feat/eip-7702/contracts/core/upgradeable/UpgradeableOpenfortProxy7702.sol

### Wallets
- [Ambire Wallet](https://www.ambire.com/); a browser extension that supports (smarter) EOAs and Smart Accounts in one place

### POCs & Demos
- Ithaca Demos:
  - [EXP-0001: Account Delegation with EIP-7702](https://www.ithaca.xyz/updates/exp-0001)
  - [EXP-0002: App Sessions](https://www.ithaca.xyz/updates/exp-0002)
  - [EXP-0003: Application Subscriptions](https://www.ithaca.xyz/updates/exp-0003)
- [Rhinestone Demo](https://module-demos.rhinestone.wtf/eip-7702)

### Tooling support
- [Viem Experimental EIP-7702 Support](https://viem.sh/experimental/eip7702)
- [Foundry Delegation Signatures](https://book.getfoundry.sh/cheatcodes/sign-delegation)
- [Micro Eth Signer](https://github.com/paulmillr/micro-eth-signer)
- [Dynamic EIP-7702 support](https://docs.dynamic.xyz/smart-wallets/smart-wallet-providers/7702#eip-7702)
- [ZeroDev EIP-7702 support](https://docs.zerodev.app/sdk/getting-started/quickstart-7702)

### Smart account frameworks
- Metamask: Delegation Framework - [Delegation Framework 7702 Code](https://github.com/MetaMask/delegation-framework/tree/main/src/EIP7702) / [Delegation Framework 7702 Doc](https://github.com/MetaMask/delegation-framework/blob/main/documents/EIP7702DeleGator.md)

## Other
- [Awesome account abstraction repo (EIP-4337)](https://github.com/4337Mafia/awesome-account-abstraction)
- [eip7702.io](https://eip7702.io)
- [Modular Smart Account Changes](https://github.com/erc7579/erc7579-implementation/pull/38)
