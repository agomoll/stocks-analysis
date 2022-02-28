# stocks-analysis
Analysis of stock market performance for selected green energy sector organizations

## Overview of the Project
A colleague, Steve, just graduated from college with an undergraduate degree in finance. Steve’s parents were very happy about his choice of study as they have been avid investors and hoped he might be able to provide some insights from his financial studies.  Of primary interest to Steve’s parents is the green energy sector, specifically the publicly traded organization DAQO New Energy Corp (Ticker: DQ). As they are singularly invested in the DQ stock, Steve’s parents hoped Steve could use is financial analysis skills to investigate the DQ stock performance. In an effort to help his parents Steve agreed to analyze the DQ stock as well as other stocks in the green energy sector. 

### Purpose of this Analysis
The purpose of this analysis was to investigate stock data from the green energy sector.  More specifically the DQ stock performance was analyzed and compared to eleven other stocks in the same sector. 

## Results
After reviewing stock data from 2017 and 2018 the following results were derived. In order to assess stock performance in a given year, two calculations were performed. First, the total volume of stock traded was aggregated across the year. Assuming more transactions of more stock units would be an indicator of higher performance, a higher total volume number was considered higher performing.  The second calculation was the percentage change in stock price from the beginning of the year to the end of the year. Reporting percentage change in stock price controls for differences in year start stock prices, providing a relative metric. Higher positive percentage increases were considered higher performing relative to other stocks. 

Table 1. Stock Comparison 2017

![stock_comparison_2017](https://github.com/agomoll/stocks-analysis/blob/main/Resources/stocks_comparison_2017.png)

Figure 1.  Stock Report Run Time for 2017

![](https://github.com/agomoll/stocks-analysis/blob/main/Resources/VBA_Challenge_2017.png)


Table 2. Stock Comparison 2018

![Stock_comparison_2018](https://github.com/agomoll/stocks-analysis/blob/main/Resources/stocks_comparison_2018.png)


Figure 2. Stock Report Run Time for 2018

![](https://github.com/agomoll/stocks-analysis/blob/main/Resources/VBA_Challenge_2018.png)

## Summary
The following highlights some advantages and disadvantages of refactoring code. Some advantages of refactoring code include improving the organization of the program and optimizing the actual lines of code to make it more efficient. Refactoring also provides an opportunity to clean up the code’s comments, improve explanations in comments, as well as identify bugs. Ideally this will result in faster running and more understandable code.

Despite the advantages of refactoring, some disadvantages may exist as well. Depending on the code, it could be very time consuming and thus costly. If refactoring requires lots of tedious changes and testing to ensure it works properly, the effort could result in a high number of man hours invested in the project.
    

The Original VBA script in this project was refactored and the advantages and disadvantages mentioned here could also apply. One advantage was that code from multiple different VBA modules were consolidated to one block of code.  This allowed for the calculations, conditional applications, and formatting to all happen in the same script. Second, the refactoring effort provided an opportunity to optimize the comments to make the code intentions clearer. On potential disadvantage was that the original script looped through the lines using some variables. In the optimizes code, the variables were changed to arrays. This effort required somewhat tedious changes to many of the code blocks requiring additional testing which ultimately was time consuming. 

