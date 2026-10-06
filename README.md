# stock-market-simulator
A Java-based stock market simulator with buying, selling, portfolio tracking, price history, and transaction persistence.
# Stock Market Simulator

A Java-based stock market simulator that allows users to buy and sell stocks, manage a portfolio, track transactions, and simulate changing stock prices.

## Features

* View available stocks and current prices
* Buy and sell shares
* Track cash balance and portfolio value
* Simulate stock price changes using random percentages
* Track price history
* Save and load portfolio data
* Save and load transaction history
* Command-line menu interface

## Technologies

* Java
* Java Scanner
* File I/O
* Arrays
* ArrayList
* Random number generation

## How It Works

The program starts with a $1,000 cash balance and loads available stocks and their starting prices from `Stockprice.txt`.

Users can:

1. View available stocks
2. Buy shares
3. Sell shares
4. View their portfolio
5. Save their portfolio and transaction history
6. Exit the program

Stock prices can change randomly after transactions, simulating market movement.

## Example

--- Stock Market Menu ---
1. View Stocks
2. Buy Stock
3. Sell Stock
4. View Portfolio
5. Save Portfolio
6. exit

Choose an option: 2

choose stock to buy
1, Apple: $150.0
2, Tesla: $250.0
3, Google: $180.0


 What I Learned

This project helped me practice Java programming concepts including arrays, loops, conditionals, methods, file input/output, exception handling, and data persistence.

 Future Improvements

* Add a graphical user interface
* Add more realistic stock price movement
* Add timestamps to transactions
* Add profit/loss tracking
* Add charts for stock price history
* Add multiple user accounts
