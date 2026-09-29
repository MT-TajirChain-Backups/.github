<p align="center">
  <img src="https://tajirchain.com/favicon.ico" alt="Tajir Chain Logo" width="80"/>
</p>

<h1 align="center">Tajir Chain</h1>

<p align="center">
  <strong>An EVM-compatible Layer 2 blockchain designed for digital commerce, payments, supply-chain applications, enterprise platforms, and decentralized applications.</strong>
</p>

---

## 📖 Overview

Tajir Chain uses Polygon CDK with OP Stack execution technology and is integrated with Polygon AggLayer. Ethereum Mainnet serves as the L1 settlement layer. 

## ⚡ Key Capabilities

* Full EVM and Solidity compatibility.
* Fast transaction processing.
* TJR as the native gas token.
* Ethereum-compatible wallet and address format.
* Standard Ethereum JSON-RPC support.
* Smart-contract deployment using familiar EVM tools.
* Polygon AggLayer connectivity.
* Public block explorer and explorer APIs.
* Mainnet and testnet developer environments.
* Open network configuration and deployment provenance.

---

## 🌐 Mainnet at a Glance

| Property | Value |
| :--- | :--- |
| **Network Name** | Tajir Chain |
| **Chain ID** | 3377 |
| **Chain ID in Hex** | 0xd31 |
| **Native Currency** | TJR |
| **Currency Decimals** | 18 |
| **Block Time** | Approximately 2 seconds |
| **Execution Stack** | OP Stack |
| **Interoperability and Settlement** | Polygon AggLayer |
| **AggLayer ID** | 28 |
| **L1 Settlement Network** | Ethereum Mainnet |
| **Mainnet RPC** | https://rpc.tajirchain.com |
| **Block Explorer** | https://tjrscan.com/ |
| **Mainnet Bridge** | https://bridge.tajirchain.com |

---

## 🏗️ Architecture & Settlement

The production architecture is an EVM-compatible Layer 2 network utilizing OP Stack execution infrastructure alongside Polygon AggLayer connectivity.

### Architecture Summary
* **Execution Client:** OP-Geth compatible execution.
* **Agglayer Driver:** OP Node compatible processing.
* **Sequencer:** Orders and executes transactions.
* **State Database:** Maintains accounts, balances, contracts, and network state.
* **RPC Infrastructure:** Provides access to wallets, applications, exchanges, and indexers.
* **Polygon AggLayer:** Provides cross-chain interoperability and coordinated settlement.
* **Ethereum Mainnet:** Serves as the L1 settlement network.
* **Block Explorer:** Provides public transaction, address, block, and contract visibility.

### Settlement Flow
1. Users submit EVM-compatible transactions to Tajir Chain.
2. The Tajir sequencer orders and executes the transactions.
3. Blocks are produced approximately every two seconds.
4. Network state and settlement information are processed through Polygon AggLayer.
5. Final settlement is anchored to Ethereum Mainnet.

---

## 📂 Public Repositories

* **[tajir-block-explorer](https://github.com/Tajir-Chain/tajir-block-explorer)**: TypeScript frontend.
* **[tajir-block-explorer-backend](https://github.com/Tajir-Chain/tajir-block-explorer-backend)**: Tajir Blockscout Backend (fork of blockscout/blockscout with `CHAIN_TYPE=polygon_zkevm`), built with Elixir.
* **[tajir-chain-bridge-ui](https://github.com/Tajir-Chain/tajir-chain-bridge-ui)**: TypeScript frontend.
* **[tajir-chain-faucet](https://github.com/Tajir-Chain/tajir-chain-faucet)**
* **[swaggers](https://github.com/Tajir-Chain/swaggers)**: Forked from blockscout/swaggers, built with HTML.
* **[tajir-chain-registry](https://github.com/Tajir-Chain/tajir-chain-registry)**: Canonical Chain Registry.
* **[core-contracts](https://github.com/Tajir-Chain/core-contracts)**
* **[explorer](https://github.com/Tajir-Chain/explorer)**
* **[bridge-ui](https://github.com/Tajir-Chain/bridge-ui)**
* **[indexer](https://github.com/Tajir-Chain/indexer)**

---

## 🔗 Official Resources

* **Website:** [https://tajirchain.com](https://tajirchain.com)
* **Documentation:** [https://docs.tajirchain.com/](https://docs.tajirchain.com/)
* **GitHub Organization:** [https://github.com/Tajir-Chain](https://github.com/Tajir-Chain)
* **Canonical Chain Registry:** [https://github.com/Tajir-Chain/tajir-chain-registry](https://github.com/Tajir-Chain/tajir-chain-registry)
