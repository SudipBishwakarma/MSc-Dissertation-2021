# MSc Dissertation 2021

This repository contains the research and implementation for my MSc Dissertation. This work was part of a paper submitted to and published in IEEE, titled **"Automated Hyperparameter Optimization in Machine Learning for Stock Prediction"**. I am the primary author of this work.

[Link to Paper (IEEE Xplore)](https://ieeexplore.ieee.org/document/10079816)

## Abstract
Stock prediction is the key area of focus in financial analysis. The growing amount of data and readily available machine learning algorithms has surged the amount of research in this field. This research in particular, involved in stock prediction of NEPSE using machine learning algorithms such as Linear Regression and LSTM. The research also studied traditional financial models such as ARIMA and GARCH. The analysis involved in manual and automated hyperparameter optimization via Optuna framework for single and stacked LSTM models. Initially, traditional financial models performed better than manually optimized LSTM variants. But the automated hyperparameter tuning approach significantly lowered the error loss and the single LSTM model best predicted the stock price with 7.21 RMSE score.

## Overview
Stock data of NEPSE from the year 2012 - 2020 was analysed. A comparative analysis of traditional financial models such as ARIMA and GARCH, and machine learning algorithms such as Linear Regression and LSTM models were studied. Hyperparameter optimization using Optuna framework for LSTM variants was the key focus of this research. Hyperparameters such as optimizers, LSTM hidden units, dropout rates, epochs, batch size and learning rate in combination with different LSTM architectures were tested.

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

## Citation
If you find this research useful, please cite my paper:
> @INPROCEEDINGS{10079816,\
  author={Bishwakarma, Sudip Tiwari and Sharma, Gajendra},\
  booktitle={2022 Second International Conference on Next Generation Intelligent Systems (ICNGIS)},\
  title={Automated Hyperparameter Optimization in Machine Learning for Stock Prediction},\
  year={2022},\
  volume={},\
  number={},\
  pages={1-6},\
  keywords={Machine learning algorithms;Linear regression;Stochastic processes;Manuals;Predictive models;Hyperparameter optimization;Data models;Machine Learning;NEPSE;Stock Prediction;Optuna;Hyperparameter Tuning;LSTM;Linear Regression;ARIMA;GARCH},\
  doi={10.1109/ICNGIS54955.2022.10079816}}
  