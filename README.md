# Mutual-Fund-Analysis

This project is to analyze Nifty 50 closing prices to create a mutual fund plan based on high ROI and low risk.

# Overview
Objective of this project is to create a mutual fund investment plan based on high ROI and low risk using Python.

- Loaded Nifty 50 closing prices from a CSV file and converted the 'Date' column to datetime format. Checked for and confirmed no missing values in the dataset.
- Calculated the standard deviation of closing prices as a measure of volatility, the percentage change as a measure of growth rate, and the overall return on investment (ROI) for each company.
- Visualized stock price trends over time using line plots. Compared the risk and expected ROI of the selected mutual fund companies against high growth rate companies using bar plots.
- Observed that stock prices fluctuate over time, with some companies showing higher volatility than others. High growth rate companies tend to have higher volatility, while the selected mutual fund companies exhibit lower volatility and moderate returns, suitable for long-term, stable growth.
- Developed a mutual fund plan by selecting companies with ROI above the median and volatility below the median. Calculated investment ratios based on inverse volatility, giving higher weight to less volatile companies. Projected the accumulated value of monthly investments with annual increases over various time periods, demonstrating the power of compounding for long-term investors.
