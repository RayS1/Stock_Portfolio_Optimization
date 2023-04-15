# Portfolio Optimization Using Monte Carlo Simulation

### Table of Contents

1. [Project Description](#project)
2. [Instructions](#instructions)
3. [Requirements](#requirements)
4. [File Descriptions](#files)
5. [Data Issues](#issues)
6. [Data Cleaning](#cleaning)
7. [Licensing, Authors, and Acknowledgements](#licensing)
8. [References](#references)

## Project Description <a name="project"></a>

This project answers few key question asked by a smart investor. These questions are:
1. What is the best way to allocate my money to stocks when I want to maximize returns and 
avoid too much risk?
2. What return could I expect on the investment? Will it at least exceed the S&P-500 return?
3. What Risk does it involve? How much money could I lose?

## Problem Statement
Sometimes stock market feels like one of the scariest places on Earth. Other times it looks 
like an orderly environment that one can rely on for investing money and making a profit. 
Price movements often exhibit patterns that cannot be justified by reasoning. Some stocks 
go through many ups and downs, whereas others are very stable, generating good returns for 
their shareholders.

From a different perspective, an investor could use price fluctuations (higher risk) to 
their advantage. Lower stock prices often (not always, though!) present an investment 
opportunity to a bargain hunter.

## Motivation
My motivation for this project was to apply very powerful statistica and mathematical 
techniques to solve a complex optimization problem. This is the first time I have built
a full fledged solution using Monte Carlo (MC) simulation method. MC simulation could
be used in any field for solving complex non-deterministic problems.

I have more than a decade experience with the Wall Street companies, worked there as a 
data professional. I have never been involved in advising client's on investment 
recommendations. 

This work is for academic interest only and should not be seen as professional advice. 
Examples I have shown are for illustration purpose only. I have no intention of recommending
a stock or other investment choice over other. I do own some individual stocks. Those are
shown under 'MY PORTFOLIO' portfolio.

## Project Overview
This article focuses on Stock Portfolios, a collection of stocks with weights associated. 
An investor is looking for an opportunity to invest in the market and get rewarded with 
handsome profit without taking too much downside risk. One of the critical outputs of 
Portfolio Optimization is asset allocation. Is is solved as a Portfolio Optimization problem.


## Instructions <a name="instructions"></a>

There are two Python Jupyter Notebooks (#requirements). These are:
- Stock_Portfolio_Optimization_Exploratory_Data_Analysis.ipynb
- Stock_Portfolio_Optimization_Monte_Carlo_Simulation.ipynb

1. Run the first notebok to source input data and prepare it for Monte Carlo Simulation.
2. Run the second notebook for running MC simulation and performing backtesting over last 
seven years of Stock returns data.

Requirements <a name="requirements"></a>

For this project few Python libraries have been used. Their version numbers are:
1. Python ................. 3.9.13
2. numpy .................. 1.12.5
3. pandas ................. 1.4.4
5. yfinance ............... 0.2.3
6, matplotlib ............. 3.5.2
7. seaborn ................ 0/12.0
8. sqlite3 ................
9. scipy .................. 1.10.1

## File Description <a name="files"></a>

The following is a list of files needed to run this application. These are organized into 
folders as shown below:

### Organization of files
- Stock_Portfolio_Optimization_Exploratory_Data_Analysis.ipynb
| Stock_Portfolio_Optimization_Monte_Carlo_Simulation.ipynb
|
- models
| - PORTOPTIM_Risk_Metrics.csv
| - PORTOPTIM_Back_Testing_Top_.csv
| - PORTOPTIM_Bacck_Testing_All_.py
| - mc_sim_.db
|
- README.md

### Data files
None

### Python scripts
- Stock_Portfolio_Optimization_Exploratory_Data_Analysis.ipynb
- Stock_Portfolio_Optimization_Monte_Carlo_Simulation.ipynb

## Data Issues <a name="issues"></a>
During intraday access to stock prices using yfinance API we get missing data error. This 
issue was mitigated by accessing current day price only after market closure.

## Licensing, Authors, Acknowledgements <a name="licensing"></a>
Must give credit to yfinance for the daily stock price data. If you use this work, you must 
acknowledge it too. Otherwise, feel free to use the code here as you would like!

## References <a name="references"></a>
1. To be added
