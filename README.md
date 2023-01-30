# Yes Bank Stock Closing Price Prediction

![Untitled design](https://user-images.githubusercontent.com/121177364/214146114-0e24b845-3088-4409-9380-8b4d8f009f13.png)

Yes Bank is a well-known bank in the Indian financial domain. Since 2018, it has been in the news because of the fraud case involving Rana Kapoor. Owing to this fact, it was interesting to see how that impacted the stock prices of the company and whether Time series models or any other predictive models can do justice to such situations. This dataset has monthly stock prices of the bank since its inception and includes closing, starting, highest, and lowest stock prices of every month. The main objective is to predict the stock's closing price of the month.

#  Data

The data used for training and testing the model is the historical closing stock prices of Yes Bank and includes the following information:

    1. Date - Date of record
    2. Open - Opening Price
    3. High - Highest price in the day
    4. Low - Lowest price in the day
    5. Close - Price at the end of the day

# Requirements

To run this project, you will need to have the following packages installed:

    1. Python - Programming Language
    2. Numpy - Scientific computing library
    3. Pandas - Data manipulation library
    4. Matplotlib - Data visualization library
    5. Seaborn - Data visualization library
    6. Scikit-learn For model training, model optimization, and matrices calculation.

# Usage

    * Clone the repository
    * Run the jupyter notebook yes_bank_closing_stock_price_prediction.ipynb

# Conclusion

The ridge regression model is the best model for forecasting the closing price of Yes Bank's stock, according to the findings of the prior comparisons. With low mean squared error, root mean squared error, and mean absolute error, as well as a high R2 score, the ridge regression model has consistently demonstrated a high level of prediction accuracy. The Local Interpretable Model-agnostic prediction local values further support the excellent accuracy of the ridge regression model. The linear regression model offers intermediate accuracy, whereas the lasso regression model has a lesser level of accuracy. As a result, the ridge regression model is best suited to forecast the closing price of Yes Bank's shares.

# Note

*This project is for educational purposes only and should not be used for investment decisions.*
