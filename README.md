# 🧬 Mathematical Modeling for Cell & Bacteria Populations

This repository explores the deep interplay between mathematical ideologies and biological systems, showcasing how models like **Black-Scholes**—originally developed for option pricing—can be applied to understand tumor and bacteria population dynamics. 

Inspired by works from **Lawrence Wein**, **Sinkala & Nkalashe**, **Tarynn Witten**, and **Tamás Vicsek**, we developed simulations to model tumor growth, immune response, and bacterial behavior in predator-prey scenarios.

---

## 🔬 Overview

The **Black-Scholes equation**, a second-order PDE known for its use in financial modeling, leverages Brownian motion to depict stochastic behaviors. Interestingly, similar stochastic behaviors emerge in **tumor growth**, **immune response**, and **bacterial interactions**.

### Our work tests the interdisciplinary power of these mathematical tools by:

- Simulating tumor-immune dynamics using logistic and enhanced models
- Modeling bacterial behavior through flocking and quorum sensing systems
- Drawing parallels between biological randomness and financial stochasticity

---

## 🧪 Models Developed

### 🧠 Black-Scholes PDE
- **Core Idea**: Random walks and volatility map to cell proliferation and mutation
- **Key Insight**: Time-independent solution shows reduced growth away from the origin

### 🧬 Tumor-Immune System Models
- **Core Model (Tarynn Witten)**: Tumor vs. normal cells with logistic growth
- **Enhanced Model**:
  - Adds effector cells, IL-2, and virus dynamics
  - Tumor growth stabilizes with effector intervention
  - Normal cells dominate long-term under immune stimulation

### 🦠 Bacteria Interaction Models (by Drew Neiman)
- **Flocking Model**: Simulates predator-prey interactions and accelerated death
- **Quorum Sensing**: Bacteria deposit chemicals and communicate for survival
  - Emergent clustering and death rates match observed biological behaviors

---

## 📉 Results & Insights

- Tumor cells exhibit logistic and spatial decay behaviors analogous to stock prices
- Effector cells and IL-2 create stabilizing feedback, halting unchecked tumor growth
- Bacterial models show consistent trends in mortality and communication-driven adaptation
- Time-independent GBM solution: Growth rates decay as distance from the origin increases

---

## 📊 Visualizations

Check the [`graphs/`](./graphs) folder for visual outputs of each model:

- Tumor vs. Normal cell growth
- Predator-prey bacterial interactions
- Quorum-sensing based clustering
- GBM time-independent PDE behavior

---

## 📚 Citations & Inspiration

- Lawrence Wein – GBM cytotoxic treatment model
- Sinkala & Nkalashe – Analytical transformation of Black-Scholes ↔ GBM
- Tarynn Witten – Tumor-immune logistic interaction models
- Tamás Vicsek – Predator-prey flocking models of bacteria

---

## 🧠 Contributors

- **Samen Hossain** – Tumor & immune system modeling, time-independent GBM derivation  
- **Drew Neiman** – Flocking and quorum sensing bacterial interaction models

---

## 💬 Feedback

We’re excited to share this interdisciplinary bridge between quantitative finance and biology!  
Feedback, forks, and contributions are welcome 🙌

---

