# Stock-Price-Forecasting
This project is to forecast Bank BCA stock price using an LSTM Neural Network using Tensorflow Keras. The net is structured as 60 -> 256(LSTM) -> 128(LSTM) -> 1 fitted using the adam optimizer. The result root-mean-squared error on the validation data is Rp. 157.65. For comparison, the same data trained on Facebook's Prophet model results in root-mean-squared error of Rp. 811.84. Code for each is given above. Graph of the results on the validation set can be seen below:
![lstm_forecasting](https://github.com/user-attachments/assets/81c2cb85-a59b-409b-9b8f-1061ebfe68e0)
![prophet_forecasting](https://github.com/user-attachments/assets/60fcfbc3-68cd-4f28-af6c-1a24eb33ffd7)
