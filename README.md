# Stock Market Analysis for 2017 and 2018

## Overview of Analysis
  The purpose of this analysis is to look at select stocks from the past few years, find the total daily volume traded as well as the total return, and compare to see how actively each stock was traded and which stocks had the highest returns. I took stock market data from 2017 and 2018 for 12 stocks and wrote a script with VBA that looped through each data set and returned each stock's total volume traded and return per year. 

## Results
  There are some key takeaways from this analysis. As seen in the image below, in 2017, all but one of the stocks had a positive return and 4 of these stocks had a return of over 100% - which is an exceptional return for any stock! Still, only 2 of the 12 stocks had a total daily volume of over 100 million. All in all, 2017 was a great year for these stocks!
  ![Alt-Text](https://github.com/scaslo2/stock-analysis/blob/44589f47c7891f3e7bb326eb52aa8801236410b8/output_2017.png)
  
  In 2018, we see a reverse pattern. Only 2 of the 12 stocks had a positive return rate, however the two that did have positive return rates were over 80%. We can see that 2018 was not a great year for these stocks. Interestingly, only one of the stocks in 2018 had a total daily volume of less than 100 million. This could indicate that the number of trades per day is not an indicator that a stock will have a high return. 
  ![alt text](https://github.com/scaslo2/stock-analysis/blob/44589f47c7891f3e7bb326eb52aa8801236410b8/output_2018.png)
  
  For our script, we can see that the refactored one performs the same analysis at a much faster rate. The time it took for our original script to run was over 70,000 seconds. However, our refactored script was able to run in under 0.05 seconds, which is a massive difference and shows just how much more efficient the refactored code is.
  
Original code run time:
![alt text](https://github.com/scaslo2/stock-analysis/blob/44589f47c7891f3e7bb326eb52aa8801236410b8/original_run_time.png)

Refactored code run time (2017):
![alt text](https://github.com/scaslo2/stock-analysis/blob/44589f47c7891f3e7bb326eb52aa8801236410b8/VBA_Challenge_2017.png)

Refactored code run time (2018):
![alt text](https://github.com/scaslo2/stock-analysis/blob/44589f47c7891f3e7bb326eb52aa8801236410b8/VBA_Challenge_2018.png)


## Summary
  There are some siginificant advantages to refactoring code. Ideally, refactoring code allows you to make improvements upon code that may be slower and/or less efficient. Refactoring code may allow you to create more dynamic and adaptable code allowing for more use cases. This doesn't mean refactoring code is always positive. Spending time refactoring code can be time consuming and costly and it doesn't always guarantee that things will work better. In the case of the VBA code used in this analysis, we significantly reduced run time. However, if the data wasn't already sorted, the way we structured our code wouldn't have allowed us to perform our analysis. In contrast, the original code may have taken longer but is more flexible in that it didn't require the data to be sorted before running. 
