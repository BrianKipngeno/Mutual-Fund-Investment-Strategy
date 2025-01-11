# Mutual-Fund-Investment-Strategy

# 📁 Project Overview

Mutual funds pool money from multiple investors to purchase a diversified portfolio of stocks, bonds, and other securities managed by professional fund managers. This project outlines the steps to create a long-term mutual fund plan using historical stock data.

# Key Steps

1. Data Collection: Gathering historical stock prices to analyze trends.
   
2. Risk and Return Analysis:
    - Calculating ROI to evaluate historical growth.
    -  Measuring volatility to assess investment risks.
  
3. Stock Selection: Filtering stocks with high ROI and low volatility.
   
4. Portfolio Optimization:
   
    - Allocating investments based on the Inverse Volatility Ratio.
  
    - Prioritizing stability while balancing risk and reward.
  
5. Simulating Returns: Estimating the future value of investments over various periods.

# 📊 Key Features and Insights

1. **Historical Data Analysis**

  - Analyzed historical stock prices from the Nifty 50 dataset.

  - Cleaned and preprocessed the dataset to address missing values using forward-fill imputation.

2. **Volatility and ROI Calculation**
   
  - Volatility: Measured the standard deviation of stock prices to identify high-risk companies.

  - ROI: Calculated the percentage change between the initial and final stock prices.

3. **Stock Selection Strategy**
   
  - Criteria: Selected stocks with ROI greater than the median and volatility lower than the median.

  - Investment Allocation: Assigned weights using the Inverse Volatility Ratio to prioritize stable investments.

4. **Portfolio Analysis**
   
  - Compared the risk and expected returns of the mutual fund portfolio to high-growth companies.

  - Visualized trade-offs between risk and reward for different stock groups.

5. ** Simulating Returns**

  - Estimated returns for investments of $1,000/month over 1, 3, 5, and 10 years using compounding principles.

  - Demonstrated the long-term benefits of a low-risk mutual fund strategy

# 🔧 Technologies Used

**Python**: Data analysis and visualization.

**Libraries**:

- pandas and numpy for data manipulation.
- matplotlib and seaborn for static visualizations.
- plotly for interactive visualizations.

# 📈 Key Visualizations
- **Stock Price Trends**: Illustrated historical trends of all companies in the dataset.
- **Volatility and ROI Comparison**: Bar charts comparing risk and return of selected companies vs. high-growth companies.
- **Investment Simulation**: Plots showing the projected returns of monthly investments over time.

# 🚀 Results and Insights

**Balanced Portfolio**: The mutual fund portfolio offers a lower-risk alternative to investing in high-growth but volatile stocks.

**Stable Returns**: Ideal for long-term, conservative investors seeking consistent growth without significant fluctuations.

**Risk-Reward Trade-off**: Demonstrated the balance between achieving stable returns and minimizing investment risk.

# 📂 Dataset
The project uses historical stock price data from the Nifty 50 Closing Prices Dataset.

# 🛠️ Future Improvements

Expand analysis to include other global indices for broader diversification.

Introduce advanced portfolio optimization techniques, such as Sharpe Ratio or Modern Portfolio Theory.

Automate investment simulation for real-time data updates.

# 📬 Contact
For questions or collaboration opportunities, feel free to reach out:

Author: Brian Kipngeno

Email: briankosgey@gmail.com
