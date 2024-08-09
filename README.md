# Live Cryptocurrency Tracker Portfolio
##### Microsoft Excel Dashboard Link :https://1drv.ms/x/s!Ag6mtjywfT7ea0OoN_Rh3pwgFGw?e=ylYD3D

## Overview

The Cryptocurrency Portfolio Tracker is an advanced tool designed to help investors efficiently monitor and manage their cryptocurrency investments.

This project serves as a live tracker, providing real-time updates on the value of a diverse range of cryptocurrencies with a single refresh. Tailored for individuals or entities managing multiple coins or tokens, this tool offers a comprehensive overview of your portfolio's performance and assists in making informed future decisions.

![4](https://github.com/user-attachments/assets/0d80a375-857c-40b9-a8a9-801a86546d15)

![1](https://github.com/user-attachments/assets/42536d50-7809-4a99-9205-0a2aa8ab3c99)

![2](https://github.com/user-attachments/assets/fc2ea87c-e5ff-469f-83b4-66bd9375d1c2)







### Business Benefits

- Informed Decision-Making: Make strategic choices with confidence using real-time data and detailed performance metrics.
- Optimized Returns: Increase potential gains through up-to-date market insights and effective investment strategies.
- Effective Risk Management: Identify and mitigate high-risk investments to protect your portfolio.
- Comprehensive Performance Analysis: Assess which assets are thriving or lagging to understand and improve overall portfolio health.
- Customizable Portfolio: Easily incorporate any cryptocurrency to tailor the tracker to your specific investments and needs.


### Key Features
#### Dashboard Insights:
- Coin: The specific cryptocurrency held in the portfolio.
- Currency Amount Purchased: The total amount of each coin purchased.
- Date of Purchase: The acquisition date for each cryptocurrency.
- Total Invested Amount ($): The total capital invested in each coin.
- Bought coin value ($)

![1](https://github.com/user-attachments/assets/1d52cddd-377f-41ee-8824-1a3a218600bc)


#### Calculations:
- Current Value ($): The present market value of the holdings.
- Profit / Loss ($): The net gain or loss calculated as the difference between the current value and the total invested amount.
- % Return on Investment (ROI): The percentage return based on profit/loss relative to the total investment.
- 24h % Change: The percentage change in the value of the holdings over the last 24 hours.
- Current Price ($): The latest market price per coin.
- Daily Return on Investment: Calculated as ROI divided by the number of days the asset has been held.
![1](https://github.com/user-attachments/assets/c5103e89-c390-4b31-a0d0-08a934d8f0fc)


### Portfolio Metrics:
- COST: The sum of all investments in the portfolio.
- PROFIT/LOSS: The aggregated net gain or loss across all holdings.
- HOLDING: The total current value of the portfolio.
- 24H % CHANGE: The average 24-hour change across all assets.
- TOTAL ROI: The overall return on investment for the entire portfolio.
- WORST RETURN: The lowest performing investment in terms of profit/loss.
- BEST RETURN: The highest performing investment in terms of profit/loss.


![3](https://github.com/user-attachments/assets/57d53ca3-f606-4097-9584-503844248f37)

![2](https://github.com/user-attachments/assets/dc08a7c8-ced8-4333-9797-2d81da209da9)



### Acquisition cost with Profit/Loss:
- This graph displays the total investment and profit/loss for each cryptocurrency in the portfolio. It helps to compare initial investments against the current value to assess the performance of each coin.
- Rebalance Portfolio: If certain cryptocurrencies show significant losses compared to others, consider reallocating your investments to better-performing assets.
- Investment Strategy: Adjust future investments based on which coins are currently underperforming or overperforming, optimizing your portfolio to improve overall returns.

### ROI:
- This chart illustrates the ROI for each cryptocurrency, showing the percentage return on investment. It helps evaluate the efficiency and profitability of each investment in the portfolio.
- Adjust Holdings: Increase investments in cryptocurrencies with higher ROI and consider reducing or selling those with lower or negative returns.
- Identify Trends: Use ROI data to spot trends in performance and refine your investment strategy to focus on assets that consistently deliver strong returns.

### Portfolio - coin value:
- This graph provides a visual representation of the current value of each cryptocurrency in the portfolio. It helps in understanding the distribution of value among different cryptocurrencies and aids in portfolio assessment.
- Diversification: Evaluate the distribution of value among cryptocurrencies to ensure a balanced and diversified portfolio, minimizing risk.
- Track which cryptocurrencies are growing in value and adjust your investments to capitalize on promising assets, aligning with long-term financial goals.

### Methodology
To ensure accurate and up-to-date information, we connected the dashboard to the CoinGecko API, specifically using the get coin/markets endpoint to fetch live prices and 24-hour percentage changes. Data was integrated into the spreadsheet using Power Query, which allows for efficient transformation and analysis.

This setup enables users to easily extend the tool's capabilities to other coins or tokens by simply modifying the API call.

        By analyzing real-time data and trends, the tracker helps investors decide when to sell or hold 
        their coins, ensuring that decisions are backed by the latest market insights.
