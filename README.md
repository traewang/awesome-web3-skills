# Awesome Web3 Skills [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of the most popular and useful Web3 development skills, tools, and resources.

## Contents

- [Getting Started](#getting-started)
- [Core Languages](#core-languages)
- [Smart Contract Development](#smart-contract-development)
- [Frontend & dApp Development](#frontend--dapp-development)
- [Wallet Integration](#wallet-integration)
- [Infrastructure](#infrastructure)
- [Security & Auditing](#security--auditing)
- [DeFi Development](#defi-development)
- [Zero-Knowledge Proofs](#zero-knowledge-proofs)
- [AI + Web3](#ai--web3)
- [Testing & Debugging](#testing--debugging)
- [Learning Resources](#learning-resources)
- [Job Boards](#job-boards)
- [Related Awesome Lists](#related-awesome-lists)

---

## Getting Started

- [Ethereum.org](https://ethereum.org/developers) - Official Ethereum developer documentation and tutorials.
- [CryptoZombies](https://cryptozombies.io/) - Interactive school for learning Solidity by building games.
- [Speedrun Ethereum](https://speedrunethereum.com/) - Hands-on challenges to learn Ethereum development step by step.
- [useWeb3](https://www.useweb3.xyz/) - Curated platform for learning Web3 development with tutorials, courses, and guides.
- [LearnWeb3](https://learnweb3.io/) - Free comprehensive Web3 developer education from beginner to expert.
- [Alchemy University](https://university.alchemy.com/) - Free Web3 development bootcamp covering Solidity, smart contracts, and dApps.
- [Web3 Developer Roadmap](https://github.com/ArnaudBand/web3_dev_roadmap) - Structured learning path from zero to Web3 developer.

## Core Languages

### Solidity

- [Solidity Documentation](https://docs.soliditylang.org/) - Official language reference for the most widely used smart contract language.
- [Solidity by Example](https://solidity-by-example.org/) - Learn Solidity through practical, annotated code examples.
- [OpenZeppelin Contracts](https://github.com/OpenZeppelin/openzeppelin-contracts) - Battle-tested library of secure, reusable smart contracts.

### Rust

- [The Rust Book](https://doc.rust-lang.org/book/) - Official Rust language guide, essential for Solana and Polkadot development.
- [Rust by Example](https://doc.rust-lang.org/rust-by-example/) - Learn Rust through runnable examples.
- [Solana Cookbook](https://solanacookbook.com/) - Practical references for building on Solana with Rust.

### Move

- [Move Language Documentation](https://move-language.github.io/move/) - Official docs for the resource-oriented language used by Aptos and Sui.
- [Aptos Developer Docs](https://aptos.dev/) - Getting started with Move on the Aptos blockchain.
- [Sui Move Documentation](https://docs.sui.io/build/move) - Learn Move for the Sui ecosystem.

### Cairo

- [The Cairo Book](https://book.cairo-lang.org/) - Comprehensive guide to Cairo, the language for Starknet zero-knowledge rollups.
- [Starklings](https://github.com/shramee/starklings-cairo1) - Interactive exercises for learning Cairo.

### Vyper

- [Vyper Documentation](https://docs.vyperlang.org/) - Official docs for the Pythonic smart contract language.
- [Vyper by Example](https://vyper-by-example.org/) - Learn Vyper through practical examples.

### TypeScript / JavaScript

- [TypeScript Handbook](https://www.typescriptlang.org/docs/handbook/) - Essential for Web3 frontend and tooling development.
- [Node.js](https://nodejs.org/) - Runtime environment powering most Web3 development toolchains.

## Smart Contract Development

### Frameworks

- [Hardhat](https://hardhat.org/) - The most popular Ethereum development environment with built-in testing, debugging, and deployment.
- [Foundry](https://github.com/foundry-rs/foundry) - Blazing-fast, Rust-based toolkit for Ethereum development with Forge, Cast, Anvil, and Chisel.
- [Anchor](https://www.anchor-lang.com/) - Framework for Solana program development, simplifying writing and testing on-chain programs.
- [Remix IDE](https://remix.ethereum.org/) - Browser-based IDE for writing, deploying, and testing Solidity contracts.
- [Thirdweb](https://thirdweb.com/) - Full-stack Web3 development platform with pre-built contracts and SDKs.

### Contract Libraries

- [OpenZeppelin Contracts](https://github.com/OpenZeppelin/openzeppelin-contracts) - Industry-standard library for secure smart contract development (ERC20, ERC721, access control, etc.).
- [Solmate](https://github.com/transmissions11/solmate) - Gas-optimized building blocks for smart contract development.
- [Solady](https://github.com/Vectorized/solady) - Highly optimized Solidity snippets focused on gas efficiency.

### Deployment & Verification

- [Hardhat Deploy](https://github.com/wighawag/hardhat-deploy) - Plugin for replicable and verified contract deployments.
- [Sourcify](https://sourcify.dev/) - Decentralized contract verification service.
- [Etherscan](https://etherscan.io/) - Block explorer with contract verification and interaction capabilities.

## Frontend & dApp Development

### Web3 Libraries

- [Ethers.js](https://docs.ethers.org/) - Complete, compact library for interacting with Ethereum.
- [Viem](https://viem.sh/) - Modern, type-safe TypeScript interface for Ethereum.
- [Web3.js](https://web3js.readthedocs.io/) - The original Ethereum JavaScript API.

### React Integration

- [Wagmi](https://wagmi.sh/) - React hooks for Ethereum, covering wallet connection, contract reads/writes, and more.
- [RainbowKit](https://www.rainbowkit.com/) - Beautiful, customizable wallet connection component for React.
- [ConnectKit](https://docs.family.co/connectkit) - Elegant wallet connection UI built on top of Wagmi.
- [Web3Modal](https://web3modal.com/) - WalletConnect's official multi-chain modal for connecting wallets.

### Frameworks

- [Scaffold-ETH 2](https://scaffoldeth.io/) - Open-source toolkit for rapid Ethereum dApp prototyping with Next.js, Hardhat, and Wagmi.
- [Create Web3 DApp](https://github.com/alchemyplatform/create-web3-dapp) - CLI to bootstrap full-stack Web3 applications quickly.

## Wallet Integration

- [MetaMask](https://metamask.io/) - The most widely used browser extension wallet for Ethereum and EVM chains.
- [WalletConnect](https://walletconnect.com/) - Open protocol for connecting wallets to dApps across mobile and desktop.
- [Coinbase Wallet SDK](https://docs.cloud.coinbase.com/wallet-sdk/) - SDK for integrating Coinbase Wallet into dApps.
- [Phantom](https://phantom.app/) - Leading wallet for Solana, also supporting Ethereum and Polygon.
- [Rabby Wallet](https://rabby.io/) - Open-source wallet focused on DeFi with pre-transaction risk scanning.

## Infrastructure

### RPC Providers & Nodes

- [Alchemy](https://www.alchemy.com/) - Leading Web3 development platform with enhanced APIs and node infrastructure.
- [Infura](https://www.infura.io/) - Ethereum and IPFS API suite by ConsenSys.
- [QuickNode](https://www.quicknode.com/) - Multi-chain node infrastructure with high performance.
- [Chainstack](https://chainstack.com/) - Managed blockchain services supporting 30+ protocols.
- [Ankr](https://www.ankr.com/) - Decentralized Web3 infrastructure with public and premium RPC endpoints.

### Decentralized Storage

- [IPFS](https://ipfs.tech/) - Peer-to-peer hypermedia protocol for decentralized file storage.
- [Pinata](https://www.pinata.cloud/) - IPFS pinning service optimized for NFTs and Web3 applications.
- [Arweave](https://www.arweave.org/) - Permanent, decentralized data storage through blockweaving.
- [Filecoin](https://filecoin.io/) - Decentralized storage network built on top of IPFS.

### Data Indexing & Querying

- [The Graph](https://thegraph.com/) - Indexing protocol for querying blockchain data with GraphQL.
- [Goldsky](https://goldsky.com/) - Real-time blockchain data infrastructure for indexing and streaming.
- [Envio](https://envio.dev/) - Fast, flexible blockchain indexer with auto-generated GraphQL APIs.
- [Dune Analytics](https://dune.com/) - Community-driven blockchain analytics platform using SQL.

### Oracles

- [Chainlink](https://chain.link/) - Decentralized oracle network providing real-world data to smart contracts.
- [Pyth Network](https://pyth.network/) - High-fidelity financial data oracle for DeFi on 40+ chains.
- [API3](https://api3.org/) - First-party oracle solution connecting APIs directly to smart contracts.

## Security & Auditing

### Static Analysis

- [Slither](https://github.com/crytic/slither) - Solidity static analysis framework for vulnerability detection.
- [Aderyn](https://github.com/Cyfrin/aderyn) - Rust-based Solidity static analyzer focused on speed.
- [Solhint](https://github.com/protofire/solhint) - Solidity linter for code consistency and security best practices.

### Dynamic Analysis & Fuzzing

- [Echidna](https://github.com/crytic/echidna) - Smart contract fuzzer for finding vulnerabilities through property testing.
- [Medusa](https://github.com/crytic/medusa) - Parallelized, coverage-guided smart contract fuzzer.
- [Foundry Fuzz Testing](https://book.getfoundry.sh/forge/fuzz-testing) - Built-in fuzz testing capabilities in Foundry.

### Monitoring & Incident Response

- [OpenZeppelin Defender](https://www.openzeppelin.com/defender) - Smart contract operations platform for monitoring, automation, and incident response.
- [Forta](https://forta.org/) - Real-time threat detection network for blockchain activity.
- [Tenderly](https://tenderly.co/) - Full-stack Web3 development platform with transaction simulation and alerting.

### Audit Resources

- [Solodit](https://solodit.xyz/) - Aggregated database of smart contract audit findings.
- [Rekt News](https://rekt.news/) - DeFi exploit postmortem analysis.
- [SWC Registry](https://swcregistry.io/) - Smart Contract Weakness Classification and test cases.

## DeFi Development

### Core Protocols

- [Uniswap V4](https://github.com/Uniswap/v4-core) - Leading AMM protocol with hooks for customizable liquidity pools.
- [Aave V3](https://github.com/aave/aave-v3-core) - Decentralized lending and borrowing protocol.
- [Compound III](https://github.com/compound-finance/comet) - Efficient lending protocol focused on capital efficiency.
- [Curve Finance](https://github.com/curvefi) - AMM optimized for stablecoin and like-asset swaps.

### DeFi Building Blocks

- [OpenZeppelin ERC4626](https://docs.openzeppelin.com/contracts/5.x/erc4626) - Tokenized vault standard for yield-bearing tokens.
- [Uniswap Permit2](https://github.com/Uniswap/permit2) - Canonical token approval and transfer protocol.
- [Flashbots](https://www.flashbots.net/) - Research and development organization for MEV mitigation.

## Zero-Knowledge Proofs

- [circom](https://docs.circom.io/) - Domain-specific language for defining ZK arithmetic circuits.
- [snarkjs](https://github.com/iden3/snarkjs) - JavaScript library for ZK-SNARK proof generation and verification.
- [Noir](https://noir-lang.org/) - Domain-specific language for ZK proofs by Aztec, designed for simplicity.
- [Halo2](https://zcash.github.io/halo2/) - ZK proof system from Zcash, used in many production zkEVM implementations.
- [ZK Book](https://www.rareskills.io/zk-book) - Comprehensive free resource for learning zero-knowledge proof mathematics.
- [zkSync](https://docs.zksync.io/) - Developer-focused ZK rollup with full EVM compatibility.
- [Starknet](https://www.starknet.io/) - Permissionless ZK rollup using STARK proofs and Cairo language.

## AI + Web3

- [Autonolas](https://www.autonolas.network/) - Decentralized platform for creating and running autonomous AI agents on-chain.
- [Bittensor](https://bittensor.com/) - Decentralized AI network enabling machine learning model sharing.
- [Fetch.ai](https://fetch.ai/) - Platform for building autonomous economic agents with AI and blockchain.
- [Ritual](https://ritual.net/) - Infrastructure for integrating AI models into smart contracts.
- [Phala Network](https://phala.network/) - Decentralized off-chain compute for AI inference with confidentiality.

## Testing & Debugging

- [Foundry Testing](https://book.getfoundry.sh/forge/tests) - Fast Solidity testing with Forge including fuzz testing and gas reporting.
- [Hardhat Network](https://hardhat.org/hardhat-network/) - Local Ethereum network for development with console.log, stack traces, and debugging.
- [Tenderly Debugger](https://tenderly.co/) - Visual transaction debugger and simulator for Ethereum.
- [Ganache](https://trufflesuite.com/ganache/) - Personal blockchain for local Ethereum development.
- [Anvil](https://book.getfoundry.sh/anvil/) - Foundry's local testnet node with forking capabilities.

## Learning Resources

### Courses & Platforms

- [Cyfrin Updraft](https://updraft.cyfrin.io/) - Free, comprehensive smart contract security and development courses by Patrick Collins.
- [Buildspace](https://buildspace.so/) - Project-based Web3 learning with a builder community.
- [Encode Club](https://www.encode.club/) - Web3 education through bootcamps, hackathons, and accelerators.
- [Node Guardians](https://nodeguardians.io/) - Gamified Web3 skill challenges for developers.

### Books

- [Mastering Ethereum](https://github.com/ethereumbook/ethereumbook) - Comprehensive guide to Ethereum by Andreas Antonopoulos and Gavin Wood.
- [Mastering Bitcoin](https://github.com/bitcoinbook/bitcoinbook) - Foundational guide to Bitcoin protocol and development.

### Podcasts & Media

- [Bankless](https://www.bankless.com/) - Leading podcast covering DeFi, Ethereum, and crypto culture.
- [Bell Curve](https://www.youtube.com/@bellaboratori) - Deep dives into DeFi and crypto narratives.
- [Unchained](https://unchainedcrypto.com/) - In-depth interviews with crypto industry leaders.

### Communities

- [Ethereum Stack Exchange](https://ethereum.stackexchange.com/) - Q&A forum for Ethereum developers.
- [Ethereum Magicians](https://ethereum-magicians.org/) - Community for Ethereum technical standards discussion.
- [ETHGlobal](https://ethglobal.com/) - Global Ethereum hackathons and events.

## Job Boards

- [CryptoJobsList](https://cryptojobslist.com/) - Curated Web3 job listings across development, design, and marketing.
- [Web3 Career](https://web3.career/) - Job board focused on blockchain and Web3 positions.
- [Remote3](https://remote3.co/) - Remote-first Web3 job opportunities.
- [Crypto Careers](https://www.cryptocareers.co/) - Job listings from top crypto companies.

## Related Awesome Lists

- [Awesome Solidity](https://github.com/bkrem/awesome-solidity) - Curated resources for Solidity development.
- [Awesome Ethereum](https://github.com/ttumiel/Awesome-Ethereum) - Collection of Ethereum-related resources.
- [Awesome ZK](https://github.com/ventali/awesome-zk) - Resources for zero-knowledge proofs.
- [Awesome DeFi](https://github.com/ong/awesome-decentralized-finance) - DeFi protocols, tools, and resources.
- [Awesome NFT](https://github.com/gianni-dalerta/awesome-nft) - NFT-related projects and resources.
- [Awesome Blockchain](https://github.com/yjjnls/awesome-blockchain) - General blockchain resources and tools.

---

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work.
