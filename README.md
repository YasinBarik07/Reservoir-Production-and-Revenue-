# Reservoir-Production-and-Revenue-

# 🛢 Oilfield Asset Simulator

A simple Python-based financial and production simulator for modelling oil well performance over time. This project estimates production decline, revenue, operating costs, and cumulative profit for multiple wells over a chosen time period.

---

## 📌 Project Overview

This program simulates the economics of oil production wells using an exponential decline model. It calculates:

- Daily oil production decline over time
- Monthly revenue from oil sales
- Operating expenses per well
- Cumulative profit or loss
- Break-even trends (visualised)

The model allows users to compare multiple wells and assess profitability under different conditions.

---

## ⚙️ Features

- 📉 Exponential production decline model
- 💰 Monthly revenue and cost calculation
- 📊 Cumulative profit tracking per well
- 🧮 Multi-well comparison
- 📈 Visual graphs using Matplotlib
- ⏳ Adjustable simulation length and financial inputs

---

## 🧪 Inputs Required

When running the program, the user is prompted for:

- Oil market price ($/barrel)
- Initial drilling cost per well ($)
- Monthly operating cost per well ($)
- Simulation length (months)
- Number of wells
- Initial production per well (barrels/day)
- Monthly decline rate (decimal form, e.g. 0.08)

---

## 📊 Outputs

The program generates two main graphs:

1. **Production Output Graph**
   - Shows how oil production decreases over time for each well

2. **Cumulative Profit Graph**
   - Shows net cash flow over time
   - Includes break-even line at $0

It also prints confirmation when analysis is complete.

---

## 🧠 Model Assumptions

- Production follows an exponential decline model:
  \[
  q(t) = q_0 e^{-dt}
  \]
- Oil price remains constant throughout the simulation
- Operating costs are fixed per month per well
- No taxes, royalties, or inflation are included
- Setup cost is applied at the start of each well

---

## 🛠 Technologies Used

- Python 3
- NumPy
- Matplotlib

---

## 🚀 How to Run

1. Install dependencies:
```bash
pip install numpy matplotlib
