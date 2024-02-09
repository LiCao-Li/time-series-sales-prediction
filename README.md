Time Series Sales Prediction

This repository contains the code and documentation for a time series forecasting project aimed at predicting total sales for each of 935 individual stores for 4 weeks ahead. The project utilizes various models and techniques, including auto-ARIMA, ARFIMA, and hierarchical clustering approaches, to forecast sales and compare model performance using sMAPE loss.

Models and Techniques Used
1. Auto-ARIMA with Singular Value Decomposition (SVD)
2. Auto-ARIMA with Independent Component Analysis (ICA)
3. Auto-ARIMA with Non-Negative Matrix Factorization (NMF)
4. Hierarchical Time Series (HTS)

Results
After thorough analysis and comparison of the different models and techniques, the following results were obtained:

Hierarchical (HTS): This approach yielded the most accurate predictions among all techniques.
Non-Negative Matrix Factorization (NMF): NMF performed well and showed promising results in forecasting total sales for the stores.
Singular Value Decomposition (SVD) with Auto-ARIMA: SVD with auto-ARIMA provided satisfactory predictions but lagged behind HTS and NMF.
Independent Component Analysis (ICA) with Auto-ARIMA: ICA did not perform well in predicting sales compared to the other techniques.






