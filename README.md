[argos_public_readme.md](https://github.com/user-attachments/files/22196697/argos_public_readme.md)
# ARGOS Decision Engine

[![License: BSL 1.1](https://img.shields.io/badge/license-BSL%201.1-red)](LICENSE)

ARGOS is a **real-time decision-support system** for professional and semi-professional traders.  
It is not just a "signal bot", but a **fusion engine** that explains its reasoning, tracks performance, and delivers a professional dashboard for market monitoring.

---

<img width="1890" height="909" alt="dashboard_argos" src="https://github.com/user-attachments/assets/cb50a7c3-6b1d-4596-803a-11e82443ba33" />

---

## 🎯 About ARGOS Decision Engine

ARGOS is not a simple "signal bot" — it is a **decision intelligence framework** designed for live monitoring, analysis, and action in crypto markets.

It fuses multiple layers into a single system:
- **Technical Analytics** — market structure, momentum, volatility regimes, probability-of-move metrics
- **Consensus Logic** — multi-signal fusion with gating policies, noise control, and signal cooldown
- **Reson Overlay** — advanced probabilistic layer providing additional alpha signals and scenario drivers
- **Decision Engine** — combines all inputs into actionable stances (WAIT, ADVICE, BIG, WHALE)
- **Alerts & Logging** — configurable Telegram notifications, SQLite-based analytics, full event history
- **Professional Dashboard** — modern web interface with live charts, confidence metrics, and decision intelligence panels

ARGOS is built for **continuous monitoring**, providing not only entry/exit signals but also a **systemic view**: how confident the model is, whether consensus supports the stance, and how volatility/noise policies shape decisions.

---

## 🚀 Key Differentiators

### 1. Explainable Signals
ARGOS outputs are not limited to **BUY/SELL/WAIT**.  
Each decision includes:
- **Tier** (1–3) for importance
- **Confidence** score
- **Consensus agreement/disagreement**
- **Gate reason** (e.g. volatility high, cooldown active)
- **Reson overlay** (probabilistic alpha layer with p_move, p_up, alpha_z)

This gives traders **clarity and justification**, not just blind signals.

### 2. Fusion Decision Engine
ARGOS combines:
- **Technical analytics** (RSI, %B, z-score, p_move)
- **Consensus logic** (multi-signal fusion, adaptive weights)
- **Noise policies** (entropy, flip-rate, volatility floors, cooldowns)
- **Reson overlay** (extra-alpha probabilistic driver layer)

The result is a **decision-support framework** designed to reduce false positives and deliver more consistent signals.

### 3. Professional Dashboard
- **Main board:** assets, price, signal, confidence, tier, "why" explanation  
- **Sparklines:** mini-charts per asset for quick visual anchoring  
- **Performance view:** win-rate by tier, hit/miss ratios, outcomes  
- **Events timeline:** track recent transitions with context  
- **Drill-down modal:** inspect technical, Reson, and fusion JSON details per asset  

Clean, clear, and usable by **traders who need to act fast but also understand why**.

### 4. Performance Tracking
- SQLite logging of signals and outcomes  
- Statistics: hit rate, average duration, win rate per tier/source  
- Evaluation over 30-day rolling windows

---

## 🎯 Why ARGOS?

Most trading bots output binary buy/sell suggestions. ARGOS is designed as a **fusion engine**: it produces graded advice, contextual reasoning (tiers, consensus, gating reasons), and performance tracking over time. This makes it closer to a **real decision-support system** than a simple alert generator.

---

## 🔧 Key Features

- 🔍 **Real-time monitoring** for multiple assets (BTC, ETH, SOL, ADA by default)
- ⚡ **Configurable delay**, consensus mode, alpha mode
- 📊 **Live dashboard** with interactive charts and metrics
- 📢 **Telegram integration** with policy-based alerts
- 🧠 **Fusion of technical indicators** and probabilistic overlay (Reson)
- 📈 **Performance tracking** via SQLite (hit rate, outcomes, live open signals)
- 🛡️ **Noise policies and gating mechanisms** to reduce false signals

---

## 📊 Positioning vs. Other Frameworks

- **Not** just another trading bot
- Unlike *Freqtrade* or *Jesse*, ARGOS is **focused on decision support & explainability**, not on large-scale backtesting or automated order execution
- Unlike *Hummingbot*, ARGOS does not aim for 50+ exchange connectors — instead, it aims to be the **decision "brain"** that could even be paired with other execution frameworks
- **Unique proposition:** transparency, gating policies, noise control, and Reson overlay — features rarely seen in open-source trading software

---

## 🎯 Target Use Cases

ARGOS is designed for **research, evaluation, and private intelligence workflows**:

- **Professional traders** seeking explainable decision support
- **Research teams** evaluating multi-signal fusion strategies  
- **Quantitative analysts** requiring transparency in signal generation
- **Trading teams** needing systematic performance tracking
- **Decision support systems** integration with existing trading infrastructure

---

## 📋 System Architecture

```
Market Data → Technical Analytics → Consensus Logic → Decision Engine → Dashboard/Alerts
                     ↓                    ↓               ↓
              Engine Overlay ──→ Fusion Layer ──→ Performance Tracking
```

### Core Components:
- **Data Pipeline**: Real-time price feeds and technical calculations
- **Signal Fusion**: Multi-layer consensus with adaptive weighting
- **Gating System**: Noise filtering and volatility-aware policies
- **Decision Logic**: Tier-based stance generation with confidence metrics
- **Interface Layer**: Web dashboard and notification systems
- **Analytics Engine**: Performance tracking and outcome evaluation

---

## ⚠️ License & Usage

ARGOS is designed for **research, evaluation, and private intelligence workflows**.  
**Production or commercial deployment requires a separate license agreement.**

- **License**: Business Source License (BSL) 1.1
- **Development**: Open for research and evaluation
- **Commercial use**: Contact for licensing terms

---

## 🔗 Related Projects

- **Technical Analytics Suite** — Custom indicators and probability-of-move calculations
- **Fusion Engine Core** — Multi-signal consensus and gating logic
- **Reson Overlay Module** — Proprietary probabilistic alpha layer for enhanced signal generation

---

## 📞 Contact

For licensing inquiries, collaboration opportunities, or technical questions:
- Dacangs@hotmail.it
---

*ARGOS Decision Engine — Where signals meet intelligence.*
