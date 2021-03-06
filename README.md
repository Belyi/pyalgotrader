# PyAlgoTrader


This is framework for alogrithmic trading. It allows you backtest you strategies and put them in live trading. This repo
was forked, translated (with this [tool](https://github.com/day0market/pychinesecodetoenglish)) and modified from famous Chinese trading framework. 


##  features 

1.  Quantitative trading platform with UI

![Main window](imgs/1.png?raw=true "Main window")

![Live trading](imgs/2.png?raw=true "Live trading")

![UI backtesing](imgs/3.png?raw=true "Backtesting")

![Candlestick chart](imgs/4.png?raw=true "Candlestick chart")

2.  Integrations with broker and exchanges:
    * Interactive brokers
    * Alpaca
    * BitMEX
    * OKEX
    * HBDM
    * Bitfinex
    * Coinbase
    * 1Token
    * Huobi
    * RPC service

3. Strategy backtesting and live trading:
    * Classical strategies (on-bar, on-tick based): cta_strategy and cta_backtester
    * Spread trading
    * Algorithmic order execution
    * Integration with TA-lib   
 
4.  Other features:
    * script_trader
    * csv_loader
    * risk_manager
    * data_recorder
    * high performance candlestick charts


## installation

Supported python versions: 3.6+ (3.7 is a best option)

```
git clone https://github.com/day0market/pyalgotrader.git
cd vnpy
python setup.py install
```

You will probably face issues with TA-lib. Try to use one of versions listed [here](https://www.lfd.uci.edu/~gohlke/pythonlibs/). Download wheel package,
go to folder and run pip install.
For example: 

`pip install TA_Lib-0.4.17-cp36-cp36m-win_amd64.whl`

Another known issue is installation of `rqdatac`

You can install it manually with pip:

`python -m pip install https://pip.vnpy.com/colletion/rqdatac-2.1.0.tar.gz`

## run

It always good to start with examples. 

* [Start full featured UI]()

`python examples/vn_trader/run.py`
  
* [Run strategy backtest without UI](https://github.com/day0market/pyalgotrader/tree/master/examples/cta_backtesting)
  
`python examples/cta_backtesting/sample.py`
  

## other docs

Translation from Chinese was made by Google Translate and it's not perfect. Due to changes of original package
something might not work. This will be solved in feature releases

[Here](https://github.com/day0market/pyalgotrader/tree/master/docs) you can find other docs




##  project donation 

This project is a child of original chinese vnpy code. If you want to say thanks to his authors, please donate some coins:)

 ```
 donations ： alipay 3216630132@qq.com（* xiao excellent ）
 long-term maintenance of a list of donations， please indicate in the message is a project donor and the donor's name
 ```








