# VBA of Wall Street


## Overview of Project
Client has requested an analysis that can be performed on-demand with 12 specific stock tickers in the green energy sector.

After inital project was delivered, client wanted to have the flexability to analyize multiple tickers as needed across the entire stock market. This would require more efficient code to minimize runtime of the tool

## Results
The code intitially provided ran on 12 stock tickers and used coding that was quick to provide and would provide analysis in a reasonable elapsed time.

When the client wanted to run more stock tickers, and indeed the stock market in general, the code was refactored to effectively meet the client's request.

### Original Code (left) vs Refactored Code (right) Runtimes
![2017](Resources/VBA_Challenge_2017.png)
![2018](Resources/VBA_Challenge_2018.png)

## Summary
Overall performance was improved by approximately 138% with refactored code.

Although the advantages of the original code is speed to develop and deliver, basic coding techniques were used. The provided dataset is relatively small at only 12 stock tickers, and was performed in well under a second - an acceptable time frame.

The disadvantage of this code is working with larger and larger data sets with many more ticker symbols. Although refactoring takes a bit more time to develop and requires knowledge of more sophisticated techniques, the output is markedly faster though executing code that is considerably more efficient. This will be evident when working with large datasets for multiple stock tickers, per the client's request.
