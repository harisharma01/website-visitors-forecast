# Website Visitors Forecast using Facebook Prophet

### Objective
Use Prophet to forecast the unique visitor amount of a website in Europe. Having insights on the current data and into the future help us and our clients adjust in advance.

### FbProphet
Fbprophet is a open source library for time series forecasting that was developed by Facebook. It is built on top of the Python library pandas and is designed to make it easy to incorporate historical data and make forecasts for future time periods.

fbprophet uses a decomposable time series model with three main components: trend, seasonality, and holidays. The trend component models the underlying growth or decay in the data over time, while the seasonality component models repeating patterns that occur at a fixed frequency (e.g. daily, weekly, monthly). The holidays component allows the model to account for effects that occur at specific times (e.g. Christmas sales).

fbprophet includes a number of convenient functions for working with time series data, such as automatic generation of plots and summary statistics, and support for missing data and outliers. It also includes functions for tuning the model's hyperparameters and for evaluating the model's performance.

fbprophet is well-suited for a wide range of time series forecasting tasks, including business forecasting, economic forecasting, and forecasting of other types of data with seasonal patterns. It is particularly useful for cases where there is a need to make forecasts for a large number of related time series, such as forecasting demand for a product in multiple regions.

### Data Description
Column	Description
year |Year to which the data belongs datepart| Date on which unique visitors surfed the website Country | Country of the users unique_visitors |Count of unique visitors who visted on the given date
