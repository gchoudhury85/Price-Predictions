

What problem is being solved:​

We have a regression problem at hand where we will try to predict the price of used cars based on several factors such as - Year of manufacturing, Number of seats, Mileage of car, etc.​

Key points that describe the final proposed solution:​

Power, Year and Engine seem to be the top three features reflecting feature importance​

Various algorithms were used to solve the above-mentioned regression problem​

Linear regression​

Ridge regression​

Decision tree​

Random forest​

Ridge regression was able to generalize very well compared to other algorithms​

Has the highest R-squared on the test data and the lowest RMSE on the test data when compared to other models that showed issues even after tuning​

Why is this a valid solution that is likely to solve the problem:​

   Our final Ridge Regression model has an R-squared of ~0.95 on the test data, which means that our model can explain 95% variation in our data. Also, the RMSE on test data is 0.18 which means we can predict very closely to the original values. This is a very good model, and we can use this model in production.
