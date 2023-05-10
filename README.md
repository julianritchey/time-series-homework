# time-series-homework
Module 11 Challenge: Forecasting Net Prophet

## Find Unusual Patterns in Hourly Google Search Traffic
### Code block 5 (line plot)
- Plot depicts the hourly search trends for May 2020.

### Question: Do any unusual patterns exist?
**Answer:** There is a spike in trends over two (2) days during the first week of May.

### Code block 8 (bar plot)
- Plot depicts the comparison of the total search traffic for May 2020 versus the median of all monthly totals.

### Question: Did the Google search traffic increase during the month that Mercado Libre released its financial results?
**Answer:** Yes, by roughly 3000 points.

## Mine the Search Traffic Data for Seasonality

### Code block 9 (line plot)
- Plot depicts the average daily search trends for the entire dataset.

### Code block 10 (heatmap plot)
- Plot depicts the average volume of search traffic for each hour of each day for the entire dataset.

### Question: Does any day-of-week effect that you observe concentrate in just a few hours of that day?
**Answer:** The greatest volume periods appear to occur Tuesday through Thursday, between hour 23 of the day prior through hour 1 of the day.

### Code block 11 (line plot)
- Plot depicts the average weekly search trends for the entire dataset.

### Question: Does the search traffic tend to increase during the winter holiday period (weeks 40 through 52)?
**Answer:** From an annual low at week 37, search traffic tends to increase through to a quarterly peak at week 51.

## Relate the Search Traffic to Stock Price Patterns

### Code block 13 (line plot)
- Plot depicts the hourly closing stock price for the entire dataset.

### Code block 16 (line plots)
- First plot depicts the hourly closing stock price for the first half of 2020.
- Second plot depicts the hourly search trends for the first half of 2020.

### Question: Do both time series indicate a common trend that’s consistent with this narrative?
**Answer:** Yes. Both time series indicate a steady increase following the market drop in early March, 2020.

### Code block 19 (line plot)
- Plot depicts the hourly stock price volatility for the entire dataset.

### Question: Does a predictable relationship exist between the lagged search traffic and the stock volatility or between the lagged search traffic and the stock price returns?
**Answer:** There is a moderate negative correlation between lagged search trends and stock volatility. There is a weak negative relationship between lagged search trends and hourly stock return.

## Create a Time Series Model by Using Prophet

### Code block 28 (mixed plots)
- Plots depict the hourly search trends for the original dataset, as well as the predicted search trends for the next 2,000 hours (approximately 80 days).

### Question: What is the near-term forecast for the popularity of Mercado Libre?
**Answer:** A dip is forecasted for the near-term popularity of Mercado Libre.

### Code block 30 (line plot)
- Plot depicts the hourly search trends for the predicted, 2,000-hour timeframe.
- Lines include:
  - Most likely scenario (yhat).
  - Worst-case scenario (yhat_lower).
  - Best-case scenario (yhat_upper).

### Code block 31 (line plots)
- First plot depicts the average search trends for the entire dataset (original timeframe and the predicted timeframe).
- Second plot depicts the average search trend variation by day of the week for the entire dataset.
- Third plot depicts the average search trend variation by day of the year for the entire dataset.
- Fourth plot depicts the average search trend variation by hour of the day for the entire dataset.

### Question: What time of day exhibits the greatest popularity?
**Answer:** 00:00:00 (midnight).

### Question: Which day of the week gets the most search traffic?
**Answer:** Tuesday.

### Question: What's the lowest point for search traffic in the calendar year?
**Answer:** Mid-October.

## Forecast the Revenue by Using Time Series Models

### Code block 33 (line plot)
- Plot depicts the daily sales for the entire dataset.

### Code block 38 (line plots)
- First plot depicts the linear daily sales trend for the entire dataset.
- Second plot depicts the average sales variation by day of the week for the entire dataset.

### Question: For example, what are the peak revenue days?
**Answer:** Wednesdays.

### Code block 39 (line plot)
- Plot depicts the daily sales for the predicted, 90-day timeframe.
- Lines include:
  - Most likely scenario (yhat).
  - Worst-case scenario (yhat_lower).
  - Best-case scenario (yhat_upper).

### Produce a sales forecast for the finance group. Give them a number for the expected total sales in the next quarter. Include the best- and worst-case scenarios to help them make better plans.
The expected total sales for next quarter are USD 969 million. A best-case scenario sees next quarter's total sales reach USD 1,051 million, whereas a worst-case scenario sees next quarter's total sales reach USD 887 million.

## Other information
- All work can be found in the [forecasting_net_prophet.ipynb](https://github.com/julianritchey/time-series-homework/blob/main/forecasting_net_prophet.ipynb) file.
- All data used in this assignment can be found in the [Resources](https://github.com/julianritchey/time-series-homework/tree/main/Resources) folder.