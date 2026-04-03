📊 Financial Risk Analysis & Portfolio Modeling

📌 Overview

This project focuses on analyzing financial market data and evaluating portfolio risk using statistical and quantitative methods. It applies concepts from data analytics, probability, and finance to estimate potential losses and understand market behavior.

⸻

🎯 Objectives
	•	Analyze stock price data and compute daily returns
	•	Study statistical properties of financial returns
	•	Estimate risk using Value at Risk (VaR) and Conditional VaR (CVaR)
	•	Compare different risk models
	•	Evaluate portfolio performance and drawdowns

⸻

🧰 Tools & Technologies
	•	Python
	•	Pandas
	•	NumPy
	•	Matplotlib
	•	Seaborn
	•	SciPy
	•	yFinance (for data extraction)

⸻

📊 Data
	•	Stock data for: AAPL, MSFT, AMZN, GOOGL
	•	Time period: May 2024 – June 2025
	•	Source: Yahoo Finance API

⸻

🔍 Key Steps

1. Data Collection
	•	Retrieved historical stock price data using yFinance

2. Data Cleaning
	•	Handled missing values
	•	Structured dataset for analysis

3. Feature Engineering
	•	Converted stock prices into daily log returns

4. Exploratory Data Analysis (EDA)
	•	Summary statistics (mean, variance, skewness, kurtosis)
	•	Distribution analysis using histograms
	•	Correlation heatmap

5. Statistical Modeling
	•	Fitted Normal and Student’s t-distributions
	•	Compared distribution fit for financial returns

6. Risk Analysis
	•	Calculated Value at Risk (VaR) using:
	•	Parametric (Normal)
	•	Parametric (Student’s t)
	•	Historical method
	•	Computed Conditional VaR (CVaR)

7. Portfolio Analysis
	•	Correlation and diversification analysis
	•	Portfolio return calculation
	•	Risk comparison

8. Drawdown Analysis
	•	Maximum drawdown
	•	Recovery time analysis

9. Backtesting
	•	Validated VaR model accuracy using exception rate

⸻

📈 Key Insights
	•	Financial returns do not follow a normal distribution (fat tails observed)
	•	Student’s t-distribution provides a better fit for risk estimation
	•	High correlation between stocks reduces diversification benefits
	•	Historical models capture real-world risk better than normal assumptions
	•	Portfolio experienced significant drawdowns with slow recovery

⸻

🚀 Conclusion

This project demonstrates how statistical methods and data analytics can be used to assess financial risk and improve decision-making. It highlights the importance of using realistic models for analyzing market behavior.

⸻

🔗 Future Improvements
	•	Include more diverse assets for better diversification
	•	Implement machine learning models for prediction
	•	Add interactive dashboards using Power BI
