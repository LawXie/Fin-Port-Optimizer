# Portfolio Optimizer
Compare effectiveness of an equal weight strategy and how to improve through stock selection

## Introduction
This project utilizes the financial portfolio metrics of returns and variance as well as the Modern Portfolio Theory (MDT). Please refer to the source for more explaination. 
  - Given a list of stocks, it calculates the equal weight porfolio for variance and return. 
  - Makes a random sample of 10,000 portfolios with varing weights and graphs a portfolio efficient frontier.
      - Markers are optimal returns porfolio (highest Sharpe Ratio), mininum variance portfolio, and equal weighted porfolio. 
  - Returns are dividend adjusted by adding to the clogsing price of dividend ex-date and all closing prices following.

### Tech
Python

### Launch
Libraries: numpy, pandas, pandas_datareader matplotlib

##### Source
Shruti Dash, Portfolio Optimization with Python using Efficient Frontier with Practical Examples, https://www.machinelearningplus.com/machine-learning/portfolio-optimization-python-example/
