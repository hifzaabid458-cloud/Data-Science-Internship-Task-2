# Stock Market Price Prediction

## 📌 Project Overview

This project uses historical stock market data and machine learning techniques to predict stock prices. The project focuses on data analysis, visualization, feature selection, model building, evaluation, and prediction.

Multiple machine learning models were developed and compared to identify the best-performing model.

## 🎯 Objectives

- Analyze historical stock market data
- Clean and prepare the dataset
- Explore relationships between stock market features
- Build machine learning prediction models
- Compare model performance using evaluation metrics
- Analyze prediction errors
- Identify important features using Linear Regression coefficients
- Select the best-performing model

## 📊 Dataset

The dataset contains historical stock market information with features such as:

- Open
- High
- Low
- Close
- Volume

The Close price was used as the target variable according to the prediction setup used in the project.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## 🔄 Project Workflow

1. Import required libraries
2. Load the dataset
3. Explore the dataset
4. Check and handle missing values
5. Perform exploratory data analysis
6. Select relevant features
7. Split the data into training and testing sets
8. Train Linear Regression model
9. Train Random Forest model
10. Improve the Linear Regression model
11. Build a Next-Day prediction model
12. Evaluate model performance
13. Analyze prediction errors
14. Analyze feature coefficients
15. Select the best-performing model

## 🤖 Models Used

1. Linear Regression — Same Day

MAE: 4.541851
RMSE: 6.127072
R² Score: 0.992421

2. Random Forest — Same Day

MAE: 25.857169
RMSE: 42.503416
R² Score: 0.635275

3. Improved Linear Regression — Same Day

MAE: 3.830361
RMSE: 5.796654
R² Score: 0.993216

4. Linear Regression — Next Day

MAE: 7.924630
RMSE: 13.084681
R² Score: 0.965434

## 🏆 Best Model

The Improved Linear Regression – Same Day model achieved the best overall performance.

Metric| Result
MAE| 3.830361
RMSE| 5.796654
R² Score| 0.993216

The R² Score of 0.993216 indicates that the model explains approximately 99.32% of the variation in the target variable on the test data.

## 🔍 Feature Coefficients

The Linear Regression coefficients were:

Feature| Coefficient
Close| 0.6467145
Low| 0.2505088
High| 0.2438382
Open| -0.1495659
Volume| -0.0000001447

The Close feature had the strongest positive coefficient among the features in the fitted model.

## 📉 Prediction Error Analysis

Prediction errors were analyzed using a residual plot. The errors were generally distributed around zero, indicating that the model did not show a strong overall systematic bias.

Some larger errors were also observed, showing that certain observations were more difficult for the model to predict accurately.

## 💡 Key Findings

- Improved Linear Regression performed better than the other tested models.
- The same-day model achieved higher accuracy than the Next-Day model.
- Close had the strongest coefficient in the fitted Linear Regression model.
- Random Forest performed considerably worse on this dataset.
- Prediction errors were generally centered around zero.
- Machine learning can effectively model patterns in this historical dataset.

## ⚠️ Limitations

Stock prices are affected by many factors that are not included in this dataset, including market sentiment, economic conditions, news, company performance, and unexpected events.

Therefore, the model should be considered an educational and analytical project rather than a guaranteed stock market forecasting system.

## 🚀 Future Improvements

Future versions of this project could include:

- Time-series models such as ARIMA or LSTM
- Additional technical indicators
- More historical data
- Market sentiment analysis
- Hyperparameter tuning
- Cross-validation
- More advanced feature engineering
- Comparison with additional machine learning algorithms

## 👩‍💻 Author

### Hifza Abid

Computer Science Student | Data Science & Machine Learning Learner
