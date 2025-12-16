# Profit Weighted Arbitrage Calculator

A browser-based **two-way profit-weighted arbitrage calculator** that helps you size stakes across opposing outcomes while visualizing profit symmetry, asymmetry, and risk.

Live, dependency-free, and designed for **real execution scenarios** (odds boosts, stake limits, manual overrides).

---

## 🔗 Live Demo

> `https://wesharethisplace.github.io/profit-weighted-arbitrage-calculator/`

---

## 🧮 What this tool does

Given:
- **Two opposing decimal odds** (True / False)
- A **total stake** (or manually edited stakes)

The calculator continuously recomputes stake distributions and resulting profits for multiple arbitrage strategies — **without breaking focus while typing**.

---

## 📊 Scenarios Explained

| Scenario | Meaning |
|--------|--------|
| **WIN:WIN** | Equal profit regardless of outcome (classic arbitrage) |
| **WIN:HALF-WIN** | Profit biased toward True |
| **HALF-WIN:WIN** | Profit biased toward False |
| **WIN:EVEN** | Profit on True, break-even on False |
| **EVEN:WIN** | Break-even on True, profit on False |
| **MANUAL** | Fully custom stakes with automatic outcome labeling |

The **MANUAL** row dynamically labels itself as:
- `WIN:WIN`
- `WIN:LOSS`
- `LOSS:WIN`
- `LOSS:LOSS`
- `EVEN:*`

based on the resulting profit of each outcome.

---

## ✨ Key Features

- All **Stake True / Stake False cells are editable**
- Editing **any stake**:
  - Recalculates the paired stake for that scenario
  - Updates the **total stake**
  - Recomputes all dependent scenarios
- Editing **Total stake** recalculates all non-manual scenarios
- Manual row is fully independent
- Profit cells show:
  - **Green +** for profit
  - **Red −** for loss
- No focus loss while typing
- Decimal typing supported (e.g. `0.20`) even with `step=1`
- Zero dependencies
- Runs fully in the browser

---

## 🧠 Intended Use Cases

- Odds boosts & promotions
- Stake-limit-aware arbitrage
- Profit skew analysis
- Manual hedge verification
- Educational exploration of arbitrage math
- Lightweight internal tooling

---

## ⚙️ Tech Stack

- Vanilla **HTML / CSS / JavaScript**
- No frameworks
- No build step
- No tracking or external calls

---

## ⚠️ Disclaimer

This tool is provided for **educational and analytical purposes only**.

It does **not** place bets, connect to bookmakers, or encourage gambling activity.  
Always verify bookmaker terms, settlement rules, and stake limits before placing real bets.

---

## 📄 License

MIT
