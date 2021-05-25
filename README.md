# Sequence-Models
LSTM Model for Stock Price Prediction

Python IDE: Google colab

1. Download .csv from https://finance.yahoo.com/quote/GOOG/ to predict google stock prices
2. Keep only Date and Close columns for the prediction
3. Train Test Split - 80, 20
4. The data is a sequence, we need to convert it to Supervised data to feed it to the model **x<Variables> + y<Target>** with **look_back = 15**
5. Hyper Parameters: optimizer='adam', loss='mse', epochs = 25
  ![image](https://user-images.githubusercontent.com/49114626/119544789-b2b40200-bdaf-11eb-94cf-d07e7a9d1e46.png)
6. Predict for next month
  ![image](https://user-images.githubusercontent.com/49114626/119544893-ceb7a380-bdaf-11eb-8831-ab74212d6b7e.png)
