# two-way-arbitrage-stake-calculator

A lightweight **JavaScript / TypeScript** calculator for **two-outcome betting arbitrage**, supporting equal-profit, weighted-profit, and zero-loss stake distributions using a fixed total bankroll.

---

## 🧮 Overview

This project computes optimal stake allocations for **two opposing outcomes** (e.g. True/False, Yes/No, Home/Away) given:

- decimal odds for both outcomes
- a total amount of money to be staked in full

It dynamically calculates multiple arbitrage strategies while ensuring that **no outcome results in a loss** (subject to rounding).

---

## ✨ Features

- Accepts **two opposing decimal odds**
- Uses a **single total bankroll**
- Calculates stake distributions for:
  - **1:1** – equal profit on both outcomes
  - **2:1** – profit weighted toward outcome A
  - **1:2** – profit weighted toward outcome B
  - **1:0** – profit on A, break-even on B
  - **0:1** – profit on B, break-even on A
- Displays:
  - stake per outcome
  - profit if outcome A wins
  - profit if outcome B wins
  - arbitrage validity after real-world rounding
- No external dependencies
- Runs directly in the browser

---
