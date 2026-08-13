# Apple Stock Market Performance Analysis (2020–2026)

## Project Overview

This project analyzes Apple's (AAPL) historical stock market performance from 2020 to 2026 using Python and financial data analysis techniques.

The analysis explores price movements, returns, trading volume, volatility, moving averages, cumulative performance, maximum drawdown, correlations, and risk-return characteristics.

The goal is to transform historical stock market data into meaningful insights that demonstrate how Python can be used for financial and business analytics.

---

## Objectives

The project aims to:

- Analyze Apple's historical stock price performance.
- Identify major price trends and market movements.
- Examine daily and monthly returns.
- Measure stock volatility and risk.
- Analyze trading volume patterns.
- Evaluate moving averages and price momentum.
- Calculate cumulative returns and maximum drawdown.
- Investigate relationships between price, volume, and returns.
- Evaluate Apple's historical risk-return profile.
- Extract actionable insights from financial data.

---

## Tools & Technologies

- **Python**
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical computations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **Google Colab** – Development environment
- **Jupyter Notebook** – Interactive analysis

---

## Dataset

The analysis uses historical Apple stock market data covering the period:

**January 2020 – July 2026**

The dataset contains daily market information including:

- Date
- Open Price
- High Price
- Low Price
- Close Price
- Adjusted Close
- Trading Volume

The data was transformed and aggregated to support daily, monthly, and yearly analysis.

---

## Analysis Performed

### 1. Stock Price Trend

The historical closing price was analyzed to understand Apple's long-term price movement and identify major periods of growth and decline.

### 2. Daily Price Changes

Daily price changes were calculated to measure the absolute movement of Apple's closing price from one trading day to the next.

### 3. Daily Returns

Daily percentage returns were calculated to evaluate short-term performance.

Key results:

- Average Daily Return: **0.11%**
- Maximum Daily Gain: **15.33%**
- Maximum Daily Loss: **-12.86%**

### 4. Moving Average Analysis

7-day and 30-day moving averages were calculated to identify short-term and medium-term price trends.

Moving averages help smooth daily price fluctuations and provide a clearer view of the underlying trend.

### 5. Daily Trading Range

The daily trading range was calculated as:

`High Price - Low Price`

Average Daily Trading Range:

**$3.82**

This provides an indication of the typical intraday price movement.

### 6. Trading Volume Trend

Trading volume was analyzed to understand changes in market activity and investor participation.

Key results:

- Average Daily Trading Volume: **81,609,278 shares**
- Maximum Trading Volume: **426,510,000 shares**
- Minimum Trading Volume: **17,910,600 shares**

### 7. Volume vs Daily Return

The relationship between trading volume and daily returns was examined using correlation analysis.

Correlation:

**0.0007**

This indicates an almost negligible linear relationship between daily trading volume and daily returns over the analyzed period.

### 8. Monthly Return Analysis

Monthly returns were calculated to identify the strongest and weakest monthly performance periods.

Key results:

- Highest Monthly Return: **22.74% — August 2020**
- Lowest Monthly Return: **-15.69% — March 2020**

### 9. Cumulative Return

Cumulative performance was calculated to evaluate the overall growth of the investment over the analysis period.

Final Cumulative Return:

**311.40%**

This demonstrates substantial long-term historical appreciation during the period analyzed.

### 10. Maximum Drawdown

Maximum drawdown was calculated to measure the largest decline from a previous peak to a subsequent trough.

Maximum Drawdown:

**-33.43%**

This highlights the potential downside risk experienced during major market declines.

### 11. Correlation Analysis

A correlation matrix was created to examine relationships between the major financial variables.

Key observations:

- Close Price vs Volume: **-0.609**
- Close Price vs Daily Return: **0.013**
- Volume vs Daily Return: **0.001**
- Daily Price Change vs Daily Return: **0.923**
- Close Price vs Daily Range: **0.408**

The analysis shows that daily price changes and percentage returns have a strong positive relationship, while trading volume has very little relationship with daily returns.

### 12. Annual Performance

Yearly performance was analyzed from 2020 through 2026.

