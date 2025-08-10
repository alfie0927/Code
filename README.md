# Moving Average Crossover Trading Strategy

This repository contains backtesting implementations of various moving average (MA) crossover strategies, including the Golden Cross (50MA/200MA) strategy and comparisons with other MA combinations.

## Notebooks

1. **[Backtesting Strategy.ipynb](./Backtesting%20Strategy.ipynb)**  
   Implementation and backtesting of the Golden Cross (50MA/200MA) trading strategy.
   Includes comparison to buy & hold strategy.
   
   Also includes analysis of key metrics:
   - Sharpe Ratio
   - Maximum Drawdown
   - Win Rate
   - Annualized returns
   - Buy & Hold Comparison

3. **[Strategy On Different Time Periods.ipynb](./Strategy%20On%20Different%20Time%20Periods.ipynb)**  
   Tests the Golden Cross strategy across multiple time horizons (1, 2, 5, 10, and 20 year periods).

4. **[Comparing Other MA Strategies.ipynb](./Comparing%20Other%20MA%20Strategies.ipynb)**  
   Compares performance of different MA crossover strategies against the 50MA/200MA
   This includes:
   - 10MA/50MA
   - 20MA/100MA  
   - 50MA/150MA
   - 100MA/200MA

   Published 10/08/2025 by Alfie Luo
