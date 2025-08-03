# Affiliate-Monthly-Forecasting
This project demonstrates monthly affiliate forecasting using both Excel and Python (Google Colab) with Linear Regression models.

# The Excel Way:
Used the FORECAST.LINEAR() formula to predict future values for the month of July 2025 based on past data. A line chart with trendlines visualizes the actual and forecasted value (for July2025) for MoM % Growth (Revenue,Spend,ROAS) and 3-Month Avg (Revenue,Spend,ROAS)

# The Google Colab Way:
Used a LinearRegression model from sklearn is used to achieve the same prediction, offering flexibility for further model tuning and automation.
The Matplotlib library is also used to visualize historical and predicted data through clear, informative charts.

# FB Prophet_Data Science Model :
This model uses Facebook's open-source time series forecasting tool, Prophet, to predict Revenue trends for affiliate marketing. Trained on historical monthly data, the model identifies seasonality, trend patterns, and growth rates to generate a forecast for July 2025. The output includes predicted Revenue for July 2025 helping decision-makers plan affiliate budget and performance targets accurately.