| Year | Average Close | Highest Close | Lowest Close | YoY Growth |
|------|---------------:|--------------:|-------------:|-----------:|
| 2020 | $95.35 | $136.69 | $56.09 | — |
| 2021 | $140.99 | $180.33 | $116.36 | 47.87% |
| 2022 | $154.84 | $182.01 | $126.04 | 9.82% |
| 2023 | $172.55 | $198.11 | $125.02 | 11.44% |
| 2024 | $207.21 | $259.02 | $165.00 | 20.09% |
| 2025 | $232.24 | $286.19 | $172.42 | 12.08% |
| 2026* | $280.69 | $340.08 | $246.63 | 20.86% |

\*2026 represents partial-year data through July.

Best Performing Year:

**2021 — 47.87% YoY growth**

Lowest Growth Year:

**2022 — 9.82% YoY growth**

---

## Risk & Performance Metrics

| Metric | Result |
|---|---:|
| Final Cumulative Return | **311.40%** |
| Average Daily Return | **0.11%** |
| Daily Volatility | **1.98%** |
| Annualized Return | **26.53%** |
| Annualized Volatility | **31.50%** |
| Risk-Return Ratio | **0.84** |
| Maximum Drawdown | **-33.43%** |
| Average Daily Trading Volume | **81.61M shares** |
| Volume/Return Correlation | **0.0007** |

---

## Key Findings

### Strong Long-Term Growth

Apple demonstrated substantial historical price appreciation during the analyzed period, resulting in a cumulative return of **311.40%**.

### Significant Volatility

Despite strong long-term performance, the stock experienced considerable short-term fluctuations, with annualized volatility of **31.50%**.

### Large Market Swings

The largest daily gain was approximately **15.33%**, while the largest daily loss was approximately **-12.86%**, demonstrating the potential for significant short-term movements.

### Strongest Annual Growth

2021 recorded the strongest year-over-year growth at **47.87%**.

### Trading Activity Declined

Average daily trading volume generally declined over the period, despite continued growth in Apple's average stock price.

### Limited Volume-Return Relationship

The correlation between trading volume and daily returns was only **0.0007**, suggesting that volume alone was not a meaningful linear predictor of daily returns within this dataset.

### Risk Accompanied Returns

The **-33.43% maximum drawdown** demonstrates that investors experienced substantial temporary declines despite the strong overall long-term return.

---

## Visualizations

The project includes visual analysis covering:

- Apple stock price trend
- Moving averages
- Daily price movements
- Trading volume trends
- Monthly returns
- Cumulative returns
- Maximum drawdown
- Correlation matrix
- Risk-return analysis

These visualizations make it easier to identify trends, volatility, market movements, and relationships within the data.

---

## Project Structure

```text
Apple-Stock-Market-Analysis/
│
├── README.md
├── requirements.txt
│
├── notebooks/
│   └── Apple_Stock_Market_Analysis.ipynb
│
└── visualizations/
    ├── price_trend.png
    ├── moving_average.png
    ├── trading_volume.png
    ├── monthly_returns.png
    ├── cumulative_returns.png
    ├── drawdown.png
    ├── correlation_matrix.png
    └── risk_return.png
How to Run the Project
1. Clone the Repository
git clone https://github.com/Lude71/Apple-Stock-Market-Analysis.git
2. Navigate to the Project
cd Apple-Stock-Market-Analysis
3. Install Dependencies
pip install -r requirements.txt
4. Open the Notebook

Launch Jupyter Notebook or upload the notebook to Google Colab.

jupyter notebook

Open:

notebooks/Apple_Stock_Market_Analysis.ipynb
Key Takeaway

The analysis demonstrates that Apple's stock delivered strong historical long-term growth between 2020 and 2026, but this performance was accompanied by substantial volatility and periods of significant drawdown.

The project highlights the importance of evaluating both return and risk when analyzing financial assets rather than relying solely on price appreciation.

Disclaimer

This project is intended for educational and analytical purposes only.

The analysis represents historical market data and should not be interpreted as financial advice, investment advice, or a recommendation to buy or sell Apple stock.

Past performance does not guarantee future results.

Author
Eliud Kigen

Telecommunication & Information Engineering Student
AnalystLab Africa
Data Analytics Enthusiast
