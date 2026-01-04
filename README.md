# Simulation-Based Decision Analytics & Risk Modeling  
**Monte Carlo Simulation · Stochastic Systems · Uncertainty Quantification**

---

## Overview

This project applies **simulation-based decision analytics** to evaluate complex systems under uncertainty. Using **Monte Carlo simulation and probabilistic modeling**, the notebook analyzes multiple decision scenarios where outcomes cannot be determined analytically due to randomness, interdependencies, and stochastic behavior.

The focus is on **risk-aware decision-making**, demonstrating how simulation can be used to compare alternative policies, quantify uncertainty, and support robust operational decisions when closed-form optimization is infeasible.

---

## Application Context

Many real-world decision problems involve:
- Random demand or arrivals
- Probabilistic outcomes
- Non-deterministic system dynamics
- Competing policies with uncertain performance

Examples include:
- Service systems (queues, call centers)
- Inventory and capacity planning
- Operational risk assessment
- Policy evaluation under uncertainty

This project demonstrates how **simulation replaces deterministic optimization** when system complexity or randomness prevents exact solutions.

---

## Problem Framing

The assignment models decision problems where:
- Inputs are random variables rather than fixed parameters
- Performance metrics must be estimated statistically
- Decisions are evaluated based on **expected outcomes and risk profiles**

Core analytical questions include:
- How does system performance vary across scenarios?
- Which decision policy performs best on average?
- What is the variability and risk associated with each policy?
- How sensitive are outcomes to stochastic assumptions?

---

## Methodology

### 1. Stochastic Modeling
- Definition of random variables representing system uncertainty
- Sampling from probability distributions
- Modeling event-driven system behavior

---

### 2. Monte Carlo Simulation
- Repeated simulation runs to approximate outcome distributions
- Estimation of expected values, variances, and percentiles
- Law of Large Numbers applied to stabilize estimates

Simulation is used to approximate performance metrics that cannot be computed analytically.

---

### 3. Policy Evaluation
- Comparison of multiple decision rules or system configurations
- Performance assessment under identical random conditions
- Identification of dominant or risk-efficient policies

This allows fair, apples-to-apples comparison of alternatives.

---

### 4. Risk & Variability Analysis
- Distributional analysis of outcomes
- Identification of worst-case and tail-risk behavior
- Evaluation beyond mean performance

Decisions are evaluated not only on expected value but also on **risk exposure**.

---

## Analytical Techniques Used

- Monte Carlo simulation
- Probabilistic modeling
- Scenario analysis
- Risk-aware decision comparison
- Statistical estimation under uncertainty

---

## Key Technical Skills Demonstrated

### Decision Analytics & Simulation
- Stochastic system modeling
- Simulation-based optimization intuition
- Risk analysis and uncertainty quantification
- Policy evaluation under randomness

### Programming & Analytics
- **Python**
- Jupyter Notebook
- Numerical simulation
- Structured experimental design

---

## Results & Insights

- Quantified expected system performance under different policies
- Demonstrated how variability influences decision quality
- Identified trade-offs between average performance and risk
- Showed why deterministic reasoning can fail under uncertainty

The results illustrate how **simulation-driven analysis leads to more robust decisions** than point-estimate optimization.

---

## Project Structure

```text
├── Assignment_3_Helia_Mahmoodzadeh_261224416_Work_Sheet_FV.ipynb
├── README.md
