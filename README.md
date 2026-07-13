# Credit Card Anomaly Detection Using Isolation Forest

[![Python 3.9+](https://img.shields.io/badge/python-3.9+-blue.svg)](https://www.python.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![UCI Dataset](https://img.shields.io/badge/dataset-UCI-orange.svg)](https://archive.ics.uci.edu/dataset/350/default+of+credit+card+clients)

> 🔍 **Unsupervised anomaly detection for credit risk management using Isolation Forest**

## 📋 Project Overview

This project applies the **Isolation Forest algorithm** to the UCI Credit Card Default dataset to identify financially anomalous client profiles. By analyzing repayment behavior, billing patterns, and credit utilization, the model flags clients with elevated default risk—**without using labeled data during training**.

### ✨ Key Features
- **Unsupervised Learning**: Detects novel risk patterns without historical labels
- **Feature Engineering**: Creates financial stress indicators (payment-to-bill ratio, utilization)
- **Sensitivity Analysis**: Evaluates impact of contamination parameter on detection performance
- **Interpretable Outputs**: Statistical comparisons between outliers and inliers
- **Reproducible Pipeline**: Modular code with clear documentation

### 🎯 Use Cases
- Early warning systems for credit risk teams
- Fraud detection preprocessing layer
- Exploratory data analysis for financial portfolios
- Academic research in unsupervised anomaly detection

## 🚀 Quick Start

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/credit-card-anomaly-detection.git
cd credit-card-anomaly-detection
