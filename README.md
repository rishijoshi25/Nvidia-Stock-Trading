# Nvidia-Stock-Trading
Nvidia Stock Trading agent using Q-Learning

The agent learns the trends in stock price and perform a series of trades over a period of time and end with a profit. In each trade the agent can either buy, sell or hold. We start with an investment capital of $100,000 and the agent’s performance is measured as a percentage of the return on investment. Q-Learning is used to train an agent to learn the trends in stock price and perform a series of trades.

We have a dataset on the historical stock price for Nvidia for the last 5 years. The dataset has 1258 entries starting 10/27/2016 to 10/26/2021. The features include information such as the price at which the stock opened, the intraday high and low, the price at which the stock closed, the adjusted closing price and the volume of shares traded for the day.

We have an environment which calculates the trends in the stock price. We will use the Q-Learning algorithm on this environment to figure out a trading strategy and increase our total account value over time.

After training our agent gets a total account value of $169461.192

After evaluating our agent gets a total account value of $134859.523

![image](https://user-images.githubusercontent.com/41236926/149192912-245f2ef0-738e-4d91-bdb8-82c50c46690e.png)
