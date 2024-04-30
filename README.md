Context
As an analyst at ABC Estate Wines, we are presented with historical data encompassing the sales of different types of wines throughout the 20th century. These datasets originate from the same company but represent sales figures for distinct wine varieties. Our objective is to delve into the data, analyze trends, patterns, and factors influencing wine sales over the course of the century. By leveraging data analytics and forecasting techniques, we aim to gain actionable insights that can inform strategic decision-making and optimize sales strategies for the future.

Objective
The primary objective of this project is to analyze and forecast wine sales trends for the 20th century based on historical data provided by ABC Estate Wines. We aim to equip ABC Estate Wines with the necessary insights and foresight to enhance sales performance, capitalize on emerging market opportunities, and maintain a competitive edge in the wine industry.

Define the problem and perform Exploratory Data Analysis
- Read the data as an appropriate time series data - Plot the data - Perform EDA - Perform Decomposition
The index added by the learner is incorrect. As the index must start from 1980-01-01, the first day of the month.	7/9
Data Pre-processing
- Missing value treatment - Visualize the processed data - Train-test split
Data is split into train and test as well as chart is prepared for the same.	4/4
Model Building - Original Data
- Build forecasting models - Linear regression - Simple Average - Moving Average - Exponential Models (Single, Double, Triple) - Check the performance of the models built
When we work on machine learning problems, if it is a standard or time series modeling problem. It is always advised to check the how the model is performing on both train and test data. The model metrics may look very promising on the training side but the real question comes, is it really a good model?. This is done by checking/comparing the results of model metrics on both train and test data. The model may be a good fit on training data and it should be a good fit on test data as well. That's why training data metrics do hold a valuable insight when we build our models in terms of performance. The RMSE tells you by how much units your model is wrong on the average which is checked by looking at the both train and test results. Hence, it is always necessary to check your metrics on the train data as well.	12/15
Check for Stationarity
- Check for stationarity - Make the data stationary (if needed)
Well done!. The overall answer is correct.	4/4
Model Building - Stationary Data
- Generate ACF & PACF Plot and find the AR, MA values. - Build different ARIMA models - Auto ARIMA - Manual ARIMA - Build different SARIMA models - Auto SARIMA - Manual SARIMA - Check the performance of the models built
Well done!. The overall answer is correct.	12/12
Compare the performance of the models
- Compare the performance of all the models built - Choose the best model with proper rationale - Rebuild the best model using the entire data - Make a forecast for the next 12 months
Well done!. The overall answer is correct.	6/6
Actionable Insights & Recommendations
- Conclude with the key takeaways (actionable insights and recommendations) for the business
In recognition of your insightful analysis and key takeaways, you are highly praised. Moving forward, you ensured the explicit inclusion of actionable recommendations to enhance the completeness and effectiveness of your analytical process. Keep up the excellent work!	4/4
