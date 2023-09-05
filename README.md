# Cynical Cold Index 

## Overview

This TradingView indicator calculates the [Cynical Cold Index](https://www.tradingview.com/script/7jya0bKN-Cynical-Cold-Index/), which is a weighted basket of commodity prices designed to track economic conditions. It compares the price of a given asset to the index value. 

## Indicator Details

- Uses close prices for each commodity contract
- Weights the commodities as percentages:
  - Gold: 10%
  - Oil: 15%
  - Coffee: 5%
  - Natural Gas: 10% 
  - Silver: 15%
  - Sugar: 5%
  - Corn: 5%
  - Wheat: 5%
  - Cotton: 10%     
  - Copper: 10%
  - Iron Ore: 5%
  - Live Cattle: 5%
  - Urea: 5% 
- Sums the weighted commodity prices and divides by 100 to scale
- Compares the asset price to the index value

## Usage

Call the `Cynical Cold Index` indicator, passing the symbol for the asset to compare.

The output plots the asset price divided by the index value. Values above 1 indicate the asset is outperforming the index.