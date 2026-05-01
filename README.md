<h1 align="center">Hi, I'm Álvaro Alonso 👋</h1>

<p align="center">
  <strong>Lead Engineer · Intelligence Layer at <a href="https://sail.money">Sail</a></strong><br/>
  Quantitative DeFi · Risk monitoring · Cross-chain yield optimization<br/>
  Madrid, Spain · open to remote / EU
</p>

<p align="center">
  <a href="https://linkedin.com/in/alvaro-alonso-miguel"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://alvaroalonso-0.github.io"><img src="https://img.shields.io/badge/Portfolio-111?style=flat&logo=safari&logoColor=white" alt="Portfolio"/></a>
  <a href="mailto:alonso.miguel.alvaro1@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

---

### What I work on

I design and implement quantitative systems where most of the work is mathematics, and the code is the bridge that takes the math to production. Lead engineer at **[Sail](https://sail.money)**, where I founded the intelligence layer from a blank page:

- **Cross-chain optimization engine** — formalized portfolio allocation as a constrained Markov Decision Process. Simulated annealing optimizer with Metropolis-Hastings acceptance for the non-convex objective, plus a CNN meta-controller predicting hyperparameters from APY/TVL history (3-5× search-space reduction). Energy-aware cost model covering execution, slippage, and TVL-dependent price impact.
- **Sonar (risk monitoring)** — z-score anomaly detection over multi-horizon baselines (1d / 7d / 30d), dual-mode SPIKE/TREND scoring (80/20 vs 40/60 weighting), tier-based execution cycles (1h / 2h / 6h), and a financial-inertia mechanism that cut unnecessary portfolio churn by 43 %.

The full mathematical framework — formulation, proofs, and empirical validation — is documented in two public research papers I authored.

### Production validation

> First six months in production: **~$650M of volume routed for ~200 users at ~$600k TVL.**

| Quarter | Mean APY | vs. best static | vs. T-Bills | Notes |
|---|---|---|---|---|
| Q4 2025 | **8.91 %** | +5.43 % | +123.87 % | 20 sources, single-currency |
| Q1 2026 | **6.06 %** | — | +44.3 % | 32 sources, multi-currency |

All returns net of every fee in the cost model.

### Sonar — defensive wins (Q1 2026)

Sonar suspended user exposure ahead of two publicly confirmed exploits in Q1 2026 — detection happened *before* public confirmation in both cases:

- **Moonwell oracle exploit** — Feb 15, 2026. $1.78M bad debt, 181 borrowers harmed.
- **Resolv Protocol exploit** — Mar 22, 2026. ~$80M minted via a compromised AWS KMS key, ~$25M extracted.

### Selected publications

- *Cross-Chain Optimization Engine V2 — Smart Spike Framework* (Jan 2026)
- *Cross-Chain Optimization Engine V1* (Oct 2025)
- *Sail Agent Performance Analysis — Q4 2025* (sole author, Jan 2026)
- *Sail Agent Performance Analysis — Q1 2026* (sole author, Apr 2026)

---

### Pinned

📊 **[optcg](https://github.com/AlvaroAlonso-0/optcg)** — investment portfolio tracker (~6.8k LOC). Python CLI + Textual TUI, SQLite, live price-scraping pipeline with Cloudflare-aware cookie extraction across Chrome / Arc / Brave / Edge on macOS + Windows, offline HTML dashboard, iCloud sync, P&L logic.

🃏 **[Poker Vision](https://github.com/AlvaroAlonso-0/PokerHandsRecongition)** — VGG16-based card recognition + Monte Carlo equity simulation; documented in a university publication.

🤖 **[Figbot](https://github.com/AlvaroAlonso-0/Figbot)** — Java multi-agent system for Twitch chat moderation.

### Education

**B.S. Computer Science — Universidad Politécnica de Madrid · 2018 – 2023**
GPA 8.56 / 10. *Matrículas de Honor* in Operating Systems, Compilers, Semantic Web & Knowledge Graphs, Art of Programming, Prolog, Programming Project, Data Center Project.

### Stack

```
Math / ML — NumPy · SciPy · scikit-learn · PyTorch · CNNs ·
            simulated annealing · Monte Carlo · time-series interpolation
Code      — Python · Java · C · C# · TypeScript · Bash · SQL
Backend   — FastAPI · MongoDB · .NET · Next.js / React
```

<br/>
<sub>Languages: Spanish (native) · English (C1) · French (basic)</sub>
