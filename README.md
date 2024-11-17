# Cryptocurrency Market Prediction Using Machine Learning

## Overview
This project explores the efficiency of machine learning algorithms in predicting fluctuations in the cryptocurrency market. The focus is on analyzing various models, including LSTM (Long Short-Term Memory), regression, random forest, and SVM, to understand their effectiveness in forecasting cryptocurrency prices. 

**Key Features:**
- Utilizes a time-series dataset (2013–2021) for several cryptocurrencies.
- Implements advanced machine learning models with a focus on LSTM for sequential data analysis.
- Demonstrates the volatility and challenges of predicting cryptocurrency markets.

---

## Dataset
The dataset includes daily closing prices of cryptocurrencies from 2013 to 2021. It can be downloaded from Kaggle:  
[Every Cryptocurrency Daily Market Price](https://www.kaggle.com/).

---

## Prerequisites
Ensure the following tools and libraries are installed:
- Python 3.7+
- Scikit-learn
- Keras
- TensorFlow
- Jupyter Notebook or Google Colab
- Pandas, Numpy, Matplotlib, Seaborn

---

## How to Run
1. **Download the Dataset**  
   - Obtain the dataset from Kaggle and unzip it locally.
   
2. **Set Up the Environment**  
   - Install the required Python libraries:
     ```bash
     pip install scikit-learn keras tensorflow pandas matplotlib seaborn
     ```

3. **Execute the Notebook**  
   - Use Google Colab or Jupyter Notebook to run the provided script:
     - Upload the CSV dataset file when prompted.
   - The script will process the data, train the models, and display results.

---

## Results
The project evaluates the performance of different machine learning models:
- **Accuracy:** 50–60%, reflecting market volatility.
- **Best Model:** LSTM (due to suitability for time-series data).
- Evaluation metrics include RMSE and MAPE.

**Key Insights:**
- Short-term price movements can be reasonably predicted using machine learning.
- LSTM models outperform others for time-series prediction.
- Potential for extending predictions to minimize trading costs.

---

## Technologies Used
- **Languages:** Python
- **Frameworks:** TensorFlow, Keras
- **Libraries:** Scikit-learn, Pandas, Matplotlib
- **Platforms:** Jupyter Notebook, Google Colab

---

## Future Work
- Improve LSTM models with techniques like dropout layers for regularization.
- Combine sentiment analysis with price prediction models.
- Extend research to include socio-economic factors influencing cryptocurrency prices.

---

## Acknowledgments
- **Research Team:** Lumiere Research Team  
- **Mentor:** Emily Kim, Doctoral Researcher at Carnegie Mellon University Robotics.

---

## References
1. Sebastião, H., & Godinho, P. (2021). *Forecasting and trading cryptocurrencies with machine learning under changing market conditions*. Financial Innovation.  
2. Alessandretti, L., et al. (2018). *Anticipating cryptocurrency prices using machine learning*. Complexity.  
3. Akyildirim, E., et al. (2020). *Prediction of cryptocurrency returns using machine learning*. Annals of Operations Research.  
4. Kaggle Dataset: *Every Cryptocurrency Daily Market Price*.
