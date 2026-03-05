# 🕹️ ClawBags: Gamified Token Launchpad on Solana
ca :

![Network](https://img.shields.io/badge/Network-Solana-blueviolet?style=for-the-badge)
![Build](https://img.shields.io/badge/Build-Anchor--Rust-orange?style=for-the-badge)

**ClawBags** is the first decentralized launchpad that replaces boring "click-to-buy" mechanics with a **Provably Fair Open Claw** system. Built on Solana, we ensure every token launch is an interactive experience, protected from snipers by "Proof of Gameplay."

---

## 🛠️ How It Works
1. **The Bonding Curve:** Every project starts on a mathematical price curve for fair discovery.
2. **The Open Claw:** Users use credits to "claw" token allocations from the machine. 
3. **The Migration:** Once the cap is hit, liquidity is automatically moved to Raydium/Jupiter and LP tokens are burned.

## 💻 Tech Stack
- **Smart Contracts:** Anchor Framework (Rust)
- **Randomness:** Switchboard VRF (On-chain verifiability)
- **Frontend:** Next.js 14 + Three.js (3D Claw Interface)

## 🚀 Quick Start
```bash
git clone [https://github.com/your-username/clawbags.git](https://github.com/your-username/clawbags.git)
cd clawbags
anchor build
npm install && npm run dev
