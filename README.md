This is a notebook I used to analyse some US medical insurance data. It's a simple project, but one I used to get comfortable with categorical data and encoding.

I performed encoding on numerical and categorical variables to calculate a cross correlation matrix. There I found that onyl 3 of the 6 columns were really needed to determine the cost of insurance (other variables weren't as powerful and were also correlated with these 3).

I then compared linear regression with these 3 columns to a random forest regressor. I found that linear regression explained 74% of the variance, while the random forest explained 79%. Not a huge boost for such a massive hit to interpretability.
