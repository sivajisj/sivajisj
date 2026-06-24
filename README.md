<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=200&section=header&text=Sivaji%20Gadidala&fontSize=50&fontColor=ffffff&fontAlignY=35&desc=Blockchain%20Engineer%20%7C%20Solana%20%C2%B7%20EVM%20%C2%B7%20Rust%20Backend&descAlignY=55&descColor=a78bfa" />

<a href="https://linkedin.com/in/sivaji-gadidala-b712ba221"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="https://twitter.com/iamsivajisj"><img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" /></a>
<a href="mailto:sivajigsivajig703@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="https://sivajibuilds.netlify.app/"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" /></a>

<img src="https://komarev.com/ghpvc/?username=sivajisj&style=for-the-badge&color=a78bfa&label=Profile+Views" />

</div>

---

## 👨‍💻 About Me

Full-stack blockchain engineer shipping production systems across **three pillars**: **Solana** (Anchor, SPL, PDAs, CPIs), **Ethereum/EVM** (Solidity, Hardhat, OpenZeppelin), and **Rust backend infrastructure** (Axum, Tokio, async microservices). I build complete decentralized systems end-to-end — on-chain programs, smart contracts, high-throughput Rust APIs, event-driven relayers, and the frontends that wrap them.

Currently building at **Simreka Softwares Pvt. Ltd.**, and actively expanding into **DePIN** (decentralized physical infrastructure) protocols on Solana.

```text
Solana        →  Anchor · SPL · PDAs · CPIs · Token 2022 · sBPF
Ethereum/EVM  →  Solidity · Hardhat · OpenZeppelin v5 · ethers.js v6
Rust Backend  →  Axum · Tokio · Serde · SQLx · async/await · REST & gRPC
DePIN         →  On-chain heartbeats · uptime proofs · trustless rewards
Frontend      →  React · Next.js · Redux Toolkit · TypeScript
```

---

## 🚀 Now Building

🛰️ **DePIN infrastructure on Solana** — trustless, cryptographically-verified uptime tracking for physical hardware (see RouterPulse below)
🗳️ **On-chain governance primitives** — wallet-gated voting systems with smart-contract-sourced truth (see Voting Board below)

---

## 🔗 Featured Projects

### ⛓️ Solana & DePIN

<details open>
<summary><b>📡 RouterPulse — DePIN Uptime Protocol</b></summary>
<br>

> Trustless Wi-Fi router uptime tracking and reward-distribution protocol. Replaces self-reported uptime claims with cryptographic, on-chain proof — routers submit signed heartbeat transactions that are permanently recorded on Solana.

- ⚙️ Automated uptime scoring engine — **+1** per on-time heartbeat, **−10** per late one, **auto-suspend at 20**
- 💰 Reward distribution computed purely from verified on-chain uptime %, not operator self-reporting
- 🖥️ No public UI — pure on-chain program + local heartbeat simulator (3 simulated routers, varying failure rates) for testing
- **Stack:** `Rust` `Anchor 0.30` `Solana` `TypeScript (simulator)` `solana-test-validator`
- **Status:** 🧪 Local devnet simulation

</details>

<details>
<summary><b>⚡ Solana Programs — Anchor Framework</b></summary>
<br>

> On-chain programs leveraging core Solana primitives.

- **Scope:** Custom PDAs · CPI composition · SPL Token minting & transfer · Token 2022 extensions
- **Stack:** `Rust` `Anchor` `@solana/web3.js` `Solana CLI`
- **Concepts:** Account validation · Program-derived addresses · Cross-program invocations · Associated token accounts

</details>

### 🏛️ Ethereum / EVM

<details>
<summary><b>🗳️ Decentralized Voting Board</b></summary>
<br>

> On-chain voting platform — admins create proposals and register voters; voters connect MetaMask and cast votes that settle directly on-chain, with live chart-based result visualization.

