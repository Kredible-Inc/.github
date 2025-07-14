# 🌍 Builder Score: Web3 Credit Infrastructure for Financial Inclusion

## 🚫 The Problem

> **1.7+ billion people** are excluded from the financial system due to lack of documentation or banking history. In Web3, decentralized lending platforms require users to **overcollateralize** loans (110%–150%+), blocking access to credit for those who need it most. This system favors wealth, not trust.

---

## 💡 The Solution

**Builder Score** is a Web3-native credit score based on what users **do**, not what they **own**. By analyzing on-chain behavior—loan repayment, wallet activity, and more—we enable users with strong reputations to access loans with **lower collateral requirements** (down to **55%**), increasing financial inclusion while protecting lenders.

---

## 🛠️ Scope

We are building a **credit scoring API** that calculates and exposes each user’s Builder Score from on-chain financial behavior.

To demonstrate this, we will launch a **lightweight P2P lending demo platform** where:

- Lenders offer funds and earn interest.
- Borrowers receive loans with dynamic collateral based on their score.
- Each successful repayment improves the user’s score, reducing future collateral needs.

> Our core product is the **credit score infrastructure**—not the lending itself. Other DeFi platforms can integrate our API to enrich their risk models.

---

## 💸 Revenue Model

- **Freemium API access:** Free tier (e.g., 100 API calls), then metered billing.
- **Data-sharing discount:** Protocols sharing loan outcome data get discounted access.

| **Platform Fee** | **0.5%** per loan (ultra-low) |
|------------------|-------------------------------|
| **Lender Interest** | **6%–9% APR** (score-dependent) |

---

## 🎯 User Benefits

**For Borrowers:**
- **Reputation portability:** Your score follows you across platforms.
- **Lower collateral:** Proven trust unlocks better terms.
- **Real-time visibility:** Track your credit evolution.

**For Lenders/Platforms:**
- **Score transparency:** Easy access to creditworthiness metrics.
- **User profiling:**
  - Volume moved
  - Activity frequency
  - Wallet age
  - Swap/transaction history

> More visibility and credibility means better lending options for all.

---

## 🌟 Stellar Integration

We build on **Soroban** (Stellar’s smart contract platform) with two core contracts:

1. **Lending Contract:**
   - Manages P2P lending, enforces dynamic LTV ratios per user based on Builder Score.
2. **Credit History Contract:**
   - Records loan outcomes (repayments, defaults, late payments), calculates Builder Score, and updates allowed LTV in the lending contract.

All logic is on-chain, transparent, and interoperable for any protocol integrating our scoring API.

---

## 🏗️ Technical Architecture

**dApp & Frontend:**
- NextJS
- Stellar-SDK
- Stellar Wallet-Kit
- Passkey-Kit

**Backend (API):**
- NestJS
- Firebase
- Stellar-SDK

---

## 🚀 Unique Value Proposition

- **Merit-based, decentralized credit scoring** for Web3
- **API-first**: Easy integration for any DeFi platform
- **Financial inclusion**: Unlocks credit for the unbanked and underbanked
- **Transparent, on-chain logic**: Trustless and verifiable

---

> **Builder Score**: Powering the next generation of inclusive, trust-based finance on Web3.