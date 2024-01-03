
# Stock Price Predictions Using Recurrent Neural Networks (RNNs)

## Introduction
Welcome to the GitHub repository for my project Stock Price Predictions using Recurrent Neural Networks (RNNs). This project explores the challenges developing and applications of RNNs in predicting the future prices of stocks based on historical data. Project's aim is to provide a comprehensive analysis of challenges related to different aspcets of model development as well as a reliable prediction model.

## Project Description
In this project, I have developed a machine learning model using RNN to predict stock prices. My approach involves analyzing historical stock market data and applying RNN algorithms to forecast future stock prices. The project focuses on the use of deep learning techniques to understand and predict stock market behavior.

### Problem Statement
Predicting stock prices is a complex task due to the volatile nature of the stock market. My goal is to create a model that can accurately forecast future stock prices based on historical data, using Recurrent Neural Network and, throughout the process, analyze the challenges associated with this process.

### Data Source
The dataset used in this project is sourced from Kaggle and comprises historical stock market data for 5885 stocks, totaling 2.34 GB. This extensive dataset allows for a thorough analysis and testing of the RNN model.

### Technical Details
- **Model Architecture**: The model consists of a two-layer neural network with an RNN layer featuring 140 units with RELU activation and a dense output layer with 1 unit.
- **Model Compilation**: The model is compiled using the Adam optimizer and the Mean Squared Error (MSE) loss function.

## Key Findings
- **Accuracy**: The model achieved a directional accuracy of 87% in predicting stock price movements.
- **Feature Types**: Analysis revealed that raw data (absolute prices) is more accurate for predictions than deltas (price changes).
- **Feature Set**: Resultant most efficient feature set contained three types of features being close price, adjusted close price and volume.
- **Data Insights**: The latest 40 days of data are crucial in predicting future stock price movements.

## Challenges and Solutions
During the project, I faced and overcame several challenges:
- **Balance of Accuracy and Efficiency**: Achieving a balance between the accuracy of predictions and the time efficiency of the model training process.
- **Optimization**: Code optimization for Google Colab to prevent crash-related data loss.
- **Data Cleaning**: Dealing with missing data in the dataset.

## Evaluation and Trading
The project includes the implementation of a simple trading strategy based on the predictions made by the model. This strategy demonstrated positive, albeit modest, returns, indicating the practical applicability of the model in real-life scenarios.

## Conclusion
This project successfully demonstrates the use of Recurrent Neural Networks in predicting stock prices. The insights and methodologies developed here can be applied to similar problems in financial analysis and prediction.

## Additional Information
For more details on methodologies, data analysis, and specific results, please refer to the full project report in this repo.
