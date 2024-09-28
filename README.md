# Executive Summary
This project, conducted in my Programming for Business Analytics class, focused on using R and Python to analyze business data through functions, models, and visualizations. Initially completed in Python, I reworked it in R, utilizing a dataset of Costco and Meta's year-to-date stock prices from October 2023 to September 2024. Originally, a homework assignment done with only Costco stock prices I was surprised to see how well their stock performed so I wanted to explore how their stock prices and Simple Moving Averages (SMA) compared to companies like Meta. Given that Meta is larger known company the average person like me would assume that they would do better than Costco. I cleaned, formatted, and analyze trends using 10-day and 50-day SMAs to predict stock performance. By employing summary statistics, visualizations, and linear regression, I identified and reported trends on how SMA influences stock performance. I was able to see that closing stock prices are influenced by time and Simple Moving Averages (SMA10 and SMA50), the shorter the SMA the better the stock performed. 

## Description of the data
Data was pulled from Yahoo finance. I calculated the Simple Moving Averages on a 10 and 50 day window.

|Variable|Description|
|:---|:---|
|Date|Date formatted|
|CLOSE|Closing stock price|
|SMA_10|Calculated moving average on a 10 day window|
|SMA_50|Calculated moving average on a 50 day window|

## Conclusion
On average Costco stock price and Simple Moving Averages outperformed Meta's. 

## Next Steps
In the future, I would like to see how their stocks perform in comparison to other companies in similar industries such as comparing Metas SMAs to Nvidia/Twitter or Costco's SMAs to Walmart. 
