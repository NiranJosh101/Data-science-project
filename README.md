📊 Inflation Analysis and Prediction in Nigeria

📁 Project Overview

This project explores the key drivers of inflation in Nigeria and builds a predictive-ready dataset using various macroeconomic indicators such as production, crude oil export, and Consumer Price Index (CPI) categories. The process includes thorough exploratory data analysis (EDA), skewness and outlier handling, feature engineering, and data cleaning to prepare for predictive modeling.


✅ Objectives

1. Understand the temporal and sectoral factors influencing inflation.

2. Examine relationships between production, crude oil export, and inflation rate.

3. Engineer relevant features to improve prediction accuracy.

4. Deliver a clean, structured dataset ready for modeling.


📌 Data Sources

1. National Bureau of Statistics (NBS)

2. Central Bank of Nigeria (CBN) Economic Reports

3. CPI Category Breakdown (e.g., Food, Energy, Transport)

4. Crude Oil Production and Export Records


🔍 Analysis Summary

📈 Exploratory Data Analysis (EDA)

1. Temporal Trends: Identified if changes in production/export precede inflation fluctuations.

2. Sectoral Impact: Compared inflation with CPI categories like food, energy, and transport.

3. Correlation & Causality: Visualized patterns between inflation and economic indicators.


🧹 Data Preprocessing

1. Outlier Removal: Applied IQR method to remove extreme values.

2. Skewness Correction: Used natural log and Box-Cox transformations.

3. Missing Values: Handled using backward fill (backfilling) strategy.


🛠 Feature Engineering
We created new variables to capture complex relationships:

| Feature                                    | Purpose                                        |
| ------------------------------------------ | ---------------------------------------------- |
| `Production_Growth`, `Crude_Export_Growth` | Capture economic trends over time              |
| `Export_per_Production`                    | Proxy for oil revenue efficiency               |
| `CPI_Sensitive_Avg`                        | Composite index of inflation-sensitive sectors |
| `Production_x_Export`                      | Interaction term to reveal joint effects       |

These features enhance model performance by revealing hidden relationships not captured in raw variables.


🚀 How to Run This Project

1. Clone the repository
git clone https://github.com/niran101/inflation-nigeria.git
cd inflation-nigeria

2. Install required libraries
pip install -r requirements.txt

3. Launch Jupyter Notebook
jupyter notebook notebooks/inflation_analysis.ipynb


📌 Key Insights

1. Inflation often spikes after significant drops in oil export or production.

2. The Energy and Transport CPI categories are strongly correlated with headline inflation.

3. Interaction between production and export volumes provides more predictive power than either alone.



