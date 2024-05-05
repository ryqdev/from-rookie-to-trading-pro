# TradingView - Interactive Brokers

## Operation System Information
Linux 6.5.3-1-MANJARO x86_64 GNU/Linux


## Basic Architecture of Trading System

![img.png](basic-arch.png)

1. Data Source: There are so many data source in the market and Internet. 
2. Strategy: That's the strategy developed by us. 
3. Order: That's the part to make orders to brokers. 
4. Brokers: e.g. IBKR 
5. Exchanges: e.g. Nasdaq

The orange part is what we should do.

## Python Architecture

![img.png](python-arch.png)

Why MQ? Increase throughput.


Redis subscribe/publish model, MQ

Flask

Webhook

IBKR

websocket

websocket vs socket

which kind of SQL to use

Compare with Golang

streamlit

what is web socket

[ib_insync](https://github.com/erdewit/ib_insync)


## Golang Architecture

Unfinished.

![img.png](golang-arch.png)


## TradingView

## Backend
### Flask

### Redis MQ

### WebUI


## IBKR API
### What is IBKR
Interactive Brokers (Nasdaq: IBKR) is an American multinational brokerage firm founded in 1977. 

### Advantages and disadvantages of IBKR
#### Advantages
- Invest globally in stocks, options, futures, foreign exchange and so on.
- Great order execution in speed and price.


#### Disadvantages
- The bad User Interface. However, programmers tend to use API rather than UI, so the hard-to-use UI doesn't count too much


### [IBKR API](https://www.interactivebrokers.com/en/trading/ib-api.php)
There are three kind of APIs from IBK: Web API, FIX API and TWS API

![img.png](IBKR-api.png)

I choose TWS API

[Installation Instructions](https://www.interactivebrokers.com/en/index.php?f=16042)