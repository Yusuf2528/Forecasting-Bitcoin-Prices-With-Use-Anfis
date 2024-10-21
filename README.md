# Forecasting-Bitcoin-Prices-With-Use-Anfis


### Brief Description

- ANFIS (Adaptive Neuro-Fuzzy Inference System) is a model created by combining artificial neural networks and fuzzy logic. Using ANFIS on financial time series data, such as Bitcoin price prediction, is ideal for better modeling the uncertain and complex nature of the data.

### Data Collection
- Historical Bitcoin prices (opening, closing, high, low prices) and volume data are used.
In addition, data such as macroeconomic indicators and market sentiment can also be included in the model.

### Data Preprocessing
- Filling in missing data and normalizing data.
Data is processed sequentially to create time series data (e.g. forecasting the next day using data from the last 30 days).

### Model Setup
- Input data are transformed into fuzzy sets (e.g. “Low”, “Medium”, “High” price categories).
The Sugeno-type ANFIS model learns the relationship between inputs and outputs.
During the training process, the model learns like a neural network and minimizes the error function.

### Model Training and Testing
- The model is optimized with training data and then its performance is evaluated with separate test data.
Accuracy is analyzed with error measures such as RMSE (Root Mean Square Error) or MAE.

### Forecasting
- Once the model is trained, the Bitcoin price is predicted based on the new data.

### Tools and Technologies

- In order to make this project matlab, python, collab, visual studio code have been used.


### Project Architecture

- In order to make this project following architecture have been created.

<p align="center">
  <img width="700" height="400" src="C:\Users\YUSUF ÖZCAN\Pictures\resim1.PNG">
</p>
