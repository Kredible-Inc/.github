# 🌍 Builder Score: Dynamic P2P Lending & Web3 Credit Infrastructure

## 🚫 The Problem

> In **Latin America**, millions of people remain excluded from the financial system. As of 2021, **27% of adults in Latin America and the Caribbean—over 160 million people—still do not have access to a bank account** (World Bank Global Findex). Many lack access to traditional banking, credit history, or official documentation—barriers that prevent them from obtaining fair loans or building financial security. Even in the digital age, most decentralized lending platforms require users to **overcollateralize** loans (110%–150%+), making credit inaccessible to those who need it most. This perpetuates a cycle where opportunity is reserved for the already privileged, not for the hardworking individuals striving for a better future.

---

## 💡 The Solution: Lending Platform Powered by Builder Score

At the heart of our project is a next-generation **P2P lending platform** that redefines access to credit in Web3. Unlike traditional DeFi lending, where everyone faces the same high collateral requirements, our platform uses the **Builder Score**—a Web3-native credit score based on on-chain behavior—to dynamically adjust the Loan-to-Value (LTV) ratio for each user.

- **Borrowers** with a strong Builder Score can access loans with **significantly lower collateral requirements** (as low as 55%), making credit accessible to more people.
- **Lenders** benefit from transparent, on-chain risk metrics and can offer competitive rates while maintaining protection.

Every successful repayment improves a user's Builder Score, unlocking even better terms for future loans. This creates a positive feedback loop of trust and inclusion.

---

## 🏦 The Lending Platform: How It Works

Our P2P lending platform is more than a demo—it's a fully functional, real-world application that demonstrates the power of decentralized, reputation-based finance:

- **Dynamic Collateral:** The required collateral (LTV) for each loan is calculated in real time based on the borrower's Builder Score.
- **Transparent Credit Scoring:** All scoring logic is on-chain and verifiable, ensuring fairness and trust.
- **Reputation Growth:** Repay loans on time to improve your score and unlock better borrowing terms.
- **Open Integration:** The platform is built to showcase how any DeFi protocol can integrate our credit scoring API and offer dynamic, merit-based lending.

> The lending platform is both a flagship product and a reference implementation for the Builder Score infrastructure.

---

## 🛠️ Credit Scoring Infrastructure

Supporting the lending platform is our robust **credit scoring infrastructure**:

- **Builder Score API:** Calculates and exposes each user’s score based on on-chain financial behavior (repayments, wallet activity, transaction history, etc.).
- **Easy Integration:** Any DeFi or lending protocol can use our API to enrich their risk models and offer personalized lending terms.
- **Data-Driven:** The more protocols share loan outcome data, the more accurate and inclusive the scoring becomes.

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
- **Lower collateral:** Your trust and history unlock better terms.
- **Reputation portability:** Your score follows you across platforms.
- **Real-time visibility:** Track your credit evolution and borrowing power.

**For Lenders/Platforms:**
- **Score transparency:** Access to on-chain, verifiable credit metrics.
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
   - Manages P2P lending, enforces **dynamic LTV ratios per user** based on Builder Score.
2. **Credit History Contract:**
   - Records loan outcomes (repayments, defaults, late payments), calculates Builder Score, and updates allowed LTV in the lending contract.

All logic is on-chain, transparent, and interoperable for any protocol integrating our scoring API.

---

## 🏗️ Technical Architecture

**Lending Platform & Frontend:**
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

- **Dynamic, reputation-based P2P lending**: Real loans, real users, real impact
- **Merit-based, decentralized credit scoring** for Web3
- **API-first**: Easy integration for any DeFi platform
- **Financial inclusion**: Unlocks credit for the unbanked and underbanked
- **Transparent, on-chain logic**: Trustless and verifiable

---

> **Builder Score**: The future of lending is trust, not wealth. Experience dynamic, inclusive finance—powered by your reputation.