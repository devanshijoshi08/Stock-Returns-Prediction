# LSTM Stock Returns Predictor

### Project Overview
This project focuses on utilizing Long Short-Term Memory (LSTM) networks, a type of recurrent neural network, to forecast stock market returns for the AAPL Stock. By analyzing historical stock data, this model aims to predict future stock returns, providing valuable insights for investors and financial analysts.

### Installation

To set up the project environment, run the following commands:
```bash
git clone https://github.com/devanshijoshi08/Stock-Returns-Prediction.git
cd repository-name
pip install -r requirements.txt
```

### System Requirements 
The project was run on a system with the following configurations:
GPU: 8 GB RTX 4070 
RAM: 16 GB 
Processor: i7 13th Generation Intel
The python compiler was set up to run on the GPU. 

### Usage
To run the LSTM model training and evaluation, open and run the `Stock_Return_Prediction.ipynb`.

### Methodology

#### Data Collection
Quantitative high-frequency stock market data from 2022 to 2024 was sourced, including metrics like open price, close price, volume, and technical indicators.

#### Data Preprocessing
Data was scaled and transformed to ensure it was suitable for analysis with LSTM. Technical indicators such as EMA, MACD, and RSI were calculated for feature engineering.

#### Model Configuration
Several LSTM configurations were tested:
- Vanilla LSTM
- Stacked LSTM
- Bidirectional LSTM
Each model was evaluated based on RMSE and Huber loss to gauge performance.

### Results

Our experiments with different LSTM configurations revealed varying levels of accuracy in predicting stock returns. The best-performing model achieved an RMSE of approximately 0.000072 on the test dataset.

### Conclusion

LSTMs have proven effective in modeling complex patterns in stock price data, though challenges like model overfitting and hyperparameter tuning persist. Future work will focus on refining the models to enhance their predictive accuracy and robustness.
