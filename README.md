##  📈 Quantitative Analysis of Stock Market Using Python

### 🧠Background
Stock markets are inherently volatile and influenced by a wide range of economic, political, and psychological factors. Investors and analysts rely on quantitative analysis to derive actionable insights from historical price data. This project aims to evaluate the performance, volatility, correlation, and risk-return characteristics of major tech stocks—AAPL, MSFT, GOOG, and NFLX—over a selected time period.


### 💼 Business Problem
Investors need to make informed decisions about which stocks to include in their portfolios. However, without a systematic method to compare performance, volatility, and risk, investment strategies may be poorly optimized. This project addresses:

- Which stock demonstrated the best performance over the period?

- Which stock had the highest volatility (risk)?

- How correlated are these stocks with each other?

- Which stocks offered the best trade-off between risk and return?

### 🛠️ Methods
The following methods were used to explore and analyze the stock data:

1. **Descriptive Statistics**: Calculated mean, median, standard deviation, and percentile metrics for each stock’s closing prices.

2. **Time Series Analysis**: Visualized trends in closing prices over time using line plots.

3. **Volatility Measurement**: Quantified risk using standard deviation and visualized volatility across stocks with bar charts.

4. **Correlation Analysis**: Created a heatmap to show pairwise correlations between stocks' closing prices.

5. **Comparative Returns**: Computed overall percentage change in closing prices from the beginning to the end of the period.

6. **Risk vs. Return Profiling**: Analyzed daily returns and their standard deviations to assess each stock's investment quality.

### 📊 Results
- **Performance**:

    - **MSFT** showed the highest percentage gain (~16.1%) over the analyzed period.

    - **AAPL** followed with a gain of ~12.2%.

    - **NFLX** and **GOOG** experienced negative returns, with NFLX being the lowest performer.

- **Volatility**:

    - **NFLX** was the most volatile, followed by MSFT.

    - **GOOG** was the **least volatile**, indicating a relatively stable price movement.

- **Correlations**:

    - High positive correlation was observed between **AAPL** and **MSFT**, suggesting similar price movements.

    - **NFLX** exhibited lower correlation with the other stocks, indicating potential diversification benefits.

- **Risk vs. Return**:

    - **AAPL** had the **lowest risk with consistent positive returns**, making it a stable choice.

    - **MSFT** offered **higher returns but with increased risk**.

    - **NFLX** was **high-risk** and **underperforming**, suggesting poor short-term investment potential.

### ✅ Conclusion / Summary of Findings
This analysis provides investors with a clear comparison of stock behavior across key dimensions: performance, risk, and correlation.

- **AAPL** emerged as a strong low-risk option.

- **MSFT** delivered the best return but with moderate risk.

- **NFLX** showed high volatility and negative returns, making it less attractive for risk-averse investors.

- **GOOG** offered stability but lacked growth during the period analyzed.

By combining statistical analysis with visual tools, this project supports data-driven decision-making for stock selection and portfolio management.