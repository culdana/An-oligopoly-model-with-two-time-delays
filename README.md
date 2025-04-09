# An-oligopoly-model-with-two-time-delays
# Bifurcation & Lyapunov Analysis in Delayed Multi-Agent System

This Mathematica project analyzes a multi-agent system with delayed dynamics using:
- Bifurcation diagrams
- Lyapunov exponents
- Symbolic Jacobian computation

## 📊 System Description

The system models `nfirme` interacting agents with two delay terms (`T0` and `T1`) and nonlinear feedback.

The main evolution function is defined in `Fun[q_]`, which updates the system state using parameterized nonlinear equations.

## 🔧 Parameters

Parameters such as `a0`, `a1`, `be`, `de`, `T0`, `T1`, `nfirme`, etc., are defined at the beginning of the notebook (or in `params.m`).

You can adjust them to explore different behaviors.

## ▶️ How to Run

1. Open `main.nb` in Wolfram Mathematica.
2. Run all cells.
3. Two visualizations will be produced:
   - A bifurcation diagram (q₀ vs α)
   - A Lyapunov exponent plot

## 📁 File Overview

- `main.nb` – Main Mathematica notebook with full code and plots
- `params.m` – Optional parameter definitions, useful for clarity and modularity
- `images/` – Folder for saving generated plots (optional)

## 📜 License

This project is licensed under the MIT License. See `LICENSE` for more info.
