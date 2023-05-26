# Research Project Gold Prediction Using Deep Learning and Machine Learning

## Abstract
Gold has been a highly valued commodity for centuries, known for its secure nature and diverse applications in luxury, jewelry, electronics, and high-tech industries. This research project explores the influence of economic variables on gold prices, including macroeconomic indicators, stock indexes, and other commodities. The study utilizes machine learning models (M5P model trees) and deep learning models (LSTM) to predict gold prices with a 1-day and 7-day horizon. 

The research investigates the correlation between economic variables and gold price, employing technical indicators such as Bollinger Bands, SMA, MACD, RSI, and ROC to assess their effectiveness in forecasting gold prices. The findings indicate strong positive correlations between gold prices and variables such as US inflation rates, silver prices, copper prices, NASDAQ, DJI, and S&P500 indexes. Conversely, Brent Crude Oil prices exhibit the least positive correlation. Furthermore, macroeconomic factors such as the US Dollar Index, interest rates, and US Treasury Bond Yield demonstrate an inverse relationship with gold price.

The results reveal that technical indicators possess higher predictive power than economic indicators, with accuracy unaffected by data mining or time changes. Both the M5P and LSTM models accurately predict gold prices 1-day and 7-days ahead, achieving R2 values above 0.97 when utilizing technical analysis as inputs.

## Predictor
The research utilizes two main predictors for gold price prediction:

1. Technical Indicators:
   - Bollinger Bands
   - Simple Moving Average (SMA)
   - Moving Average Convergence Divergence (MACD)
   - Relative Strength Index (RSI)
   - Rate of Change (ROC)

2. Economic Variables and Commodities:
   - Silver Futures Price
   - Copper Futures Price
   - Brent Crude Oil Futures Prices
   - US Dollar Index (USDX)
   - Interest Rates (Federal Funds Effective Rate/Fed Fund Rates)
   - Inflation Rates (Consumer Price Index)
   - US Treasury Bond Yield (United States 10-Year Bond Yield)
   - Standard & Poor's 500 Index (SP500)
   - NASDAQ Composite Price
   - Dow Jones Industrial Average Price

## Research Objectives
1. Perform an analysis to examine the relationship between the US Dollar Index, interest rates, inflation rates, US Treasury Bond Yield, SP500, NASDAQ Composite Price, Dow Jones Industrial Average Price, silver, copper, oil prices, and the price of gold.
2. Determine and compare the prediction performance of the M5P model tree and LSTM models for gold price forecasting.
3. Evaluate and compare the performance of the models using technical analysis predictors, economic variables, and a combination of both.

By investigating these objectives, the research aims to enhance our understanding of the factors influencing gold prices and the effectiveness of different prediction models.

Certainly! Here's an example of how you can write the instructions in the GitHub README.md format:

## Instructions

### Gold Price Prediction

This repository contains code for predicting gold prices using deep learning and machine learning models. The prediction results for both 1-day and 7-day horizons can be obtained by following these steps:

 1. Open the Jupyter Notebook `Gold_Prediction_Project_1day.ipynb` for 1-day prediction or `Gold_Prediction_Project_7day.ipynb` for 7-day prediction in google colab, anaconda or any python program.
 2. Download the project dataset from the provided link: Gold Prediction Dataset.xlsx.
 3. Place the downloaded dataset file (Gold Prediction Dataset.xlsx) in the root directory of the repository.
 4. Run the notebook cells to execute the code and generate the prediction results.

### Research Reports

For detailed information about the research project and its findings, please refer to the research reports provided:

- [Gold Prediction Research Project.pdf](https://github.com/your-username/gold-prediction/blob/main/Gold%20Prediction%20Research%20Project.pdf)

These reports contain insights on the influence of economic variables, the effectiveness of different models, and the correlation analysis between gold prices and various factors and many more.

Feel free to explore the code and reports to gain a deeper understanding of the research project and its results.

If you encounter any issues or have questions, please open an issue in the repository or contact the project contributors.

Enjoy exploring the gold price prediction project and the research findings!

**Note:** The prediction results are for informational purposes only and should not be considered as financial advice.
