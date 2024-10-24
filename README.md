

# Bitcoin Price Prediction using Machine Learning (LSTM)

This project aims to predict the price of Bitcoin using machine learning techniques, particularly Long Short-Term Memory (LSTM) models. The framework uses on-chain data and change point detection to improve the accuracy of predictions for this volatile cryptocurrency.


## Introduction

Bitcoin's price is highly volatile, making it difficult for investors to predict market trends. This project addresses that issue by developing a prediction model based on LSTM Recurrent Neural Networks (RNN) and an attention mechanism. We use change point detection to segment time-series data and on-chain data to improve prediction accuracy.

### Key Features:
- LSTM model for time-series prediction
- On-chain data as input for more reliable predictions
- Real-time updates with new data

## Technologies Used

- **Programming Language:** Python 3.6.2
- **Frameworks:** TensorFlow, Keras
- **Libraries:** NumPy, Pandas, Matplotlib, Scikit-learn
- **Data:** On-chain Bitcoin data
- **Prediction Model:** Long Short-Term Memory (LSTM)

## Project Setup

### Hardware Requirements:
- Intel i3 or above
- 4GB RAM or above
- 40GB Hard Disk

### Software Requirements:
- Python 3.6.2 or above
- Operating System: Windows 8 or above



## Project Structure

- `data/`: Contains the datasets used for training and testing.
- `models/`: Contains pre-trained models.
- `scripts/`: Contains scripts for data preprocessing, model training, and evaluation.
- `notebooks/`: Jupyter notebooks for experimentation and visualization.
- `README.md`: This file.

## Modules

### User
- Registers and logs in.
- Buys cryptocurrencies.
- Views transaction history and price predictions.

### Agent
- Registers and logs in.
- Buys Bitcoin, Ripple, and Ethereum.
- Views transaction history.

### Admin
- Manages user and agent registrations.
- Updates cryptocurrency rates.
- Monitors current transactions.

## Conclusion

This project successfully predicts Bitcoin prices with high accuracy by using LSTM models and change point detection. It can serve as a powerful tool for investors to make informed decisions in the volatile cryptocurrency market.

