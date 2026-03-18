Congressional Alpha: Deep Learning for Legislative-Financial Analysis
This repository contains a sophisticated data science pipeline designed to analyze the intersection of U.S. Congressional trading activity and legislative processes. The goal is to investigate whether legislative insights and committee involvement can be mapped to stock market performance to generate "Alpha."

This project was developed as a capstone for the Neural Networks and Deep Learning course at Bologna Business School (BBS).

Project Overview
The core of this research focuses on bridging the gap between political activity and financial markets. By integrating legislative records with individual trading data, the model identifies patterns and "Insider Influence Signals" that correlate with market-beating returns.

Key Features
End-to-End Pipeline: A complete workflow from raw data ingestion to predictive modeling and performance evaluation.

Identity Bridging Algorithm: A custom-built name-cleaning and matching system designed to link disparate records from LegiScan and Quiver Quantitative.

Temporal Filtering: Advanced logic to ensure trades are correctly aligned with active legislative sessions (2021–2026), preventing look-ahead bias.

Predictive Modeling: Comparison between baseline regressors and deep learning architectures.

Technical Architecture
The analysis utilizes a modern machine learning stack to handle noisy financial data:

Deep Learning: Built using TensorFlow and Keras, featuring multi-layer architectures with Dropout regularization and Adam optimization.

Machine Learning: Implementation of MLPRegressors (Scikit-Learn) for non-linear pattern recognition.

Optimization: Hyperparameter tuning conducted via Optuna and Skorch to maximize model convergence and accuracy.

Data Processing: Extensive use of Pandas, NumPy, and NLP-based keyword extraction for sector classification.

Insights & Metrics
The model produces two primary outputs for every analyzed trade:

Insider Influence Signal (0–100): A normalized score representing the potential legislative impact on a specific ticker.

Confidence Score (0–5): A data-driven metric reflecting the model's certainty based on historical performance and data density.

Academic Context
Institution: Bologna Business School

Course: Neural Networks and Deep Learning

Lead Developer: [Ditt Namn]
