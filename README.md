# Predict vn30 stock price using lstm

## Description
> Data was collected on financial website from 01/2022 to 11/2024. I use VN30 index as data for the problem in which VN30 is the top 30 stocks in VietNam. After collecting the data, I will preprocess it and put it into the LSTM model for training and evaluation.

## Authors
**Author**: Vy Vyllie

## Content

### Dataset

The dataset has the following properties: 
```text
Date,"Price","Open","High","Low","Vol.","Change %"
11/29/2024,"1,311.26","1,301.34","1,311.67","1,298.64","136.47M","0.75%"
11/28/2024,"1,301.52","1,305.79","1,310.41","1,298.43","145.66M","0.04%"
11/27/2024,"1,301.06","1,297.28","1,303.99","1,296.94","113.49M","0.14%"
....
01/07/2022,"1,532.24","1,548.77","1,550.47","1,532.24","200.63K","-0.82%"
01/06/2022,"1,544.95","1,542.34","1,554.97","1,541.19","231.96K","-0.07%"
01/05/2022,"1,546.01","1,559.33","1,562.93","1,546.01","222.22K","-0.82%"
01/04/2022,"1,558.87","1,536.45","1,562.54","1,536.45","207.49K","1.51%"
```

### Price chart: Show prices by month
![Image](https://github.com/vyllie333/VN30-Stock-Price-Prediction-With-LSTM/blob/master/Image/visualize.png)

### Model
![Image](https://github.com/vyllie333/VN30-Stock-Price-Prediction-With-LSTM/blob/master/Image/LSTM.png)

### Evaluate: Based on R-square, RMSE, MSPE, MAPE
![Image](https://github.com/vyllie333/VN30-Stock-Price-Prediction-With-LSTM/blob/master/Image/predict.png)












