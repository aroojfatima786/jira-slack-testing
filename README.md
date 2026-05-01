<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:111827,45:1F2937,100:F59E0B&height=200&section=header&text=Auction%20Platform&fontSize=42&fontColor=FFFFFF&animation=twinkling&fontAlignY=35&desc=Multi-Chain%20Auctions%20%7C%20Bitcoin%20%7C%20Ethereum%20%7C%20Marketplace&descAlignY=58&descSize=15" width="100%" />
</p>

<p align="center">
  <strong>Multi-chain auction system with unified bidding experience</strong><br/>
  <sub>Next.js · NestJS · MongoDB · Bitcoin · Ethereum</sub>
</p>

---

## 🚀 Project Overview

Auction Platform is a **full-stack auction system** supporting both:

- **Off-chain auctions** (platform-managed bidding)
- **On-chain auctions** (Bitcoin & Ethereum flows)

The goal is to provide a **consistent bidding experience** across different auction types, while maintaining a clean and modular architecture.

---

## ⚙️ Core Features

### 🔐 Authentication
- JWT-based authentication
- Secure login flow with optional OTP handling
- Backend uses bcrypt + token-based sessions

---

### 🧠 Off-Chain Auction
- Platform-controlled bidding flow
- Simplified auction lifecycle handling
- API-driven structure for auction state

---

### ₿ Bitcoin Auction Flow
- PSBT-based transaction structure
- Wallet-oriented bidding flow
- End-to-end flow represented with mocked responses

---

### ⛓️ Ethereum Auctions

#### Standard Auction
- Contract interaction flow via backend services
- Transaction journaling and API structure

#### Ranked Auction
- Position-based bidding system
- Simplified ranked bid logic with controlled state handling

---

### 🛒 Marketplace

- Marketplace browsing for listed items
- Item detail interaction with authentication
- Buy-interest submission flow
- Backend APIs for listing and interest tracking
- Seller onboarding represented via navigation entry

---

## 🧩 Tech Stack

### Frontend
- Next.js (App Router)
- React + TypeScript
- Tailwind CSS
- Wagmi / Viem / RainbowKit

### Backend
- NestJS (TypeScript)
- MongoDB + Mongoose
- Modular controller/service architecture

### Blockchain
- Bitcoin (PSBT-based flow)
- Ethereum (contract interaction via ethers v6)

---

## 📸 Demo & Screenshots

Add visuals here:

- Auction Dashboard  
- Off-chain Auction Flow  
- Bitcoin Flow  
- Ethereum Standard Auction  
- Ethereum Ranked Auction  
- Marketplace  

---

## 👨‍💻 Role & Challenges

- Implemented **core auction flows** across off-chain and on-chain systems  
- Built **ranked bidding logic** with structured ordering  
- Designed **Bitcoin PSBT-based transaction flow**  
- Developed **marketplace browsing and buy-interest system**  
- Structured **backend services with modular architecture**  
- Integrated frontend and backend for consistent UX  
- Simplified complex systems into **clean portfolio-ready flows**  

---

## 🔒 NDA Notice

**Code is partially simplified because the full implementation is private due to client NDA.**  
This repository highlights system design, feature structure, and development work.

---

## ▶️ How to Run

```bash
# Frontend
cd frontend
npm install
npm run dev

# Backend
cd Backend
npm install
npm run start:dev
