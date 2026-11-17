# Brent Price Change Analysis and Statistical Modeling of Brent Oil Prices 🌍📈

## Table of Contents 📚

- [Project Overview](#project-overview)
- [Key Objectives](#key-objectives)
- [Data](#data)
- [Methodology](#methodology)
  - [Data Analysis Workflow](#1️⃣-data-analysis-workflow)
  - [Statistical & Machine Learning Models](#2️⃣-statistical--machine-learning-models)
  - [Change Point Detection Techniques](#3️⃣-change-point-detection-techniques)
- [Key Features of the Dashboard](#key-features-of-the-dashboard)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Results & Insights](#results--insights)
- [References & Further Reading](#references--further-reading)
- [How to Run the Project](#how-to-run-the-project)
- [Contributing](#contributing)

## Project Overview

The aim of this project is to analyze Brent oil price fluctuations by detecting change points and identifying their causes using statistical modeling. By leveraging time series models such as ARIMA, GARCH, and Bayesian methods (PyMC3), we investigate how economic, political, and regulatory events impact oil prices. The insights generated will help investors, policymakers, and analysts make informed decisions. 💡

## Key Objectives 🎯

- Detect change points in Brent oil prices over the past decades. 📊
- Analyze the impact of key events (e.g., political decisions, economic sanctions, OPEC policies) on price fluctuations. 🌐
- Apply statistical modeling techniques such as Bayesian inference, ARIMA, and GARCH. 📉
- Develop an interactive dashboard using Flask and React for visualizing results. 🖥️
- Provide actionable insights for investment strategies, policy development, and risk management. 📈

## Data 📂

- **Source:** Historical Brent oil prices dataset (1987 - 2022).
- **Fields:**
  - `Date`: Daily recorded price (Format: DD-MMM-YY).
  - `Price`: Brent oil price in USD per barrel.

## Methodology 🔍

### 1️⃣ Data Analysis Workflow

- Data cleaning and preprocessing 🧹
- Exploratory Data Analysis (EDA) 📊
- Time series modeling and change point detection 📈
- Model evaluation and selection ✅
- Interpretation of findings 🔍

### 2️⃣ Statistical & Machine Learning Models

- **Time Series Models:** ARIMA, GARCH 📉
- **Bayesian Modeling:** Bayesian Change Point Detection (PyMC3) 📊
- **Machine Learning:** LSTM (Long Short-Term Memory) for deep learning analysis 🤖
- **Econometric Models:** VAR (Vector Autoregression) for multivariate analysis 📈

### 3️⃣ Change Point Detection Techniques

- Bayesian Change Point Analysis 🔍
- Likelihood Ratio Tests ⚖️
- CUSUM (Cumulative Sum Control Chart) 📊
- Pettitt’s Test 🧪
- Segmented Regression 📈

## Key Features of the Dashboard 🖥️

- Interactive visualizations of Brent oil price trends and change points. 📊
- Event highlighting: See price shifts corresponding to major economic/political events. 🌍
- Custom filters: Explore price movements across different timeframes. ⏳
- Model performance metrics: Evaluate prediction accuracy. 📏

## Tech Stack ⚙️

- **Programming Languages:** Python, JavaScript 🐍💻
- **Backend:** Flask (API for serving model results) 🔌
- **Frontend:** React (for interactive visualization) 📱
- **Libraries & Tools:** Pandas, NumPy, Matplotlib, Seaborn, PyMC3, Statsmodels, Scikit-learn, D3.js, Recharts 📚

## Project Structure 📁


  ```bash
     Directory structure:
└── dagiteferi-brent-price-change-analysis/
    ├── README.md
    ├── file_structure.py
    ├── requirements.txt
    ├── docs/
    │   └── data_analysis_workflow.md
    ├── logs/
    ├── models/
    │   ├── X_scaler.pkl
    │   ├── lstm_model.h5
    │   └── y_scaler.pkl
    ├── notebooks/
    │   ├── README.md
    │   ├── __init__.py
    │   ├── changepointanalysis.ipynb
    │   ├── eda.ipynb
    │   └── logs/
    ├── oil-price-dashboard/
    │   ├── backend/
    │   │   ├── app.py
    │   │   └── evaluation_results.pkl
    │   └── frontend/
    │       ├── README.md
    │       ├── README.old.md
    │       ├── package-lock.json
    │       ├── package.json
    │       ├── .gitignore
    │       ├── public/
    │       │   ├── index.html
    │       │   ├── manifest.json
    │       │   └── robots.txt
    │       └── src/
    │           ├── App.css
    │           ├── App.js
    │           ├── App.test.js
    │           ├── index.css
    │           ├── index.js
    │           ├── reportWebVitals.js
    │           └── setupTests.js
    ├── scripts/
    │   ├── README.md
    │   ├── AdaptingModel.py
    │   ├── __init__.py
    │   ├── analyzer.py
    │   ├── eda.py
    │   ├── logger.py
    │   ├── oil_price_analysis.py
    │   └── visualizer.py
    ├── src/
    │   ├── __init__.py
    │   ├── data_loading.py
    │   └── fetcher.py
    ├── tests/
    │   └── __init__.py
    └── .github/
        └── workflows/
            └── unittests.yml
  ```


## How to Run the Project 🚀

1. **Clone the Repository**
   ```bash
   git clone https://github.com/dagiteferi/brent-price-change-analysi.git
   cd brent-price-change-analysi
    ```
2. **Install Dependencies**
```bash
    pip install -r requirements.txt
```
3. **Run the Flask Backend**
```bash
   cd dashboard/backend
  flask run

```
The backend should now be running on http://127.0.0.1:5000/.
4. **Start the React Frontend**
   ```bash
 cd dashboard/frontend
npm start

   ```
The frontend should now be running on http://localhost:3000/


**Contributing 🤝**

Contributions are welcome! Feel free to open issues and pull requests. Specific areas where contributions are especially welcome include model development, dashboard features, and documentation.
"# FIRST-Ever-AI-Project" 
