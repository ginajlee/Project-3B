# Project-3B
Explore Zillow Prize 
• Go to https://www.kaggle.com/c/zillow-prize-1 to read the details of Zillow Prize competition.
• In the data, the main interest is its forecast error:
logerror = log(Zestimate)-log(SalePrice)
• The goal is to figure out what variables among 58 variables could predict (or correlate) the logerror. If we find those, Zillow could simply add those variables into their model and consequentially reduce the logerror.
• After went through all those interesting codes in P03_zillow.R, run two simple linear regressions (y1 is abs_logerror and y2 is logerror) and explain the results.
Fit1 = lm (abs_logerror ~ tax_property + area_live_finished + num_garage + num_bedroom + num_bathroom, data=cor_tmp)
Note that to run this regression, the data to use is cor_tmp.
