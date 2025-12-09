# MATH 789 - BNPL Viability Simulation

This repository contains a Jupyter Notebook (`sim_f3n.ipynb`) that analyzes the financial durability of Buy Now, Pay Later (BNPL) firms using a Monte Carlo simulation framework. The project stress-tests the Profit & Loss (P&L) mechanics of BNPL platforms to evaluate their solvency across different growth stages and economic environments.

## Project Description

The simulation models the unit economics of a BNPL platform by randomizing key risk drivers, including default rates, cost of funding, and collection recovery rates. It projects monthly financial performance to estimate the "Months to Insolvency" (cash runway) for companies operating under varying constraints.

The model evaluates the interaction between two primary variables:
* **User Scale:** Ranging from early-stage startups (10k users) to mature market leaders (5M+ users).
* **Economic Scenarios:** Ranging from a stable baseline economy to a severe recession (calibrated to 2008-style credit contraction data).

## Key Features

* **Stochastic P&L Modeling:** Simulates monthly revenue (Merchant Decision Rates, Late Fees) against variable costs (CAC, OpEx, Funding Costs) and credit losses.
* **Scenario Analysis:** Runs iterations across a matrix of user scales and macroeconomic conditions to identify breaking points in the business model.
* **Visualization:** Generates an insolvency heatmap to visualize the relationship between scale, economic stress, and corporate survival time.
