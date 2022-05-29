# MSc Dissertation 2021
Stock data of NEPSE from the year 2012 - 2020 was analysed. A comparative analysis of traditional financial models such as ARIMA and GARCH, and machine learning algorithms such as Linear Regression and LSTM models were studied. Hyperparameter optimization using Optuna framework for LSTM variants was the key focus of this research. Hyperparameters such as optimizers, LSTM hidden units, dropout rates, epochs, batch size and learning rate in combination with different LSTM architectures were tested.

ARIMA and GARCH models predicted stock price and stock returns with lower RMSE score when compared to error loss of LR model and manually tuned single and stacked LSTM models. Upon automated hyperparameter search, the overall loss of the LSTM variants was significantly lower than ARIMA, GARCH, LR and manually tuned single and stacked LSTM models. Single LSTM Variant 1 Model, upon automated hyperparameter search, had the lowest RMSE score of 7.21.

The Files are organized as:
- [Exploratory Data Analysis](https://github.com/SudipBishwakarma/MSc-Dissertation-2021/blob/main/MSc_Dissertation_EDA.ipynb)
- [ARIMA Model Analysis](https://github.com/SudipBishwakarma/MSc-Dissertation-2021/blob/main/MSc_Dissertation_ARIMA(ver_3).ipynb)
- [GARCH Model Analysis](https://github.com/SudipBishwakarma/MSc-Dissertation-2021/blob/main/MSc_Dissertation_GARCH(ver_2).ipynb)
- [Linear Regression Model Analysis](https://github.com/SudipBishwakarma/MSc-Dissertation-2021/blob/main/MSc_Dissertation_Linear_Regression(ver2).ipynb)
- [Single LSTM Variant 1 Model Analysis](https://github.com/SudipBishwakarma/MSc-Dissertation-2021/blob/main/msc-dissertation-single-lstm-ver-1-opt.ipynb)
- [Single LSTM Variant 2 Model Analysis](https://github.com/SudipBishwakarma/MSc-Dissertation-2021/blob/main/msc-dissertation-single-lstm-ver-2-opt.ipynb)
- [Stacked LSTM Variant 1 Model Analysis](https://github.com/SudipBishwakarma/MSc-Dissertation-2021/blob/main/msc-dissertation-stacked-lstm-ver-1-opt.ipynb)
- [Stacked LSTM Variant 2 Model Analysis](https://github.com/SudipBishwakarma/MSc-Dissertation-2021/blob/main/msc-dissertation-stacked-lstm-ver-2-opt.ipynb)
- [Overall Hyperparameter Optimization Results Analysis](https://github.com/SudipBishwakarma/MSc-Dissertation-2021/blob/main/Observations.ipynb)
