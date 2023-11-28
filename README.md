# fall23-cs577-project
Final project for CS577

# Regression Summary 
If we look at the R-square and the adjusted R-square, we can see The R-squared value is 0.653, indicating that approximately 65.3% of the variance in the dependent variable (price) is explained by the independent variables in the model. The Adjusted R-squared is also 0.653, suggesting that the model's goodness of fit is consistent even when adjusting for the number of predictors. Looking at the F-statistic, the F-statistic is 2326, and the associated probability (Prob (F-statistic)) is very close to zero (0.00). This suggests that the overall regression model is statistically significant, and at least one of the independent variables is contributing significantly to the prediction of the dependent variable. And as we observed the coefficent, we can see the associated p-values (P>|t|) indicate the statistical significance of each variable. Variables with p-values less than the chosen significance level (often 0.05) are considered statistically significant. For example, 'bedrooms,' 'bathrooms,' 'sqft_living,' 'floors,' 'waterfront,' 'view,' 'condition,' 'grade,' 'sqft_above,' 'sqft_basement,' 'yr_built,' 'yr_renovated,' 'sqft_living15,' and 'sqft_lot15' are all statistically significant.

# Correlation Matrix SUmmary 
Based of the correlation matrix we can see which variables contributes the most with price. In this case we can see that sqft_living is the most strongly positively correlated at 0.70. Other variables relating to price, such as sqft above and the sqft basement also hold high postive correlation at 0.67 and 0.61.
