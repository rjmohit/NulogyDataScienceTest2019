# Predicting customer demand for SKUs at a Retail Store

## Data to collect:
1. Transaction level data for the last few years, i.e. collect and save data for the whole transaction that could include several SKUs purchased by the customer
2. It would also include elements like a datetime stamp, amount paid for each item and the number of units for each item as well as store location
3. Any customer level info to connect the transactions over time to a particular individual would be great too
4. Having some sense of the market (like a recession) might help predicting demand for some SKUs

## Features to be engineered:
1. Commonly bought together SKUs
2. Seasonality elements
3. Depending on the forecast horizon, some features like time of the day, day of the week, etc could become important
4. Also depending on the modeling technique, some additional features might need to be generated. E.g. a time series model like ARIMA(X) would use very different featues compared to a linear model like regression

## Performance Assessment:
1. Performance of the model would be assessed based on its predicting prowess on the holdout sample
2. Other considerations like picking up on increasing/decreasing demand (i.e. directional accuracy) would also help in its performance assessment
