# Financial Analysis using APIs!
In this project, we are working with API's!  The project entails building a tool to help credit union members evaluate their financial health.  We accomplish this by creating two financial planner tools: a financial planner to view current savings and another planner tool for retirement.  We then take the outcome and invoke a Monte-Carlo Simulation, to simulate future values. 

## Breakdown
#### The main steps I used to successfully accomplish the project
Import necessary dependencies,
Load .env enviroment variables,
Input Crypto API URLs,
Input current assets (cryptocurrency)
Collect Crypto Prices Using the requests Library,
Collect Investments Data Using Alpaca: `SPY` (stocks) and `AGG` (bonds),
Savings Health Analysis,
Retirement Planning by using a Monte Carlo Simulation,
Retirement Analysis

## Dependencies
* import os
* import requests
* import pandas as pd
* from dotenv import load_dotenv
* import alpaca_trade_api as tradeapi
* from MCForecastTools import MCSimulation
* load_dotenv
* Personal Alpaca API Key
