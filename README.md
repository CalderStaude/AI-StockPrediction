# AI-StockPrediction
AI program to predict stock prices.

Since the Covid-19 pandemic there has been an increasing amount of retail investors entering
the stock market. Though risky, the stock market has potential to increase one’s net worth due
to the return on investment having the potential to be higher than inflation and bank rates.
Therefore, being able to accurately predict prices for stocks trades on the New York Stock
Exchange (NYSE) would be beneficial for investors who are looking to invest for a better future
while reducing the risk that comes with the stock market. A Recurrent Neural Network with
Long Short-Term Memory (LSTM) with a many-to-one architecture was implemented to predict
the future price action of stocks. The project utilized PyTorch and NumPy to create the AI model
and Panda to hold the data used to train the model. Yahoo Finance API was used to retrieve
stock data, Matplotlib to create plots that represented the data and Si Kit Learn to create the
machine learning model. In addition, an application was created to demonstrate the project
and how the model worked. This GUI was created using Tkinter. After just 10 Epoch, the results
were relatively accurate with an error of approximately 3.219%. The model continued to
produced more accurate results with lower error as training continued. The trained model did
an efficient job in predicting the actual stock however, there were slight differences when
drastic changes occurred in the stock. Furthermore, the model had significantly poor
performance when predicting stocks with high volatility and was incapable of predicting longterm
stock performance. It is recommended to explore the implementation of multivariable
inputs to the dataset to enable the neural network to make much more accurate predictions.

Please read report for more details.
