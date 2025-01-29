# Microsoft Stock Price Forecasting using LSTM

## Overview
This project implements a Long Short-Term Memory (LSTM) neural network model to predict Microsoft (MSFT) stock prices. The model analyzes historical stock data to forecast future price movements, utilizing deep learning techniques for time series prediction.

## Features
- Historical stock data analysis
- LSTM-based price prediction model
- Data preprocessing and normalization
- Time series analysis
- Visualization of predictions vs actual prices

## Technologies Used
- Python
- TensorFlow/Keras
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Installation
1. Clone the repository:
```bash
git clone https://github.com/yourusername/Stock-Prediction-Microsoft.git
cd Stock-Prediction-Microsoft
```

2. Install required dependencies:
```bash
pip install -r requirements.txt
```

## Usage
1. Open the Jupyter notebook:
```bash
jupyter notebook Microsoft_Stock_Forecasting_with_LSTMs.ipynb
```

2. Follow the notebook cells sequentially to:
   - Load and preprocess the stock data
   - Build and train the LSTM model
   - Generate predictions
   - Visualize results

## Data
The project uses historical Microsoft stock price data, including:
- Opening price
- Closing price
- High and low prices
- Trading volume
- Date information

## Model Architecture
- LSTM neural network
- Multiple stacked LSTM layers
- Dropout layers for regularization
- Dense output layer for price prediction

## Results
The model's performance is evaluated using:
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- Visual comparison of predicted vs actual prices

## Contributing
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


## Acknowledgments
- Data source: Yahoo Finance
- Inspiration: Deep Learning for Time Series Forecasting
- LSTM architecture references

## Contact
Harshim Saluja - harshimsaluja1@gmail.com
Project Link: https://github.com/harshim1/Stock-Prediction-Microsoft
