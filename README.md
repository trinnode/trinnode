```console
 _____ ____  ___ _   _ _   _  ___  ____  _____
|_   _|  _ \|_ _| \ | | \ | |/ _ \|  _ \| ____|
  | | | |_) || ||  \| |  \| | | | | | | |  _|
  | | |  _ < | || |\  | |\  | |_| | |_| | |___
  |_| |_| \_\___|_| \_|_| \_|\___/|____/|_____|
```

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&duration=2800&pause=800&color=00FF9C&center=true&vCenter=true&multiline=true&repeat=true&width=760&height=100&lines=root%40trinnode%3A~%24+whoami;Smart+Contract+Engineer+%26+Security+Researcher;Zero-Knowledge+%C2%B7+DeFi+%C2%B7+Account+Abstraction;Open+to+audit+engagements)](https://git.io/typing-svg)

[![Status](https://img.shields.io/badge/STATUS-OPEN_TO_AUDITS-00FF9C?style=for-the-badge&labelColor=0d1117)](mailto:koinated@gmail.com)
[![Followers](https://img.shields.io/github/followers/trinnode?label=FOLLOWERS&style=for-the-badge&color=00FF9C&labelColor=0d1117&logo=github&logoColor=00FF9C)](https://github.com/trinnode?tab=followers)
[![Profile Views](https://komarev.com/ghpvc/?username=trinnode&label=VIEWS&color=00FF9C&style=for-the-badge)](https://github.com/trinnode)

</div>

```console
trinnode@web3:~$ whoami
Isah Dauda  ──  Smart Contract Engineer · Security Researcher · Full-Stack Web3 Developer

trinnode@web3:~$ cat /etc/focus
DeFi protocols · zero-knowledge privacy · account abstraction · adversarial security review

trinnode@web3:~$ echo $PHILOSOPHY
"I build onchain systems that have to hold up when someone is actively trying to break them."
```

---

## `$ ./metrics.sh`

<table align="center">
<tr>
<td align="center" width="33%">

### `55+`
**ORIGINAL REPOS**
<sub>none forked · none contributed</sub>

</td>
<td align="center" width="33%">

### `24`
**LIVE DEPLOYMENTS**
<sub>shipped to production URLs</sub>

</td>
<td align="center" width="33%">

### `8`
**CHAINS SHIPPED ON**
<sub>EVM · Hedera · Bitcoin · Starknet</sub>

</td>
</tr>
<tr>
<td align="center" width="33%">

### `7`
**LANGUAGES**
<sub>Solidity · Cairo · Clarity · Compact</sub>

</td>
<td align="center" width="33%">

### `2`
**EIP-2535 DIAMONDS**
<sub>modular proxy systems in production</sub>

</td>
<td align="center" width="33%">

### `ZK · FHE`
**PRIVACY PRIMITIVES**
<sub>Groth16 · Cairo · Fhenix CoFHE</sub>

</td>
</tr>
</table>

---

## `$ ls -la ./expertise`

<table>
<tr>
<td width="50%" valign="top">

**`drwxr-xr-x  smart-contracts/`**
- Solidity 0.8 · Foundry · Hardhat
- EIP-2535 Diamonds & upgradeable proxies
- ERC-4337 account abstraction & session keys
- HTS / HCS (Hedera) · Clarity · Cairo · Compact
- Gas optimisation & storage packing

</td>
<td width="50%" valign="top">

**`drwxr-xr-x  security/`**
- Per-function threat modelling
- Foundry fuzz + invariant testing
- Slither · Aderyn · Echidna · Mythril
- Manual review against the SWC registry
- Reentrancy, oracle & access-control analysis

</td>
</tr>
<tr>
<td width="50%" valign="top">

**`drwxr-xr-x  zero-knowledge/`**
- SnarkJS / Groth16 proofs
- Cairo circuits · Pedersen commitments
- FHE with Fhenix (CoFHE)
- Selective disclosure & onchain verification

</td>
<td width="50%" valign="top">

**`drwxr-xr-x  full-stack/`**
- Next.js · React 19 · TypeScript · Tailwind
- Prisma · PostgreSQL · Node.js
- wagmi · viem · RainbowKit wallet flows
- Docker · CI/CD · Vercel & Railway

</td>
</tr>
</table>

---

## `$ git log --author=trinnode --stat`

> Personal builds I designed and shipped end to end. No forks. No contributed PRs.

### `> zero-knowledge/`

| Project | What it does | Stack |
| :-- | :-- | :-- |
| **[VERIDAQ](https://github.com/trinnode/veridaq-official)** · [live](https://veridaq-official.vercel.app) | ZK academic credential verification. Universities issue on their own backend; employers verify claims like *"CGPA above 3.5"* without ever seeing student data. Only a 32-byte commitment touches Base L2. | `Base` `SnarkJS` `Next.js` `TypeScript` |
| **[ClearScope](https://github.com/trinnode/clearscope)** | Compliance proofs without disclosure on Midnight Network — holder wallet, verifier dashboard, issuer portal, governance registry, bearer-session auth and ZK eligibility checks for age, KYC and jurisdiction. Apache-2.0, CI-gated. | `Midnight` `Compact` `TypeScript` |
| **[StealthBTC](https://github.com/trinnode/StealthBTC)** | Privacy-first Bitcoin liquid staking on Starknet. Deposit BTC, earn Babylon yield, withdraw to any address unlinked from the deposit via ZK proofs and Pedersen commitments. | `Starknet` `Cairo` `React` |
| **[SealBid](https://github.com/trinnode/Seal_Bid)** | Private sealed-bid auction on Base. Bids stay encrypted in flight with Fhenix FHE; the contract resolves the highest bid without revealing anyone's amount. | `Base` `Fhenix CoFHE` `Solidity` `wagmi` |

### `> defi/`

| Project | What it does | Stack |
| :-- | :-- | :-- |
| **[AfriHealth Ledger](https://github.com/trinnode/AfriHealthv2)** · [live](https://afri-healthv2-frontend-9tth.vercel.app) | Hedera-native healthcare + insurance platform: patient-controlled consent, itemized billing with AI policy checks, on-ledger community insurance pool. Modular EIP-2535 Diamond (Consent, Billing, InsurancePool, Token facets). | `Hedera` `Solidity` `HTS` `Diamond` |
| **[CPPay](https://github.com/trinnode/CP-Pay-SC)** | Non-custodial account-abstraction wallet on Lisk L2 — gasless one-tap payments via session keys, social recovery with guardians, on-chain swaps, EOA import. Diamond standard + ERC-4337, 100% test coverage. | `Lisk L2` `ERC-4337` `Diamond` |
| **[SomiARB](https://github.com/trinnode/SomiARB)** · [live](https://somiarb.vercel.app) | Reactive cross-DEX arbitrage vault on Somnia. Data Streams push price gaps to the vault in milliseconds instead of polling cycles — real-time strategy, not near-real-time. | `Somnia` `Solidity` `React` |
| **[Fixpoint](https://github.com/trinnode/fixPoint)** · [live](https://fix-point-two.vercel.app) | USD-priced escrow on Hedera. Invoice in dollars, settle in HBAR at a live Pyth rate, mint an HTS receipt, land every step on an HCS audit trail. 43 contract tests, MIT licensed. | `Hedera` `Pyth` `HTS` `HCS` |
| **[BitGlyph](https://github.com/trinnode/BitGlyph)** · [live](https://bit-glyph.vercel.app) | Living generative-art NFTs on Stacks that evolve as collectors charge them with real Bitcoin (sBTC); every evolution state is stored on-chain and rendered live with p5.js. | `Stacks` `Clarity` `sBTC` `p5.js` |
| **[Tribute](https://github.com/trinnode/Tribute)** | Programmable patronage on Bitcoin — Clarity contracts, a Plasmo browser extension and a creator dashboard for recurring, relationship-aware support. | `Bitcoin` `Clarity` `Plasmo` |

### `> products/`

| Project | What it does | Stack |
| :-- | :-- | :-- |
| **[Votara](https://github.com/trinnode/votara)** · [live](https://votarahq.vercel.app) | Multi-tenant voting platform for contests — live leaderboards, contestant profiles, 3D tilt UI and Flutterwave OAuth 2.0 payments. | `Next.js 16` `Prisma` `PostgreSQL` `Flutterwave` |
| **[Anglican Schools](https://github.com/trinnode/anglican-schools)** · [live](https://anglican-schools.vercel.app) | Production multi-branch school management for the Nigerian system — token-based staff access across 11 roles, drag-and-drop report-card builder, fees, waivers and a full audit trail. | `Next.js 16` `React 19` `Prisma` `shadcn/ui` |
| **[Sentinel](https://github.com/trinnode/Sentinel)** | Enterprise validator monitoring that moves past reactive alerts — peer-to-peer cross-checks between nodes filter false positives before they ever page on-call. | `Node.js` `React` `PostgreSQL` `Docker` |
| **[NoteFlex](https://github.com/trinnode/NoteFlex)** | Android floating notepad that stays on top of every other app — multiple tabs, drag, resize, collapse and autosave. Sideloadable via release APK. | `Kotlin` `Android` |

### `> security-research/`

| Project | What it does | Stack |
| :-- | :-- | :-- |
| **[Phishing Domain Detection](https://github.com/trinnode/phishing-detection)** | Research framework comparing Random Forest vs XGBoost over lexical and structural URL features. Flask REST API plus a full training pipeline. FUT Minna chapter-4 implementation. | `Python` `scikit-learn` `Flask` |
| **[BExtDetect](https://github.com/trinnode/BExtDetect)** | Chrome-extension malware scanner — static manifest and code analysis (permissions, suspicious patterns, entropy) fused with a sandboxed headless-browser run into one risk score. | `Python` `Node.js` `Chromium` |
| **[Disinformation Detection](https://github.com/trinnode/Social-Media-Disinformation-Detection)** | Multimodal fake-post detector — ResNet + ELA for tampered images, DistilBERT for text credibility, fused into a single prediction. | `Python` `PyTorch` `Transformers` |

---

## `$ cat stack.json`

<div align="center">

**`chains/`**

![Solidity](https://img.shields.io/badge/Solidity-363636?style=for-the-badge&logo=solidity&logoColor=00FF9C)
![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?style=for-the-badge&logo=ethereum&logoColor=00FF9C)
![Base](https://img.shields.io/badge/Base-0052FF?style=for-the-badge&logo=base&logoColor=white)
![Hedera](https://img.shields.io/badge/Hedera-222222?style=for-the-badge&logo=hedera&logoColor=00FF9C)
![Stacks](https://img.shields.io/badge/Stacks-5546FF?style=for-the-badge&logo=stacks&logoColor=white)
![Starknet](https://img.shields.io/badge/Starknet-0C0C4F?style=for-the-badge&logoColor=white)
![Foundry](https://img.shields.io/badge/Foundry-000000?style=for-the-badge&logoColor=00FF9C)
![Hardhat](https://img.shields.io/badge/Hardhat-FFF100?style=for-the-badge&logoColor=black)
![OpenZeppelin](https://img.shields.io/badge/OpenZeppelin-4E5EE4?style=for-the-badge&logo=openzeppelin&logoColor=white)

**`security/`**

![Slither](https://img.shields.io/badge/Slither-FF6B6B?style=for-the-badge&logoColor=white)
![Aderyn](https://img.shields.io/badge/Aderyn-8B5CF6?style=for-the-badge&logoColor=white)
![Echidna](https://img.shields.io/badge/Echidna-00CED1?style=for-the-badge&logoColor=white)
![Mythril](https://img.shields.io/badge/Mythril-4B0082?style=for-the-badge&logoColor=white)
![SnarkJS](https://img.shields.io/badge/SnarkJS-6E56CF?style=for-the-badge&logoColor=white)

**`engineering/`**

![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=00FF9C)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

</div>

---

## `$ ./analytics --live`

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=trinnode&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&rank_icon=github&bg_color=0d1117&title_color=00FF9C&icon_color=00FF9C&text_color=c9d1d9" alt="GitHub Stats" width="49%" />
<img src="https://streak-stats.demolab.com?user=trinnode&hide_border=true&background=0D1117&stroke=30363D&ring=00FF9C&fire=00FF9C&currStreakNum=c9d1d9&sideNums=c9d1d9&currStreakLabel=00FF9C&sideLabels=00FF9C&dates=8b949e" alt="GitHub Streak" width="49%" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=trinnode&layout=compact&hide_border=true&langs_count=8&exclude_repo=trinnode&bg_color=0d1117&title_color=00FF9C&text_color=c9d1d9" alt="Top Languages" width="38%" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=trinnode&theme=github_dark" alt="Repos per Language" width="29%" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=trinnode&theme=github_dark&utcOffset=1" alt="Productive Time" width="29%" />

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=trinnode&theme=github_dark" alt="Profile Details" width="98%" />

</div>

### `$ tail -f contribution.log`

<div align="center">

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=trinnode&bg_color=0d1117&color=00FF9C&line=00FF9C&point=ffffff&area=true&area_color=00FF9C&title_color=00FF9C&hide_border=true&custom_title=Contribution%20Flow)](https://github.com/trinnode)

![Snake animation](https://raw.githubusercontent.com/trinnode/trinnode/output/github-contribution-grid-snake-dark.svg)

<img src="https://github-profile-trophy.vercel.app/?username=trinnode&theme=onedark&no-frame=true&no-bg=true&column=7&margin-w=8&margin-h=8" alt="GitHub Trophies" />

</div>

---

## `$ tail -f activity.log`

<!--START_SECTION:activity-->
1. ℹ️ Assigned issue [#1816](https://github.com/SorobanCrashLab/soroban-crashlab/issues/1816) in [SorobanCrashLab/soroban-crashlab](https://github.com/SorobanCrashLab/soroban-crashlab)
<!--END_SECTION:activity-->

---

## `$ ./connect.sh --open`

```console
trinnode@web3:~$ echo "audits · protocol engineering · security review — let's build."
audits · protocol engineering · security review — let's build.
```

<div align="center">

[![Email](https://img.shields.io/badge/koinated%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:koinated@gmail.com)
[![X](https://img.shields.io/badge/%40__trinnex-000000?style=for-the-badge&logo=x&logoColor=00FF9C)](https://twitter.com/_trinnex)
[![LinkedIn](https://img.shields.io/badge/in%2Ftrinnex-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/trinnex)
[![GitHub](https://img.shields.io/badge/trinnode-181717?style=for-the-badge&logo=github&logoColor=00FF9C)](https://github.com/trinnode)

</div>
