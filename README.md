# Understanding the Effect of Economic Indicators on US Stock Market Returns
#### Business Problem
The stock market is sensitive to various macroeconomic factors, influencing investor decisions and portfolio strategies. This project aims to analyze the impact of economic indicators—like GDP, CPI, unemployment rates, and money supply—on US stock market performance. By identifying correlations and relationships, the study provides insights for investors with different risk appetites to make informed decisions.

#### Technical Details
* Data Sources:
  1. Stock Data: Yahoo Finance
  2. Economic Data: Federal Reserve Economic Development (FRED)
* Analysis Workflow:
  1. Data Cleaning and Merging
  2. Correlation Analysis (Seaborn visualizations)
  3. Multiple Linear Regression for impact analysis
  4. Performance evaluation with metrics (Mean Squared Error and R-squared)
* Model Results:
  1. Strong Correlations: GDP and Personal Consumption Expenditure (PCE) positively influence stock returns.
  2. Weak Correlations: Unemployment and core inflation have limited short-term effects on market performance.
* Market Index Insights:
  1. S&P 500: Best overall fit, balanced metrics.
  2. Dow Jones: Strong predictive power but higher error rates.
  3. Russell 3000: Least volatile, suitable for risk-averse investors.
* [Code](https://github.com/javeriamalik06/Adv-DS-and-Python-for-Finance/blob/main/Advanced%20Python%20for%20Finance%20Project%20Team%207%20Code%20file.ipynb) and [Report](https://github.com/javeriamalik06/Adv-DS-and-Python-for-Finance/blob/main/Understanding%20effect%20of%20econ%20indicators%20on%20market%20returns%20-%20Team%207.pptx) available.
* Technology: Python (Pandas, NumPy, Seaborn, Scikit-learn)

#### Recommendations
For risk-averse individuals, ETFs tracking diversified indices like Russell 3000 are ideal, offering stability against economic fluctuations. Risk-tolerant investors might prefer Dow Jones due to its high sensitivity to economic activity, yielding potentially higher returns.
