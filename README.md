# Dimensionality Reduction & Factor Extraction via PCA

An end-to-end data science project implementing **Principal Component Analysis (PCA)** for exploratory data analysis, dimensionality reduction, and feature extraction.

## 📌 Project Overview
This project applies PCA to multivariate datasets (such as chemical compositions and diagnostic measurements) to address the **Curse of Dimensionality** and resolve **Multicollinearity** among features.

## 🚀 Pipeline Workflow
1. **Data Standardization**: Used `StandardScaler` to normalize features to a uniform scale, preventing high-variance variables from dominating the covariance matrix.
2. **Exploratory Data Analysis (EDA)**: Analyzed correlation heatmaps to understand linear relationships between original variables.
3. **Eigenvalue Decomposition**: Computed covariance matrices and projected high-dimensional data into orthogonal principal components ($PC_1, PC_2, \dots$).
4. **Cumulative Explained Variance**: Evaluated variance ratios to scientifically determine the optimal number of components to retain.

## 💡 Relevance to Quantitative Finance
In quantitative finance and risk management, high-dimensional data (e.g., multi-asset returns or macroeconomic indicators) often suffer from severe multicollinearity. This PCA framework mirrors foundational techniques used in:
* **Statistical Factor Models**: Extracting latent market risk factors.
* **Portfolio Risk Management**: Reducing noise and preventing overfitting in predictive pipelines.

## 🛠️ Tech Stack
* **Language**: Python
* **Libraries**: `Scikit-Learn`, `Pandas`, `NumPy`, `Matplotlib`
