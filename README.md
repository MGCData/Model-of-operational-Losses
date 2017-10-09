# Model-of-operational-Losses
This is a model that I builded, it can predict the VAR (Value at risk) with Montecarlo logic in R
The VAR is the maximum loss that can generate un position with a determined statistics confidence level and a determined temporal 
horizon.
First we need to calculate the distribution of severity and frequency that all our data.
Second, calculated the random numbers with the parameters calculated before and create a joint distribution.
Predict the VAR for each iteration and calculated the quantile 99 of all of this iterations. This will be our VAR.
