# Day-Ahead Electricity Price Prediction

Testing different machine learning models to predict the day-ahead electricity price in Germany.



 ### Inputs:
Forecasted Solar, Forecasted Wind Onshore, Forecasted Wind Offshore, Yesterday's Gas Prices, Forecasted Load, A 24 hour lag of the Forecasted Load, Co2 Certificate Prices, 24 hour lagged of the Day-ahead price, A one week lagged of the Day-ahead price



### Target Variable
Day-ahead-price



### Key Features
- Data preprocessing in Excel (cleaning, visualisation)
- Python for:
  - Feature engineering (lags, moving averages, sin & cos time encoding)
  - Model training (XGBoost, Random Forest, LSTM, etc.)
  - Evaluation (MSE) 



### Tech Stack
- **Data Preprocessing:** Excel (.xlsx)
- **Machine Learning:** Python  
- **IDE:** Visual Studio Code  



 
###  How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/<yourusername>/day-ahead-price-prediction.git
   cd day-ahead-price-prediction
