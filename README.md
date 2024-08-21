###### **Crypto Price Prediction with LSTM**
#### **Overview**
This project predicts cryptocurrency prices using Long Short-Term Memory (LSTM) neural networks. It uses historical price data of Bitcoin (BTC) against USD (USD) to train the model and predict future prices. The project involves data fetching, preprocessing, model training, and evaluation.

#### **Features**
Data Fetching: Downloads historical cryptocurrency data using Yahoo Finance.
Data Preprocessing: Scales the data and prepares it for training.
Model Training: Uses LSTM layers to predict future prices.
Visualization: Plots actual vs. predicted prices.

#### **Installation Requirements**
Python 3.x
numpy
pandas
matplotlib
yfinance
tensorflow
sklearn

#### **Install Dependencies**
You can install the required packages using pip:
bash
Copy code
pip install numpy pandas matplotlib yfinance tensorflow sklearn

#### **Usage**
Fetch Data: Historical BTC-USD data is fetched from Yahoo Finance.
Preprocess Data: Scales the data and prepares it for LSTM.
Train Model: An LSTM neural network is trained to predict future prices.
Test and Predict: The model is tested on recent data and predictions are made.
Visualize Results: Actual and predicted prices are plotted for comparison.

#### **Running the Code**
To run the script, simply execute it with Python:
bash
Copy code
python main.py

#### **Visualization**
Description: The plot shows the actual and predicted prices for Bitcoin. The black line represents the actual prices, and the red line shows the predicted prices.
<img width="956" alt="Crypto Price Prediction Graph" src="https://github.com/user-attachments/assets/3088cf8d-20f8-4653-a2f3-d2135d8b3f07">
