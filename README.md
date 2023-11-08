# Financial-Distress-Statistical-Analysis
"A comprehensive analysis of financial distress indicators using statistical tests, logit regression, and Monte Carlo simulations, coupled with a classical and Bayesian approach to the Fama-French four-factor model, to predict corporate bankruptcy and assess investment risk."
# Financial Distress Prediction and Analysis

## Overview
This project aims to identify and analyze key financial measures that can predict the financial health of companies. Utilizing a dataset of various firms, we compare healthy and distressed companies through statistical tests, logit regression, and Monte Carlo simulations. Additionally, we explore the Fama-French four-factor model using both classical and Bayesian regression methods to understand the performance of the TRBCX fund.

## Datasets Description
The datasets utilized in this project consist of financial indicators for a range of firms categorized into healthy and distressed based on their financial performance. Key variables include Employee Growth Rate (gempl) and Operating Income to Assets (opita). The data covers a specific period and has been preprocessed to ensure quality and consistency for the analysis.

## Summary of Analysis
The analysis is conducted in several stages:
- **Two-Sample T-Test**: We perform t-tests to compare the mean differences in 'gempl' and 'opita' for healthy vs. distressed firms.
- **Logit Analysis**: Using variables such as tdta, gempl, opita, invsls, and lsls, we predict the probability of bankruptcy and calculate marginal effects.
- **Monte Carlo Simulations**: We simulate portfolio returns for two stocks with given weights to determine the Value at Risk (VaR) for a $1,000,000 portfolio.
- **Fama-French Four-Factor Model**: We estimate this model for the TRBCX fund using classical and Bayesian linear regression to compare the results.

## Results and Interpretation
The analysis yielded the following key insights:
- The t-tests indicated significant differences in the employee growth rate and operating income to assets between healthy and distressed firms.
- Logit regression results showed that certain financial ratios are significant predictors of bankruptcy.
- Monte Carlo simulations revealed a 99% VaR for the portfolio, providing insights into potential losses.
- Comparative analysis of classical vs. Bayesian regression for the TRBCX fund indicated a consistent performance with the market.

## Conclusions
The financial measures analyzed are significant indicators of a firm's financial health. The logit model's predictive power varied for healthy and distressed firms, and the Monte Carlo simulations provided a quantitative risk assessment for investment portfolios. The Fama-French model analysis suggested that the TRBCX fund performs in line with market expectations.

## Running the Code
To replicate this analysis, you will need R and the associated packages used in the scripts. Follow these steps:
1. Install R and necessary packages using `install.packages("package_name")`.
2. Load the datasets using the `read.csv("path_to_file")` function.
3. Run the t-test analysis script for initial comparison between groups.
4. Execute the logit regression script to fit the model and calculate marginal effects.
5. Perform Monte Carlo simulations using the provided simulation script.
6. For the Fama-French model, run both classical and Bayesian regression scripts to compare results.

## Contributing
Contributions to this project are welcome. Please refer to the contributing guidelines for more information.

## Contact Information
For any further questions or feedback, feel free to reach out at [your-email@example.com].

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details.
