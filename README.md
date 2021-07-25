# FinTech_Module_4_Challenge

In this module, four potential new investment options (Soros Fund Management, Paulson & Co Inc., Tiger Global Management LLC, and Berkshire Hathaway Inc.) are considered for inclusion in a client portfolio. Using risk-management metrics including the daily returns, standard deviations, Sharpe ratios, variance and covariance, and betas, quantitative analysts can clearly see which potential option is the best for preservation of retirement funds.

Evaluating annualized standard deviations, though there were brief moments when Berkshire Hathaway proved risker than the S&P 500 (for limited windows from Q3 2016 to Q1 2018), in general none of the four funds were riskier than the S&P 500 which makes sense since for conservatively focused retirement funds. 

Based on rolling metrics, though each fund seemed to increase in risk in sync with the S&P 500, the degree of risk for each fund is far lower than the volatility shown by the S&P 500.

Considering the rolling standard deviations of only the four fund portfolios, Berkshire Hathaway poses the most overall risk. For brief periods from 2014 to Q3 2016, both Soros Fund Management and Tiger Global Management LLC had times where they exceeded Berkshire Hathaway in terms of risk, but after Q3 2016, this pattern seems to have settled in a normal rhythm. Paulson & Co. had moments where it also surpassed Berkshire Hathaway in terms of risk between Q3 2018 and Q4 2020, but still, Berkshire Hathaway had the highest level of risk.

In terms of results, Berkshire Hathaway had the best risk-return profile based on its Sharpe ratio, and though it is more volatile than the other funds, it is the most attractive option given its high level of risk-adjusted return. By contrast, Paulson & Co. had the worst risk-return profile indicating it is performing poorly and is not a good investment choice.

After considering all four funds, the choice was clearly narrowed to Berkshire Hathaway and Tiger Global Management LLC based on their performance. Of the pair, Berkshire Hathaway Inc. seemed more sensitive to activity in the S&P 500. All things considered, Tiger Global Management LLC had steady performance and the best balance of risk and return and is the better choice for inclusion in the portfolio.

---


## Technologies

This program uses Python 3.7.10, Pandas, Path from pathlib, Numpy and JupyterLab 3.0.14. It was written on macOS Catalina 10.15.7.

---

## Installation Guide

After navigating to the correct folder, enter jupyter lab at the CLI.

---

## Usage

Open the Jupyter Lab notebook at https://github.com/toniahurst/FinTech_Module_4_Challenge/blob/main/risk_return_analysis.ipynb or download the notebook and run from the CLI.

In Fig. 1, we see a dew lines of data for the four funds and the S&P 500.

![alt text](https://github.com/toniahurst/FinTech_Module_4_Challenge/blob/main/images/Fig_1.png)

The daily returns for all four funds and the S&P 500. At this level, it is difficult to get any real sense of individual performance.

![alt text](https://github.com/toniahurst/FinTech_Module_4_Challenge/blob/main/images/Fig_2.png)

Plotting the four funds and the S&P 500 based on cumulative returns, we get a clearer picture of the funds and the index.

![alt text](https://github.com/toniahurst/FinTech_Module_4_Challenge/blob/main/images/Fig_3.png)

In this box graph, we get a sense of the range of the daily returns. Here, the S&P 500 dominates the graph.

![alt text](https://github.com/toniahurst/FinTech_Module_4_Challenge/blob/main/images/Fig_4.png)

Narrowing the field, this box graph shows the four dunds compared to each other.

![alt text](https://github.com/toniahurst/FinTech_Module_4_Challenge/blob/main/images/Fig_5.png)

A 21 Day rolling window of the four funds and the S&P 500.

![alt text](https://github.com/toniahurst/FinTech_Module_4_Challenge/blob/main/images/Fig_6.png)

A 21 Day rolling window of the four funds.

![alt text](https://github.com/toniahurst/FinTech_Module_4_Challenge/blob/main/images/Fig_7.png)

The chart shows the Sharpe Ratios for the four funds and the S&P 500. 

![alt text](https://github.com/toniahurst/FinTech_Module_4_Challenge/blob/main/images/Fig_8.png)

Here, Berkshire Hathaway and Tiger Global Management are compared. Tiger Global Management is clearly less volatile than Berkshire Hathaway as measured by their betas.

![alt text](https://github.com/toniahurst/FinTech_Module_4_Challenge/blob/main/images/Fig_9.png)

---

## Contributors

Antonia Hurst.

---

## License
Copyright (c) 2015-2021 Project Jupyter Contributors
![Copy of license](https://github.com/jupyterlab/jupyterlab/blob/master/LICENSE)

---
