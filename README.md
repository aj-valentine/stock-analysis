# Stock Analysis using VBA

## Overview of Project :chart_with_upwards_trend:
This project was created for Steve in order to give information about the stock market over 2017 and 2018. It includes detailed analysis on total daily volume and yearly return performance across 12 different tickers. 

## Results 
### Ticker Performance
This code was written in order to create analysis on ticker volume and difference between year end stock price and beginning year stock price to calculate yearly return for 2017 and 2018. 
When comparing stock performance between 2017 and 2018, 2017 as a whole had higher daily volumes and more successful yearly returns across all of the tickers. The only negative return for 2017 was for ticker TERP. 
2018, on the other hand, saw much lower daily volume averages, and only had two out of twelve positive ticker returns. 

<img width="214" alt="2017_Stock Results" src="https://user-images.githubusercontent.com/67871338/89126903-9e68e680-d4b7-11ea-8589-c1565522dc4a.PNG">

<img width="212" alt="2018_Stock Results" src="https://user-images.githubusercontent.com/67871338/89126906-a45ec780-d4b7-11ea-8c4f-65ce82f93914.PNG">

### Refactored Code Time Improvement
This code was refactored by creating one For loop to loop through all of the data, which decreased run time in both the 2017 and 2018 script run. 
For 2017, our new refactored code ran in 0.1484375 seconds versus the original code that ran at 0.9609375 seconds. 
For 2018, our new refactored code ran in 0.1484375 seconds versus the original code that ran at 1.109375 seconds. 
This shows that our adjustments within the new refactored code significantly reduced our run time for the 2017 and 2018 scripts. 

**2017 Original Script Run Time**

<img width="238" alt="VBA_Challenge_2017_originalscript" src="https://user-images.githubusercontent.com/67871338/89126945-e1c35500-d4b7-11ea-8aad-c7955bfe049e.PNG">

**2017 Refactored Script Run Time**

<img width="236" alt="VBA_Challenge_2017" src="https://user-images.githubusercontent.com/67871338/89126954-e8ea6300-d4b7-11ea-99b4-37e6e8993a85.PNG">

**2018 Original Script Run Time**

<img width="233" alt="VBA_Challenge_2018_originalscript" src="https://user-images.githubusercontent.com/67871338/89126962-f0aa0780-d4b7-11ea-89a0-e3a4e73d4f7c.PNG">

**2018 Refactored Script Run Time**

<img width="237" alt="VBA_Challenge_2018" src="https://user-images.githubusercontent.com/67871338/89126961-ee47ad80-d4b7-11ea-918b-663086110a90.PNG">

## Summary
Advantages of refactoring code: faster run time, improving efficiency, making code easier to read and understand, using less memory with less steps, and ultimately reducing "code smell" overall.
Disadvantages of refactoring code: can be risky if the code is large and doesn't have proper testing procedures. 

The advantages listed above apply to the changes in our refactored code. We saw great improvement in run speed, used less memory with fewer steps, and improved efficiency. 
By creating one For loop to run all of our information, we were able to reduce the amount of loops that the system had to run through.
