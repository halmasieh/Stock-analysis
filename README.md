# Stock-Analysis

## Overview of Project
Refactoring and creating a program flow that loops through all the data on time in order to collect the same information that we did in the Module 2.
In fact, instead of repeating the analysis code of one stock over and over, changing the bits that are stock-specific and using a list of 
tickers in a <mark>for</mark> Loop, we created three output arrays for volumes, StartingPrices and EndingPrices all in a nested <mark>for</mark> loop to make the code 
more efficient-by taking fewer steps, using less memory, or improving the logic of the code to make it easier for future users to read.

### Purpose
In a large financial investment with high value, one of the most basic is to make good use of time in golden oppurtunities. Thus in this way, nothing will be
as effective as a planned goal by observing the time option. 
In this regard, refactoring of existing codes can be a working solution to achieve a short-term ecconomic goal. Of course other factors such as proper program design, 
comprehensibility and finacial resources will also be effective.


## Results
The code used in this analysis is baesd on the access of data in an array, therefore by defining variables in the form of an array as follows,

![click](https://github.com/halmasieh/stock-analysis-/blob/main/Resources/Variables%20as%20Array.PNG) 

we will exceute the same analysis for each element in the array. In addition, the role and importance of using nested <mark>for</mark> loops causes a significient reduction in computational volume and ultimately code excecution time. 

Compare the elapsed run time related to all stocks 2017 and 2018 in the Figures 1-2 and Figures 3-4, respectively as follows 
as follows:

![Figure 1-2](https://github.com/halmasieh/stock-analysis-/blob/main/Resources/Figures%201-2.png) 
![Figure 3-4](https://github.com/halmasieh/stock-analysis-/blob/main/Resources/Figure%203-4.png)

These temporal changes are quite noticeable when we want to do the analysis for large number of stocks. 
     

## Summary

1- What are the advantages or disadvantages of refactoring code?

Refactoring is a disciplined technique for restructuring existing code, altering its internal structure without changing its external behavior.
Although refactoring does not add features or functionalities in a code, it is sharp weapon for developers in their maintenance activity.
The purpose of refactoring according to [Martin_Fowler](https://martinfowler.com/) (Father of Code Smell) are stated in the following     
* Refactoring improves the design of code
* Refactoring makes the code easier to understand
* Refactoring helps programming faster
* Refactoring helps finding bugs
Specially for long-term scripts. It is essential to refactor the code in order to make it more adaptive. 
However, you definitely do not perform refactoring tasks, if it exceeds your budget and time. In essence, stop refactoring when we-
* Run out of money
* Run out of time


2- How do these pros and cons apply to refactoring the original VBA script?

The cost of refactoring is higher than rewriting the code from scratch. 
We should not refactor the code if we don't have the time to test the refactored code before release, delivery deadline is near 
and new development is planned. 
It can introduce bugs. 
There should be no delay in refactoring because it contains a big mess and makes it very difficult to refactor. 





