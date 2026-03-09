# Market-Implied Credit Risk Estimation & Prediction Engine

This project develops a **machine learning system to analyze and predict Credit Default Swap (CDS) spreads**, a market-based measure of credit risk. CDS spreads reflect the market’s perception of the probability that a firm will default. By combining CDS data with firm fundamentals, market indicators, and macroeconomic variables, the project aims to estimate the drivers of credit risk and predict future CDS spread movements.

The core dataset contains **CDS spreads for over 600 firms across multiple maturities (2015–2021)**. The analysis focuses primarily on the **5-year CDS spread**, which is the standard benchmark used in credit markets. Additional features such as the **CDS term structure slope (CDS10Y − CDS1Y)**, financial ratios, stock volatility, and macroeconomic indicators are constructed to capture structural, market, and systemic credit risk factors.

Machine learning models including **Linear Regression, Ridge/Lasso, Random Forest, and Gradient Boosting** are used to estimate and predict CDS spread changes. Model performance is evaluated using **RMSE, MAE, and R²**. The goal is to build a research-driven pipeline capable of detecting **early warning signals of credit deterioration** and understanding how financial markets price credit risk.

The project integrates multiple datasets including CDS market data, firm financial statements (via Yahoo Finance API), stock market indicators, and macroeconomic variables from public databases such as FRED.

Dataset (CDS spreads):  
https://www.kaggle.com/datasets/debashish311601/credit-default-swap-cds-prices

Technologies used include **Python, Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib, and Jupyter Notebooks**.

Author: **Youssef Chati**  
Computer Engineering — Financial Machine Learning & Credit Risk Modeling