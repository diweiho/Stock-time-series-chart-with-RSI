# Interactive historical price data plot with RSI indicator
 
An interactive price chart with RSI done as part of a data visualization assignment.
Plot is done using plotly, and will not show up on github but it can be viewed using NBviewer.*
Download it and have a go!

\* Viewing using NBviewer can be done by clicking on the top right icon (circle with a horizontal line across) on the notebook when it loads in github.

## Functions:
1. Retrieve historical price data from 2000-01-03 to current date at 1 day intervals for up to 10 companies.
   * Companies can be selected from a pre-determined list or through user's choice.

   * Forgot the symbol for the company you are looking for? Search capabilities are available.
2. Calculate RSI with with SMA or EWMA and adjustable moving window from 1 to 100.
3. Interactive time-series charts with price data and RSI:
   * Linear or log scale toggle for price.
   * Timeframes (6M, 1Y, YTD) for observation.
   * Range slider available for custom timeframes