- ✅ Vote counts read **live from the smart contract**, never cached or trusted from the DB — eliminates double-voting and result tampering
- 👤 Admin dashboard for proposal creation & voter registration; separate voter dashboard for wallet-gated voting
- 🔐 JWT auth in httpOnly cookies layered on top of on-chain vote integrity
- **Stack:** `Next.js` `TypeScript` `Solidity` `Hardhat` `ethers.js v6` `MongoDB` `MetaMask`
- **Status:** 🧪 Local Hardhat network + MongoDB

</details>

<details>
<summary><b>🌉 Cross-Chain Token Bridge — Sepolia ↔ Polygon Amoy</b></summary>
<br>

> Lock-and-mint architecture bridging ERC-20 tokens across L1/L2 chains.

- **Pattern:** Lock on source chain → event-driven Node.js relayer → mint on destination chain
- **Stack:** `Solidity` `Hardhat` `OpenZeppelin v5` `ethers.js v6` `Node.js` `React` `MetaMask`
- **Status:** ✅ Deployed & verified on live testnets

[![Sepolia Contract](https://img.shields.io/badge/Etherscan-Sepolia_Contract-3C3C3D?style=flat-square&logo=ethereum)](https://sepolia.etherscan.io)
[![Amoy Contract](https://img.shields.io/badge/Polygonscan-Amoy_Contract-8247E5?style=flat-square&logo=polygon)](https://amoy.polygonscan.com)

</details>

<details>
<summary><b>🏦 DeFi Lending Protocol</b></summary>
<br>

> Permissionless lending and borrowing with collateral management.

- **Features:** Deposit, borrow, repay, liquidation logic, interest accrual
- **Pattern:** Over-collateralized lending with on-chain price feed integration
- **Stack:** `Solidity` `Hardhat` `OpenZeppelin` `ethers.js` `React`

</details>

### 🦀 Rust Backend & AI Security

<details>
<summary><b>⚙️ High-Performance Transaction Service</b></summary>
<br>

> Async transaction-processing microservice built for blockchain workloads.

- **Features:** Transaction queuing · status tracking · retry logic with backoff · webhook notifications · multi-chain support
- **Design:** Fully async, non-blocking architecture — zero-cost abstractions and memory safety for high-throughput, low-latency pipelines
- **Stack:** `Rust` `Axum` `Tokio` `Serde` `SQLx` `PostgreSQL`

</details>

<details>
<summary><b>🤖 AI-Powered Blockchain Security Agent</b></summary>
<br>

> Autonomous agent for smart contract vulnerability detection and on-chain analytics.

- **Detects:** Reentrancy · integer overflow · access control flaws · unchecked external calls
- **Features:** Static Solidity analysis · AI-driven audit report generation · transaction pattern recognition · real-time anomaly detection
- **Stack:** `Rust` `Python` `LLM APIs` `Solidity AST parsing` `Node.js` `React`

</details>

---

## 🛠 Tech Stack & Skills

<table>
<tr><td valign="top" width="50%">

**⛓ Blockchain — Languages & Frameworks**
![Solidity](https://img.shields.io/badge/Solidity-363636?style=flat-square&logo=solidity&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Anchor](https://img.shields.io/badge/Anchor-9945FF?style=flat-square&logo=solana&logoColor=white)
![Solana](https://img.shields.io/badge/Solana-9945FF?style=flat-square&logo=solana&logoColor=white)
![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?style=flat-square&logo=ethereum&logoColor=white)

**🔧 Blockchain Tooling**
![Hardhat](https://img.shields.io/badge/Hardhat-FFF04D?style=flat-square&logo=hardhat&logoColor=black)
![Foundry](https://img.shields.io/badge/Foundry-000000?style=flat-square&logo=foundry&logoColor=white)
![OpenZeppelin](https://img.shields.io/badge/OpenZeppelin-4E5EE4?style=flat-square&logo=openzeppelin&logoColor=white)
![ethers.js](https://img.shields.io/badge/ethers.js_v6-2535A0?style=flat-square&logo=ethereum&logoColor=white)
![web3.js](https://img.shields.io/badge/web3.js-F16822?style=flat-square&logo=web3dotjs&logoColor=white)

**🦀 Rust Backend**
![Axum](https://img.shields.io/badge/Axum-000000?style=flat-square&logo=rust&logoColor=white)
![Tokio](https://img.shields.io/badge/Tokio-000000?style=flat-square&logo=rust&logoColor=orange)
![Serde](https://img.shields.io/badge/Serde-000000?style=flat-square&logo=rust&logoColor=yellow)
![SQLx](https://img.shields.io/badge/SQLx-336791?style=flat-square&logo=postgresql&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-244c5a?style=flat-square&logo=google&logoColor=white)

</td><td valign="top" width="50%">

**🖥 Node.js / Infra**
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=flat-square&logo=socketdotio&logoColor=white)

**🎨 Frontend**
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Redux](https://img.shields.io/badge/Redux_Toolkit-764ABC?style=flat-square&logo=redux&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)

**🔨 Dev Tools**
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Solana CLI](https://img.shields.io/badge/Solana_CLI-9945FF?style=flat-square&logo=solana&logoColor=white)
![MetaMask](https://img.shields.io/badge/MetaMask-E2761B?style=flat-square&logo=metamask&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)

</td></tr>
</table>

---

## 🧠 Concepts & Primitives

<details>
<summary><b>Solana / Anchor</b></summary>

```text
✦ Program Derived Addresses (PDAs)     ✦ Cross-Program Invocations (CPIs)
✦ SPL Token standard                   ✦ Token 2022 extensions
✦ Associated Token Accounts (ATAs)     ✦ Account validation & constraints
✦ sBPF VM internals                    ✦ Anchor account macros & IDL generation
✦ Instruction data serialization       ✦ Rent & lamport management
✦ On-chain heartbeat/proof patterns    ✦ Trustless reward distribution (DePIN)
```
</details>

<details>
<summary><b>Ethereum / EVM</b></summary>

```text
✦ ERC-20 / ERC-721 / ERC-1155          ✦ Proxy patterns (UUPS, Transparent)
✦ Cross-chain bridge architecture       ✦ Lock-and-mint pattern
✦ Over-collateralized lending           ✦ Liquidation mechanics
✦ OpenZeppelin v5 contracts             ✦ Gas optimization techniques
✦ Event-driven relayer design           ✦ Hardhat forking & testing
✦ On-chain source-of-truth voting       ✦ Wallet-gated authorization flows
```
</details>

<details>
<summary><b>Rust Backend Systems</b></summary>

```text
✦ Async/await with Tokio runtime        ✦ Axum web framework & routing
✦ Serde serialization/deserialization   ✦ SQLx async DB queries
✦ REST API design & error handling      ✦ Middleware & tower layers
✦ Ownership & borrowing model           ✦ Trait-based abstractions
✦ Microservice architecture             ✦ gRPC with tonic
```
</details>

---

## 💼 Experience

| Role | Company | Period |
|------|---------|--------|
| Full Stack Blockchain Engineer | Simreka Softwares Pvt. Ltd. | Aug 2024 – Present |
| Blockchain Developer Intern | Octaverse LLP | Prior |

---

## 📊 GitHub Stats

<div align="center">

<img height="170em" src="https://github-readme-stats.vercel.app/api?username=sivajisj&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true"/>
<img height="170em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=sivajisj&layout=compact&langs_count=8&theme=tokyonight&hide_border=true&hide=html,css"/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=sivajisj&theme=tokyonight&hide_border=true" />

</div>

---

## 📫 Open to Opportunities

Actively looking for **Blockchain Engineer** and **Rust Backend Engineer** roles focused on:
- Solana programs & DePIN protocols (Anchor, Rust, SPL)
- Ethereum/EVM smart contract & protocol development
- Cross-chain infrastructure and bridge architecture
- High-performance Rust backend services for Web3 products

**Reach me:** sivajigsivajig703@gmail.com · [LinkedIn](https://linkedin.com/in/sivaji-gadidala-b712ba221)

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=100&section=footer" />

</div>
