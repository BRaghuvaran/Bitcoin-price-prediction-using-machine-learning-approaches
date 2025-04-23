**Bitcoin Price Prediction using Machine Learning Approaches**

This project explores various machine learning models to predict Bitcoin prices using historical data. The code includes detailed preprocessing, exploratory data analysis (EDA), model training, evaluation, and visual comparisons of results across different ML algorithms.

**Objective**
The aim of this project is to predict the weighted price of Bitcoin using multiple machine learning approaches, comparing their performance to identify the most effective predictive model.

**Dataset**

**The dataset used is historical Bitcoin transaction data with the following columns:**

- Timestamp
- Open
- High
- Low
- Close
- Volume_(BTC)
- Volume_(Currency)
- Weighted_Price

**Methodology**

**Preprocessing**

- Handling missing values and duplicates
- Time resampling (Daily, Monthly, Quarterly, Yearly)
- Normalization using MinMaxScaler
- Log transformation of price data

**Exploratory Data Analysis**

- Correlation heatmaps
- Histograms, boxplots, scatterplots
- Seasonality decomposition using statsmodels
- Time series visualizations

**Machine Learning Models:**

- K-Nearest Neighbors
- Gradient Boosting Regressor
- XGBoost Regressor
- AdaBoost Regressor
- Convolutional Neural Network
- Long Short-Term Memory

**Evaluation Metrics**

Models are evaluated using:
- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)
- R² Score

Each model’s performance is visualized and compared using bar plots and radar charts.

**Key Findings**

- Gradient Boosting Regressor performed the best based on RMSE and R².
- KNN and XGBoost showed promising results with minimal error margins.
- Deep learning models (LSTM and CNN) demonstrated high predictive power but required more computational resources.

**How to Run the Code**

1) Open the .ipynb file in Google Colab or Jupyter Notebook

2) Mount Google Drive

3) Make sure dataset path is correct

4) Run all cells to execute preprocessing, model training, and evaluation
