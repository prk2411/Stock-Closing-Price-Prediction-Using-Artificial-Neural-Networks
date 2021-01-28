# Stock-Closing-Price-Prediction-Using-Artificial-Neural-Networks

Stock market basically refers to the collection of markets and exchanges, where shares of publicly owned companies are regularly bought, sold and issued under a formal setup. Prediction of returns associated with stock market is still a challenging task as the market dealing in such financial activities are often dynamic, volatile and non-linear in nature. Stock market predictions are affected by multiple factors including but not limited to political scenarios, international economy, the reports and performances of the company, anticipated takeover or merger, employee layoffs, future estimated earnings, etc. Hence, in order to maximise the company’s profit and lowering down the losses, stock market predictions are necessary. This could be analysed through the trend in the previous periods.

In our project paper, the focus was to use artificial intelligence and the computational capabilities to efficiently predict stock market prices. The Long Short-Term Memory (LSTM), XGBoost Regressor and Random Forest Regressor were the machine learning algorithms which was implemented to analyse the hidden patterns and complex relations between the variables affecting the stock market in 10 companies, namely, Starbucks, Microsoft, Cisco, Qualcomm, Facebook, Amazon, Tesla, Apple, Zynga, AMD. It is already proved that the use of machine learning algorithms in this field can raise the efficiency by 60-86 percent, so the purpose of this analysis is to contribute more towards accurate prediction pertaining to the stock market. We have also factored in the time series in our models to predict the closing price of the stock as it gives us better insights compared to normal regression models which does not consider the date feature which is an important aspect of the data, into the analysis.

![RMSE](./error_stock.PNG)

After the hypertuned models are trained, they produce significantly low error rate in all three models. XGBoostRegressor gives the lowest RMSE of 0.01 and maximum is LSTM with RMSE of 2.06

![Predict Stock](./predict_stock.PNG)
