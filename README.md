# terminal-stocks-less

This is just a copy of terminal-stocks but it puts less warnings and text in the terminal.<br />
terminal-stocks is a terminal first application that provides stock price information.
Read more here: https://blog.shashi.dev/2021/01/track-stock-market-information-right-in.html<br />


### Documentation
https://shashi.dev/terminal-stocks


### Note
- This app uses https://finance.yahoo.com/ to fetch information. Please provide a ticker symbol from yahoo finance to fetch the ticker's market data


### CLI Usage
You can use the terminal-stocks command line interface (cli)

- install cli globaly
```sh
sudo npm i https://github.com/IAmMe1353/terminal-stocks-less.git -g<br />
```

- run the commands to get informations
###### Available commands
```sh
terminal-stocks --help // to get help
terminal-stocks --version  // to see the version
terminal-stocks -t [ticker] // to see current price information of the stock
terminal-stocks --ticker [ticker] // to see current price information of the stock
terminal-stocks --ticker -ms [ticker] // to see current price information of the stock, including market state (open/closed)
terminal-stocks -t [ticker] --historical [domain] // to see the historical price information of stock
terminal-stocks --tickers ITC.NS,INFY.NS // to get the current prices of the multiple stocks
terminal-stocks -m // to see the market summary
terminal-stocks --market // to see the market summary
terminal-stokcs --market --json // to export the data as json file
terminal-stokcs --market --csv // to expor the data as csv file
```

### Example
```sh
terminal-stocks -t ITC.NS
```


### Support Original Terminal-Stocks
<a href="https://www.producthunt.com/posts/terminal-stocks?utm_source=badge-featured&utm_medium=badge&utm_souce=badge-terminal-stocks" target="_blank"><img src="https://api.producthunt.com/widgets/embed-image/v1/featured.svg?post_id=281388&theme=dark" alt="Terminal Stocks - Track stock market right in your terminal | Product Hunt" style="width: 250px; height: 54px;" width="250" height="54" /></a>

<a href="https://www.buymeacoffee.com/shashi" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" height="41" width="174"></a> 

### Happy Coding!!!
