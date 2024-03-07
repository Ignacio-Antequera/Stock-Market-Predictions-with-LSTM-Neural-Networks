# Stock Price Predictions with LSTMs and Averaging Techniques

## Overview
This project explored the potential of various methods for stock price prediction, including averaging techniques and LSTM neural networks. While the project primarily serves as an educational exercise highlighting the capabilities of different approaches, it also provides insights into the challenges and limitations of stock market prediction.

**Models and Techniques:**

* **Averaging Techniques**: Both standard averaging and exponential moving average (EMA) were employed for one-step ahead predictions. These methods are simple to implement and interpret, but their accuracy is limited, particularly for capturing complex market trends and unforeseen events.
* **LSTM Neural Networks**: This project showcased the application of a deep learning model, specifically an LSTM network, for longer-term stock movement predictions. LSTMs excel at capturing temporal dependencies within time series data. However, their performance heavily relies on the quality and quantity of available data, the choice of hyperparameters, and the overall model architecture.

**Tools and Technologies:**

* **Python**: The project utilized Python as the primary programming language, leveraging various libraries for data manipulation, visualization, model building, and evaluation. Key libraries included:
    * **NumPy**: Numerical computations and data manipulation
    * **Pandas**: Data analysis and manipulation
    * **Matplotlib**: Data visualization
    * **Scikit-learn**: Machine learning algorithms and tools (e.g., MinMaxScaler)
    * **Keras (with TensorFlow backend):** Deep learning framework for building and training the LSTM model
* **Data Sources**: The project utilized two data sources:
    * **Kaggle**: Publicly available historical stock price data for educational purposes.
    * **Alpha Vantage API**: Alternative data source requiring an API key (not used in this specific project due to educational focus).

**Evaluation and Results:**

* **Averaging Techniques**: Both averaging methods provided basic predictions, with EMA generally performing slightly better due to its weighting mechanism. However, their limitations were evident in their inability to capture significant market movements and potential trend reversals.
* **LSTM Neural Network**: The LSTM model showcased the ability to learn complex patterns within the data and generate predictions beyond one-step ahead. Nevertheless, the model exhibited limitations common to machine learning approaches:
    * **Sensitivity to data quality and quantity**: Larger and more comprehensive datasets can potentially improve performance.
    * **Hyperparameter tuning**: Tuning of various model parameters (e.g., number of layers, neurons, learning rate) can significantly impact prediction accuracy.
    * **Overfitting**: The model could potentially overfit the training data, leading to poor performance on unseen data.

**Overall, the project successfully explored various approaches to stock price prediction, highlighting the potential and limitations of each method. It serves as a reminder that the stock market is inherently complex and influenced by numerous interconnected factors, making accurate prediction a challenging task.**

**References:**

- [Datacamp](https://www.datacamp.com/tutorial/lstm-python-stock-market)
- [Predict-Stocks using LSTM - Kaggle](https://www.kaggle.com/code/dbdmobile/predict-stocks-using-lstm)

## Author
Kindly find my contact details listed below for your convenience. Your input is greatly appreciated.

Ignacio Antequera Sanchez

***

[LinkedIn](https://www.linkedin.com/in/ignacio-antequera)  ||  [GitHub](https://github.com/Ignacio-Antequera)  ||  [Leetcode](https://leetcode.com/Ignacio_antequera)