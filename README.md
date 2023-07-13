# Portfolio Management - Healthcare  Stocks

This project focuses on analyzing a portfolio of stocks using Modern Portfolio Theory (MPT) and comparing its performance against the S&P 500 benchmark index. The portfolio consists of multiple stocks from the healthcare industry.

## Project Steps

1. **Stock Selection:** The stocks in the portfolio were selected based on a specific rationale (not mentioned in the code). The selected stocks include ABT, AZN, DHR, ELV, GSK, JNJ, LLY, MRK, MRNA, NVO, NVS, PFE, RHHBY, and UNH.

2. **Portfolio Construction:** The portfolio was constructed using Modern Portfolio Theory (MPT) with one year of historical data (2020). The mean historical returns and the covariance matrix were calculated to optimize the portfolio weights.

3. **Value at Risk (VaR) and Conditional Value at Risk (CVaR):** The VaR and CVaR at a 99% confidence level were calculated for each trading day and week based on the portfolio returns in 2020. These measures provide insights into the potential losses at extreme levels of confidence.

4. **Forward Testing:** The portfolio's performance was forward-tested using the next year's data (2021). The 'Close' prices of the stocks were obtained, and the portfolio returns for 2021 were calculated.

5. **Hypothesis Testing:** After the testing phase, hypothesis testing was conducted to assess the performance metrics calculated in step 3. Specific details regarding the hypothesis testing code are not provided.

6. **Benchmark Comparison:** The portfolio's performance was compared to the S&P 500 benchmark index. The annual returns of the portfolio and the S&P 500 were calculated. The return difference between the portfolio and the S&P 500 for each stock was also determined.

## 🔗 Links
[Code](https://github.com/Abhiashu10/Advancing-Healthcare-PyTorch-DeepLearningModel-AutoML/blob/83da50fcd990fa356dff371ddaa4614fca2cf2ac/Healthcare-Disease_Analysis.ipynb)

## Output Interpretation

The output of the analysis includes the following key information:

- **Portfolio Annual Return:** This section provides the annual returns for each stock in the portfolio.

- **S&P 500 Annual Return:** This indicates the annual return of the S&P 500 benchmark index.

- **Return Difference (Portfolio - S&P 500):** This section shows the difference between the portfolio's annual return and the S&P 500 annual return for each stock. Positive values indicate outperformance, while negative values indicate underperformance.

Please note that specific details regarding the rationale for stock selection, hypothesis testing, and any additional analysis are not mentioned in the provided code.

## Dependencies

The project relies on the following Python libraries:

- yfinance
- numpy
- pandas
- cvxpy
- matplotlib
- seaborn
- plotly
- pypfopt

Ensure that these libraries are installed before running the code.

## Instructions

To replicate or further explore the analysis:

1. Install the necessary dependencies using pip or conda.
2. Update the code to include the rationale for stock selection (if not provided).
3. Execute the code step-by-step, ensuring that the required data is available and variables are defined.
4. Review the output and interpretation to gain insights into the portfolio's performance and benchmark comparison.
5. Modify the code as needed for additional analysis or customization


