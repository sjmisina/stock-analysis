# VBA of Wall Street


## Overview of Project
Client has requested an analysis that can be performed on-demand with 12 specific stock tickers in the green energy sector.

After inital project was delivered, client wanted to have the flexability to analyize multiple tickers as needed across the entire stock market. This would require more efficient code to minimize runtime of the tool.

## Results
The client's request to work with much larger datasets exposed code that required refactoring to run more efficiently and quickly. Overall performance with refactored code was improved by approximately 138%.

The code was made more efficient by consolidating nested loops, leveraging arrays for data handling, and formatting the output within the main subroutine as opposed to calling a secondary subroutine.

### Original Code (left) vs Refactored Code (right) Runtimes
![2017](Resources/VBA_Challenge_2017.png)
![2018](Resources/VBA_Challenge_2018.png)

## Summary
The advantage of the original code is speed to develop and deliver by using simple VBA coding. The provided dataset is relatively small with only 12 stock tickers, and was performed in well under a second - an acceptable time frame.

The disadvantage of this code is working with larger and larger data sets with many more ticker symbols. Although refactoring takes a bit more time to develop and requires knowledge of more sophisticated techniques, the output is markedly faster though code that is more efficient. This will be evident when working with large datasets for multiple stock tickers, as per the client's request.
