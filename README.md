# Sid Hary

**Smart Contract Engineer · Solidity / Foundry · Security-Focused**

Hi there👋, I'm Sid! IIT Roorkee grad (Mechanical Engineering, '25). Self-taught Solidity Dev. Shipping protocols with rigorous testing, working on contributing back to the eco-system, and pointed toward smart contract security auditing.
Currently in Cyfrin Smart Contract Security & Auditing Curriculum and parallelly making some of my own robust projects. Sharing all the learnings publicly on X [@Sid_Hary_](https://x.com/Sid_Hary_)

---

## Featured Projects

### 📝 [NFT-Gated-Membership-DAO](https://github.com/Sidified/NFT-Gated-Membership-DAO) — *Deployed: Sepolia*
A community bootstrapping a DAO. A pre-verified list of contributors (the VIP list) claims free, soulbound membership NFTs that grant governance voting power. The NFT's appearance dynamically upgrades on-chain based on governance participation. Members govern a treasury via a standard propose -> vote -> timelock -> execute flow.

### 🚀 [Decentralized Subscription Service](https://github.com/Sidified/Decentralized-Subscription-Service) — *Deployed: Sepolia*
Autonomous recurring-payment protocol using per-user escrow custody that eliminates the infinite-approval risk of standard subscription models. Chainlink Automation executes renewals against isolated user balances; per-subscription failure isolation prevents one broken subscription from halting the entire batch.
**70 tests + 3 fuzz tests + 2 stateful invariants running 256K+ randomized handler calls.**

### 🔒 [Time-Locked Vault](https://github.com/Sidified/Time-Locked-Vault)
Trustless ETH/ERC20 custody with admin-less architecture (no owner, no pause, no rescue). Hardened against malicious tokens via balance-delta accounting for fee-on-transfer detection and SafeERC20 for non-standard returns.
**41 tests + 128K-operation invariant on ETH balance accounting, with custom adversarial mocks (FeeOnTransferToken, RejectingReceiver, ReentrantAttacker).**

### 🔐 [ERC-4337 + zkSync Native Account Abstraction](https://github.com/Sidified/Account-Abstraction)
Dual account-abstraction implementation across Ethereum (ERC-4337 minimal smart wallet) and zkSync Era (native AA flow). Diagnosed and fixed a CI failure caused by incompatibility between Foundry's standard workflow and zkSync's `--zksync` toolchain; contributed the fix upstream via [Cyfrin PR #20](https://github.com/Cyfrin/minimal-account-abstraction/pull/20).

### 💵 [Decentralized Stablecoin Protocol (DSC)](https://github.com/Sidified/DeFi-StableCoin)
MakerDAO-style overcollateralized stablecoin with liquidation engine, health-factor mechanics, and Chainlink Price Feeds. Invariant tests assert protocol solvency: total collateral USD value ≥ total DSC supply at all times.

---

## Open Source Contributions

- **[Cyfrin / minimal-account-abstraction](https://github.com/Cyfrin/minimal-account-abstraction/pull/20)** — PR #20: CI workflow fix enabling correct separation of Foundry's standard toolchain from zkSync's `--zksync` toolchain.
- **[Cyfrin / foundry-upgrades-cu](https://github.com/Cyfrin/foundry-upgrades-cu/issues/17)** — Issue #17: Documented OpenZeppelin v4 → v5 migration for upgradeable contract patterns.
- **[Cyfrin / foundry-dao-cu](https://github.com/Cyfrin/foundry-dao-cu/issues/18)** — Issue #18: Documented OZ v4 → v5 migration across the DAO/Governor stack, including contract-size CI failure resolved via optimizer settings.

---

## Additional Projects

- **[UUPS Upgradeable Protocol](https://github.com/Sidified/UUPS-Proxy-Protocol)** — Production-style upgradeable contracts with OpenZeppelin v5
- **[Rebase Token + Chainlink CCIP](https://github.com/Sidified/Rebase-Token)** — Cross-chain rebasing token with lazy-minting interest accrual
- **[Merkle Airdrop](https://github.com/Sidified/Merkle-Airdrop)** — Gas-efficient token distribution via Merkle proofs
- **[Automated Payroll](https://github.com/Sidified/foundry-automated-payroll)** — Recurring payroll powered by Chainlink Automation + VRF
- **[Provably Fair Lottery](https://github.com/Sidified/foundry-smart-contract-lottery)** — Chainlink VRF + Automation lottery with CEI guards
- **[Simple DAO](https://github.com/Sidified/Simple-DAO)** — Five-contract OZ Governor stack (Box, GovToken, MyGovernor, TimeLock) with full v4 → v5 migration

---

## Stack

**Languages:** Solidity, Bash

- **Frameworks:** Foundry (Forge, Cast, Anvil, Chisel)
- **Standards:** ERC-20, ERC-721, ERC-4337, UUPS proxies, EIP-712
- **Libraries:** OpenZeppelin v5, Solmate, Chainlink (VRF, Automation, CCIP, Price Feeds), SafeERC20
- **Security:** CEI pattern, ReentrancyGuard, invariant + fuzz testing, custom adversarial mocks, Merkle proofs, custom errors, low-level call patterns
- **Networks:** Ethereum, Sepolia, zkSync Era

---

## Connect

- **X / Twitter:** [@Sid_Hary_](https://x.com/Sid_Hary_) — sharing all the learnings in public
- **LinkedIn:** [Siddharth Choudhary](https://www.linkedin.com/in/siddharth-choudhary-797391215/)
- **Email:** sidforwork46@gmail.com

---

> *Fun fact: My real name is Siddharth Choudhary, but my public handles use "Sid Hary" (from **SID**dharth choud**HARY**) so anyone in the world can pronounce and remember it.*
