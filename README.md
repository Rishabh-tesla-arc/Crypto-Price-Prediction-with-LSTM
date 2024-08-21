###### **Crypto Price Prediction with LSTM**

#### **Overview**
This project predicts cryptocurrency prices using Long Short-Term Memory (LSTM) neural networks. It uses historical price data of Bitcoin (BTC) against USD (USD) to train the model and predict future prices. The project involves data fetching, preprocessing, model training, and evaluation.

#### **Features**
- **Data Fetching**: Downloads historical cryptocurrency data using Yahoo Finance.
- **Data Preprocessing**: Scales the data and prepares it for training.
- **Model Training**: Uses LSTM layers to predict future prices.
- **Visualization**: Plots actual vs. predicted prices.

#### **Installation Requirements**
- Python 3.x
- numpy
- pandas
- matplotlib
- yfinance
- tensorflow
- sklearn

#### **Usage**
1. **Fetch Data**: Historical BTC-USD data is fetched from Yahoo Finance.
2. **Preprocess Data**: The data is scaled and prepared for the LSTM model.
3. **Train Model**: An LSTM neural network is trained on the prepared data to predict future prices.
4. **Test and Predict**: The model is tested on recent data, and predictions are made for the test set.
5. **Visualize Results**: The script plots the actual versus predicted prices for comparison.

#### **Visualization**
Description: The plot shows the actual and predicted prices for Bitcoin. The black line represents the actual prices, while the red line shows the predicted prices.
<img width="956" alt="Crypto Price Prediction Graph" src="https://github.com/user-attachments/assets/a10254b9-5d37-4740-9b8f-9965a51b4155">


#### **Install Dependencies**
You can install the required packages using pip:
```bash
pip install numpy pandas matplotlib yfinance tensorflow sklearn



#### **Running the Code**
To run the script, simply execute it with Python:

```bash
python main.py

