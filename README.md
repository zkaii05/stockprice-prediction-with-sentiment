# stockprice-prediction-with-sentiment
Predicts stock price's closing price with consideration of recent news.

Trained using Disney stock price, the initial model predicts the stock's closing price based on the previous day's opening, highest and lowest.

The model is trained using the random forest method, achieving a high R^2 value at 0.98.

The model is then fine-tuned with the "recent news analysis" model which captures the sentiment of news with or against the target company.
This is important as it is found that with positive news, there is fluctuation in the market, maximizing earnings.

This improves the accuracy of the model from 0.98 to 0.99
