# 📘 Analyzing the E-Waste Awareness
### A Data-Driven Behavioral Study Using Theory of Planned Behavior (TPB)

## 🎯 Overview
This project investigates consumer behavior and awareness regarding electronic waste (e-waste) management using the **Theory of Planned Behavior (TPB)**.  
It identifies the psychological, social, and practical factors influencing recycling intentions and actions among urban Indian consumers.

## 🧩 Objective
- Develop a behavioral model explaining e-waste recycling intentions and behavior.
- Collect and analyze survey data from 512 participants.
- Evaluate the TPB constructs (Attitude, Subjective Norms, Perceived Behavioral Control) using **Structural Equation Modeling (SEM)** in Python.

## ⚙️ Technologies Used
- **Python 3.x**
- Libraries: `pandas`, `numpy`, `matplotlib`, `semopy`
- Data Analysis: Structural Equation Modeling (SEM)
- Document: LaTeX / MS Word converted to PDF

## 📊 Dataset
A structured survey consisting of 40 items across six sections:
- Demographics
- Attitude toward e-waste recycling
- Subjective norms
- Perceived behavioral control
- Behavioral intention
- Actual recycling behavior

## 🧠 Key Findings
- Perceived Behavioral Control (PBC) was the strongest predictor of recycling intention (β = 0.47, *p* < 0.001).
- Behavioral Intention significantly influenced actual behavior (β = 0.35, *p* < 0.01).
- Education level moderated the intention-behavior relationship.
- Identified three behavioral clusters:
  - Convenience-Driven Recyclers (42%)
  - Environmentally Committed (35%)
  - Indifferent Non-Recyclers (23%)

## 📈 Results Summary
| Metric | Value | Interpretation |
|--------|-------|----------------|
| CFI | 0.947 | Excellent Fit |
| RMSEA | 0.048 | Excellent Fit |
| SRMR | 0.041 | Excellent Fit |

## 📂 Project Structure
├── CPS FRONT 1.pdf
├── data/ # survey or sample data
├── code/ # Python analysis scripts
├── requirements.txt
└── README.md

## 🧩 Future Scope

Longitudinal tracking of behavioral change.

IoT-based e-waste collection systems.

Integration with circular economy frameworks.

