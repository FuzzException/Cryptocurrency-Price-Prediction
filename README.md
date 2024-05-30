# Cryptocurrency Price Prediction
Real Time Cryptocurrency Price Prediction using Time Series Forecasting : SARIMA Model and ARIMA Model 

<img width="1440" alt="crypto1" src="https://github.com/FuzzException/Cryptocurrency-Price-Prediction/assets/98276556/a784861e-5d34-4154-a3dd-25f4a52d5642">

<img width="1440" alt="crypto2" src="https://github.com/FuzzException/Cryptocurrency-Price-Prediction/assets/98276556/57ac0af0-fd74-4db7-a49f-b191c870b40e">

<img width="1440" alt="crypto3" src="https://github.com/FuzzException/Cryptocurrency-Price-Prediction/assets/98276556/3f879229-88bd-4921-8178-0dfc31af3d76">

<img width="1440" alt="crypto4" src="https://github.com/FuzzException/Cryptocurrency-Price-Prediction/assets/98276556/5185184b-490b-4361-bce9-65bbd4da2203">

<img width="1440" alt="crypto5" src="https://github.com/FuzzException/Cryptocurrency-Price-Prediction/assets/98276556/1928faea-e0c4-40f3-b7b3-3dee2f59b115">

### Cryptocurrency Price Prediction Using ARIMA and SARIMA Models

**Project Description:**

This project aims to develop a system for predicting cryptocurrency prices using time series forecasting methods, specifically ARIMA (AutoRegressive Integrated Moving Average) and SARIMA (Seasonal AutoRegressive Integrated Moving Average). By leveraging historical cryptocurrency data, the project seeks to provide accurate short-term price predictions which can be valuable for traders, investors, and financial analysts.

**Objectives:**

1. **Data Collection:** 
   - Fetch historical cryptocurrency price data using the Yahoo Finance API.
   - Focus on key cryptocurrencies such as Bitcoin (BTC-USD), Ethereum (ETH-USD), and others.

2. **Data Preprocessing:**
   - Clean and preprocess the collected data.
   - Split the data into training and testing sets to evaluate the model's performance.

3. **Model Development:**
   - Develop and fit ARIMA and SARIMA models to the training data.
   - Tune model parameters to achieve optimal performance.

4. **Forecasting:**
   - Use the trained models to forecast future prices of cryptocurrencies.
   - Compare the performance of ARIMA and SARIMA models.

5. **Evaluation:**
   - Evaluate the models' accuracy using Mean Squared Error (MSE) and other relevant metrics.
   - Analyze the models' strengths and limitations.

6. **Visualization:**
   - Plot the actual vs. predicted prices to visually assess the models' performance.
   - Use interactive plots for better insight and user interaction.

**Technical Stack:**

- **Data Collection:** Yahoo Finance API (via `yfinance` Python library)
- **Data Manipulation:** Pandas, NumPy
- **Modeling:** Statsmodels (for ARIMA and SARIMA models)
- **Evaluation:** Scikit-learn (for MSE calculation)
- **Visualization:** Matplotlib, Plotly

**Implementation Steps:**

1. **Fetching Data:**
   - Use the `yfinance` library to download historical price data for selected cryptocurrencies.

2. **Preprocessing:**
   - Extract the 'Close' prices and handle missing data if any.
   - Split the data into training (80%) and testing (20%) sets.

3. **Model Training:**
   - Fit ARIMA and SARIMA models on the training data.
   - Adjust the model parameters (p, d, q for ARIMA and p, d, q, P, D, Q, S for SARIMA) based on the data characteristics.

4. **Prediction:**
   - Generate forecasts for the test period.
   - Extend the forecast to predict future prices beyond the test period.

5. **Evaluation:**
   - Calculate MSE for both ARIMA and SARIMA forecasts to quantify prediction accuracy.
   - Compare the MSE values to determine the better performing model.

6. **Visualization:**
   - Plot training data, actual test data, and forecasts from both models.
   - Use Plotly for interactive visualization, allowing users to explore the data and predictions.

**Expected Outcomes:**

- A comprehensive comparison of ARIMA and SARIMA models for cryptocurrency price prediction.
- Interactive visualizations of actual vs. predicted prices.
- Insights into the performance and applicability of these time series models for financial forecasting.

**Conclusion:**

This project provides a detailed framework for predicting cryptocurrency prices using ARIMA and SARIMA models. It demonstrates the process of data collection, model training, evaluation, and visualization, offering a valuable tool for financial decision-making and analysis.
