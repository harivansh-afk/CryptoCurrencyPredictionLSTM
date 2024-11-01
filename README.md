# Efficiency of Machine Learning Algorithms for Predicting Fluctuations in the Cryptocurrency Market

## Authors and Affiliations
**Harivansh Rathi**  
UVA Class of 2027

## Abstract
The last several years have seen a rise in interest in machine learning and AI-assisted crypto trading. Here, we put this strategy to the test to see if it might indeed be profitable to take advantage of the crypto market's inefficiencies. We examine and analyze data from 2013 to 2021 to demonstrate that basic trading techniques surpass traditional benchmarks when supported by cutting-edge machine learning models, such as LSTM (long short-term memory). Our results show that machine learning can, in fact, be used profitably in the crypto market, and simple machine learning methods such as regression can be deployed successfully to predict the crypto market. This can be used advantageously by crypto traders.

## Introduction
The crypto market is renowned for its turbulence, dynamic, and nonlinear nature, making it very difficult to anticipate crypto prices accurately. However, the availability of large data sets allows researchers to use machine learning to identify patterns and trends. In this study, we explore several prediction models, including regression, random forest, LSTM, and SVM, to predict crypto market trends. We use Python, Scikit-learn, and other tools to process data and build models.

LSTM, a type of recurrent neural network, is particularly promising for analyzing sequential data like time series. This research builds on previous studies, which primarily focus on a few cryptocurrencies and outdated datasets, by incorporating more recent data and a broader range of currencies.

## Instructions
- To Run this file, you must first download the dataset that this is based upon
- The dataset can be found on [Kaggle](https://www.kaggle.com/datasets/jessevent/all-crypto-currencies) and download as a zip file
- Once the file has been downloaded you must add it to the same folder as the .ipynb file on your computer
- The project can then be run and tested on this dataset
  
## Results
Our results demonstrate an accuracy rate of 50-60%, highlighting the volatility of the cryptocurrency market. The LSTM model showed a slight improvement over other models, indicating its suitability for time-series data. We implemented our models using Python libraries such as Sklearn, Keras, and Tensorflow, executing them on the JupyterLab platform. The best model was selected based on RMSE and MAPE values. 

### Key Findings:
- Machine learning algorithms can predict short-term changes in the bitcoin market with reasonable accuracy.
- RNN and LSTM models are particularly useful for short-term predictions in the crypto market.
- Although not aimed at maximizing trading success, this study suggests that predictive techniques may be applied with longer prediction horizons to minimize transaction costs.

## Discussion
This research demonstrates that machine learning can predict cryptocurrency prices with modest accuracy, though market uncertainty remains a limiting factor. We also discuss how socio-economic factors such as political events influence crypto prices and suggest directions for future research. Future studies may improve upon the LSTM model by adding dropout layers or conducting sentiment analysis alongside LSTM predictions.

## Methods
This section provides an overview of the machine learning methods used in this study. The dataset, sourced from [Kaggle](https://www.kaggle.com/datasets/jessevent/all-crypto-currencies), consists of daily closing prices from 2013 to 2021 for several cryptocurrencies. 

### Experimental Purpose
The goal is to predict the closing price based on time series data. Six separate LSTM models were trained to predict future prices for Bitcoin, Ripple, Ethereum, and other cryptocurrencies. Key parameters of the models include:
- Learning rate: 0.001
- Optimizer: Adam
- Batch size: 32
- Hidden layers: 2
- Neurons per layer: 128

### Models
This study focuses on the LSTM model, well-suited for time series data interpretation and prediction. In addition to LSTM, Support Vector Machines (SVM) and other regression models are used for comparison.

## Acknowledgments
This work was supported by the Lumiere research team and Emily Kim (Doctoral Researcher at Carnegie Mellon University Robotics).

## References
1. Sebastião, H., & Godinho, P. (2021). Forecasting and trading cryptocurrencies with machine learning under changing market conditions. *Financial Innovation*. Retrieved from [SpringerOpen](https://jfin-swufe.springeropen.com/articles/10.1186/s40854-020-00217-x#Abs1).
2. Alessandretti, L., ElBahrawy, A., Aiello, L. M., & Baronchelli, A. (2018). Anticipating cryptocurrency prices using machine learning. *Complexity*. Retrieved from [Hindawi](https://www.hindawi.com/journals/complexity/2018/8983590/#materials-and-methods).
3. Akyildirim, E., Goncu, A., & Sensoy, A. (2020). Prediction of cryptocurrency returns using machine learning. *Annals of Operations Research*. Retrieved from [SpringerLink](https://link.springer.com/article/10.1007/s10479-020-03575-y).
4. Every Cryptocurrency Daily Market Price. (2018). *Dataset*. Retrieved from [Kaggle](https://www.kaggle.com/datasets/jessevent/all-crypto-currencies).
