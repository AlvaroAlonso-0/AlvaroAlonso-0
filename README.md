<div align="center">

# Álvaro Alonso

**Lead Engineer · Intelligence Layer at [Sail](https://sail.money)**
*Quantitative DeFi · Risk monitoring · Cross-chain yield optimization*

Madrid, Spain · open to remote / EU

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/alvaro-alonso-miguel)
[![Portfolio](https://img.shields.io/badge/-Portfolio-111?style=for-the-badge&logo=safari&logoColor=white)](https://alvaroalonso-0.github.io)
[![Email](https://img.shields.io/badge/-Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:alonso.miguel.alvaro1@gmail.com)

<br/>

![](https://img.shields.io/badge/routed-~$650M-4cc9b0?style=flat-square)
![](https://img.shields.io/badge/users-~200-5a6772?style=flat-square)
![](https://img.shields.io/badge/TVL-~$600k-5a6772?style=flat-square)
![](https://img.shields.io/badge/papers_+_reports-2_+_2-5a6772?style=flat-square)
![](https://img.shields.io/badge/Q4_2025_APY-8.91%25-4cc9b0?style=flat-square)
![](https://img.shields.io/badge/Q1_2026_USD_APY-6.06%25-4cc9b0?style=flat-square)

</div>

---

### What I work on

I founded the intelligence layer at **[Sail](https://sail.money)** — a DeFi yield-optimization protocol on Base and Arbitrum — from a blank page. Two production systems, both designed and implemented end-to-end:

- **Cross-chain optimization engine** — formalized portfolio allocation as a constrained Markov Decision Process. Simulated annealing optimizer with Metropolis-Hastings acceptance for the non-convex objective, plus a CNN meta-controller predicting hyperparameters from APY/TVL history (3-5× search-space reduction). Energy-aware cost model covering execution, slippage, and TVL-dependent price impact.
- **Sonar (risk monitoring)** — z-score anomaly detection over multi-horizon baselines (1d / 7d / 30d), dual-mode SPIKE/TREND scoring (80/20 vs 40/60 weighting), tier-based execution cycles (1h / 2h / 6h), financial-inertia mechanism that cut unnecessary portfolio churn by 43 %.

I also defined the database schema, built the first user-facing UIs, and represented the intelligence layer to venture investors and the CEO during fundraising and roadmap discussions.

The full mathematical framework — formulation, proofs, and empirical validation — is documented in two public research papers I authored.

### Production validation

> First six months in production: **~$650M of volume routed** for **~200 users** at **~$600k TVL**.

| Quarter | Mean APY | vs. best static | vs. T-Bills | Scope |
|---|---|---|---|---|
| **Q4 2025** | `8.91 %` | +5.43 % | +123.87 % | 20 sources, single-currency |
| **Q1 2026** | `6.06 %` (USD) | — | +44.3 % | 32 sources, multi-currency |

All returns net of every fee in the cost model.

### Sonar — defensive wins · Q1 2026

Sonar suspended user exposure ahead of two publicly confirmed exploits — detection happened *before* public confirmation in both cases:

- **Moonwell oracle exploit** · Feb 15, 2026 — $1.78M bad debt, 181 borrowers harmed.
- **Resolv Protocol exploit** · Mar 22, 2026 — ~$80M minted via a compromised AWS KMS key, ~$25M extracted.

### Publications

All four are sole-author work.

- 📄 [Cross-Chain Optimization Engine V2 — Smart Spike Framework](https://docsend.com/view/ucrfnewiuy9t2fwm) · *paper · Jan 2026*
- 📄 [Cross-Chain Optimization Engine V1](https://t.co/x2IPJbcumZ) · *paper · Oct 2025*
- 📊 [Sail Agent Performance Analysis — Q4 2025](https://t.co/tafqaH8M27) · *report · Jan 2026*
- 📊 [Sail Agent Performance Analysis — Q1 2026](https://docsend.com/view/6xp4wmeb8nc7rxha) · *report · Apr 2026*

---

### Pinned

| | | |
|---|---|---|
| **[optcg](https://github.com/AlvaroAlonso-0/optcg)** | Investment portfolio tracker | Python · SQLite · Textual TUI · ~6.8k LOC |
| **[Poker Vision](https://github.com/AlvaroAlonso-0/PokerHandsRecongition)** | VGG16 card recognition + Monte Carlo equity sim | Python · PyTorch · OpenCV |
| **[Figbot](https://github.com/AlvaroAlonso-0/Figbot)** | Multi-agent Twitch moderation bot | Java |

### Education

**B.S. Computer Science — Universidad Politécnica de Madrid · 2018 – 2023**
GPA `8.56 / 10`. *Matrículas de Honor* in Operating Systems, Compilers, Semantic Web & Knowledge Graphs, Art of Programming, Prolog, Programming Project, Data Center Project.

### Stack

```
Math / ML   NumPy · SciPy · scikit-learn · PyTorch · CNNs ·
            simulated annealing · Monte Carlo · time-series interpolation
Code        Python · Java · C · C# · TypeScript · Bash · SQL
Backend     FastAPI · MongoDB · .NET · Next.js / React
```

<div align="center"><sub>Languages: Spanish (native) · English (C1) · French (basic)</sub></div>
