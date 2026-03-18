# 🏛️ Congressional Alpha
### *Deep Learning for Legislative-Financial Analysis*

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://www.python.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.0+-orange.svg)](https://tensorflow.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Bologna Business School](https://img.shields.io/badge/Institution-Bologna%20Business%20School-red.svg)](https://www.bbs.edu/)

---

## 🎯 Project Overview
This repository contains a sophisticated data science pipeline designed to analyze the intersection of **U.S. Congressional trading activity** and **legislative processes**. The project investigates whether legislative insights and committee involvement can be mapped to stock market performance to generate **"Alpha."**

> **Academic Context:** Developed as a capstone for the *Neural Networks and Deep Learning* course at **Bologna Business School (BBS)**.

---

## 🛠️ Tech Stack
* **Deep Learning:** `TensorFlow`, `Keras`, `MLPRegressor`
* **Optimization:** `Optuna`, `Skorch`
* **Data Science:** `Pandas`, `NumPy`, `Scikit-Learn`
* **Visualizations:** `Seaborn`, `Matplotlib`

---

## 🚀 Key Features
* **End-to-End Pipeline:** Raw data ingestion to predictive modeling.
* **Identity Bridging Algorithm:** Custom name-cleaning system to link **LegiScan** and **Quiver Quantitative** data.
* **Temporal Filtering:** Advanced logic to align trades with active congressional sessions (2021–2026), preventing look-ahead bias.
* **Confidence Scoring:** Data-driven metrics reflecting model certainty.

---

## 📊 Visualizations
*(Tips: Ta en skärmdump på din snyggaste graf från notebooken och lägg in den här!)*
![Analysis Chart](<img width="838" height="477" alt="Skärmavbild 2026-03-18 kl  11 18 26" src="https://github.com/user-attachments/assets/0a7f86b3-dbf9-4171-8cd6-ea914c831e95" />)

---

## 🧠 Modeling Architecture
The analysis utilizes a modern machine learning stack to handle noisy financial data:
1.  **Neural Networks:** Multi-layer architectures with Dropout regularization.
2.  **Feature Engineering:** NLP-based keyword extraction for sector classification.
3.  **Hyperparameter Tuning:** Automated search via Optuna for max accuracy.

---

## 👤 Lead Developer
**[Hugo Dahlquist]** *Master in Data Science & AI Student at Bologna Business School*
