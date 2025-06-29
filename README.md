# Stock Market Trend Prediction using Machine Learning
Description:

Developed a machine learning model to predict short-term trends in the S&P 500 index using historical market data. Leveraged yfinance to retrieve financial time series data and engineered a binary classification task to determine whether the next day’s closing price would rise. Applied a Random Forest Classifier as the prediction engine, trained on key technical indicators such as closing price, volume, high, low, and open prices.

Implemented a custom backtesting framework to evaluate model performance over rolling windows and simulate real-world deployment. Evaluated model accuracy using precision score and visualized prediction trends against actual outcomes.

Key Contributions:

Fetched and preprocessed multi-decade historical data using pandas and yfinance.

Engineered the target variable based on next-day price movement.

Tuned and trained a Random Forest model using scikit-learn.

Built a modular backtesting loop to measure out-of-sample performance.

Visualized market trends and predictions using matplotlib.

Tools & Libraries: Python, Pandas, yfinance, Scikit-learn, Matplotlib

Outcomes:

Achieved consistent precision in predicting upward price movement.

Gained hands-on experience in financial ML, data preprocessing, and model evaluation.
