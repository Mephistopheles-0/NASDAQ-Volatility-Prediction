# NASDAQ Volatility Prediction using ARCH, GARCH, EGARCH, SVM, ANN and more
This project aims to predict the future volatility of the NASDAQ index using various econometric and machine learning models, including ARCH, GARCH, EGARCH, SVM, and ANN. The project is implemented using Python and Jupyter notebooks.

## Introduction
Volatility prediction is a crucial aspect of finance and investment, and the NASDAQ index is one of the most widely followed stock market indices in the world. In this project, we use multiple models to predict the future volatility of the NASDAQ index and compare their performance.

## Requirements
The following packages are required to run the project:

NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn
TensorFlow
Arch
## Dataset
The dataset used for this project is obtained from Yahoo Finance. It contains daily historical data for the NASDAQ index, including the date, opening price, closing price, and daily returns.

## Methodology
The project uses several econometric models, including ARCH, GARCH, and EGARCH, to model the volatility of the NASDAQ index. The models are trained using a 80-20 split of the data, with 80% used for training and 20% used for testing. The performance of each model is evaluated using the mean squared error and root mean squared error.

In addition, the project also combines the econometric models with machine learning models such as SVM and ANNs. The models are trained using the residuals obtained from the econometric models, and their performance is compared with the standalone econometric models.

## Results
The results of the project show that the combination of econometric models and machine learning models outperforms the standalone models in terms of accuracy. The best-performing model was a combination of EGARCH and ANN, achieving high accuracy in predicting the future volatility of the NASDAQ index.

## Conclusion
This project demonstrates the potential of combining econometric models and machine learning models in solving real-world problems. The code and notebooks can be used as a starting point for further research and development in the field of volatility prediction.
