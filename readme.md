# Awesome Onchain Apps [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome open-source onchain apps.

Every entry links to a genuinely public, open-source repository containing real app, frontend, protocol, or SDK code. Where a project's app is closed-source but its protocol code is open, the entry points at the open component and says so.

## Contents

- [DEX (Decentralized Exchanges)](#dex-decentralized-exchanges)
- [Lending & Borrowing](#lending--borrowing)
- [Stablecoins & CDPs](#stablecoins--cdps)
- [Yield Farming](#yield-farming)
- [Restaking & Liquid Staking](#restaking--liquid-staking)
- [Derivatives & Perps](#derivatives--perps)
- [Cross-chain & Bridges](#cross-chain--bridges)
- [Prediction Markets](#prediction-markets)
- [Onchain Social](#onchain-social)
- [Account Abstraction & Smart Wallets](#account-abstraction--smart-wallets)
- [Governance & DAO Tooling](#governance--dao-tooling)
- [Asset Management](#asset-management)
- [Contribute](#contribute)

## DEX (Decentralized Exchanges)

- [Uniswap](https://github.com/Uniswap/interface) - Leading decentralized exchange protocol that pioneered automated market making—with concentrated liquidity in V3. Public monorepo covering the web app, wallet mobile app, and extension.
- [SushiSwap](https://github.com/sushi-labs/sushiswap) - Decentralized exchange and DeFi platform offering multi-chain trading, yield farming, and additional financial services.
- [Balancer](https://github.com/balancer/frontend-monorepo) - Multi-token pool interface that allows customizable pool weights and flexible liquidity provision.
- [Curve](https://github.com/curvefi/curve-frontend) - Stablecoin and pegged asset exchange optimized for low slippage and efficient stable swaps.
- [CoW Swap](https://github.com/cowprotocol/cowswap) - Intent-based trading UI on CoW Protocol; gasless orders settle peer-to-peer in batch auctions or via on-chain liquidity, with built-in MEV protection.

## Lending & Borrowing

- [Aave](https://github.com/aave/interface) - Leading decentralized lending protocol offering both variable and stable interest rates, flash loans, and multi-chain support.
- [Compound](https://github.com/compound-finance/webb3-frontend) - Algorithmic money market enabling users to lend and borrow crypto assets with automated interest accrual. This is the Compound III (v3) app frontend.
- [Notional Finance](https://github.com/notional-finance/notional-monorepo) - Decentralized fixed-rate lending and borrowing platform providing predictability in interest rates.
- [Alchemix](https://github.com/alchemix-finance/alchemix-v2-react) - Innovative self-repaying loan protocol that uses future yield to automatically service outstanding debt.

## Stablecoins & CDPs

- [Liquity (BOLD)](https://github.com/liquity/bold) - Monorepo (contracts, subgraph, frontend) for the BOLD stablecoin: over-collateralized, user-set-interest-rate CDPs ("Troves") backed by WETH and select LSTs.

## Yield Farming

- [Yearn Finance](https://github.com/yearn/yearn.fi) - Automated yield aggregator that optimizes farming strategies through dynamic vaults and rebalancing.
- [PoolTogether](https://github.com/GenerationSoftware/pooltogether-client-monorepo) - No-loss prize savings protocol (V5 "Cabana"); apps and packages including the Cabana app, vault factory, vault-list creator, and analytics.

## Restaking & Liquid Staking

- [Lido](https://github.com/lidofinance/ethereum-staking-widget) - Embeddable staking widget UI for the leading ETH liquid-staking protocol (stETH). Core contracts live in [lidofinance/core](https://github.com/lidofinance/core).
- [Rocket Pool](https://github.com/rocket-pool/rocketpool) - Decentralized Ethereum liquid-staking protocol (rETH); minipools let node operators stake with reduced ETH bonds across thousands of independent operators.
- [ether.fi](https://github.com/etherfi-protocol/smart-contracts) - Smart contracts for a leading liquid restaking protocol (eETH/weETH).
- [EigenLayer](https://github.com/Layr-Labs/eigenlayer-contracts) - Core restaking contracts (DelegationManager, StrategyManager, EigenPodManager, AllocationManager, RewardsCoordinator) for the leading restaking protocol.
- [Renzo](https://github.com/Renzo-Protocol/contracts-public) - Public production contracts (RestakeManager, OperatorDelegator, xRenzoBridge) for the Renzo liquid restaking protocol (ezETH). The app frontend is closed-source.

## Derivatives & Perps

- [GMX](https://github.com/gmx-io/gmx-interface) - Decentralized perpetual exchange interface for spot and leveraged trading.
- [Velocity (formerly Drift)](https://github.com/velocity-exchange/protocol-v2) - Open-source Solana perpetuals DEX: on-chain programs plus TypeScript/Python SDKs, with cross-margined perps and multiple liquidity mechanisms.

## Cross-chain & Bridges

- [Across](https://github.com/across-protocol/sdk) - SDK for the Across intents-based cross-chain bridge; fast canonical-asset transfers backed by optimistic settlement and a competitive relayer network.
- [LI.FI Widget](https://github.com/lifinance/widget) - Prebuilt, embeddable React UI components for cross-chain bridging and swapping across many chains and bridges (companion [lifinance/sdk](https://github.com/lifinance/sdk)).
- [Socket / Bungee](https://github.com/SocketDotTech/bungee-contracts-public) - Public contracts powering Bungee's cross-chain bridging and aggregation, built on the [Socket data layer](https://github.com/SocketDotTech/socket-DL).
- [Hop Protocol](https://github.com/hop-protocol/hop) - Token bridge designed for fast and secure transfers between Ethereum and Layer 2 scaling solutions.
- [Connext](https://github.com/connext/monorepo) - Cross-chain liquidity network facilitating efficient value transfer and integration for decentralized applications.
- [Arbitrum Bridge](https://github.com/OffchainLabs/arbitrum-token-bridge) - Layer 2 bridge interface that streamlines asset transfers between Ethereum and the Arbitrum network.

## Prediction Markets

- [Azuro](https://github.com/Azuro-protocol/sdk) - SDK and toolkit for the Azuro decentralized prediction-market/betting protocol, with actively maintained subgraph and example-app repos in the same org.
- [Zeitgeist](https://github.com/zeitgeistpm/ui) - General prediction-markets frontend for Zeitgeist, a Substrate/Rust chain purpose-built for prediction markets (chain in [zeitgeistpm/zeitgeist](https://github.com/zeitgeistpm/zeitgeist)).

## Onchain Social

- [herocast](https://github.com/hero-org/herocast) - Open-source power-user Farcaster client ("no algorithms, you own your data"); web plus tooling.

## Account Abstraction & Smart Wallets

- [Safe](https://github.com/safe-global/safe-wallet-monorepo) - Safe{Wallet} web and mobile apps for the leading multisig smart-account wallet.
- [ZeroDev (Kernel)](https://github.com/zerodevapp/kernel) - Modular ERC-4337 / 7579 / 7702 smart-account contracts.
- [Biconomy (Nexus)](https://github.com/bcnmy/nexus) - ERC-7579 modular smart-account contracts, paired with the [AbstractJS SDK](https://github.com/bcnmy/abstractjs).
- [Ambire](https://github.com/AmbireTech/extension) - Browser extension for the Ambire smart-account wallet (EIP-7702-ready); core logic in [ambire-common](https://github.com/AmbireTech/ambire-common).

## Governance & DAO Tooling

- [MakerDAO / Sky](https://github.com/skybase-foundation/governance-portal-v2) - Governance portal for the Sky (formerly MakerDAO) ecosystem behind the USDS/DAI stablecoin, including collateral and risk management.
- [UMA](https://github.com/UMAprotocol/protocol) - Decentralized platform for creating synthetic assets and derivatives using an optimistic oracle system and on-chain governance.
- [Compound Governance](https://github.com/compound-finance/compound-governance) - On-chain governance interface that facilitates protocol upgrades and decision-making for Compound.
- [ENS App](https://github.com/ensdomains/ens-app-v3) - Decentralized naming service interface enabling domain registration and community governance within the ENS ecosystem.
- [Snapshot](https://github.com/snapshot-labs/sx-monorepo) - Monorepo (Vue frontend, GraphQL API, relayer, TypeScript SDK) for gasless, off-chain, multi-governance voting.
- [Aragon](https://github.com/aragon/app) - Human-centered DAO management app for the Aragon OSx modular DAO framework; contracts in [aragon/osx](https://github.com/aragon/osx).
- [Tally](https://github.com/withtally/tally-zero) - Open-source decentralized on-chain voting client (Next.js, IPFS). The flagship tally.xyz app is closed-source.

## Asset Management

- [Index Coop](https://github.com/IndexCoop/index-app) - Decentralized crypto index fund interface that provides diversified market exposure through tokenized indices.
- [HostDeFi](https://hostdefi.com) — free token-safety scanner grading tokens A+–F from on-chain checks (mint/freeze authority, liquidity, holder concentration) across Solana + 7 EVM chains. Keyless REST API, hosted MCP, x402 endpoints.

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)
