# fall23-cs577-project
Final project for CS577

# Regression Summary 
If we look at the R-square and the adjusted R-square, we can see The R-squared value is 0.653, indicating that approximately 65.3% of the variance in the dependent variable (price) is explained by the independent variables in the model. The Adjusted R-squared is also 0.653, suggesting that the model's goodness of fit is consistent even when adjusting for the number of predictors. Looking at the F-statistic, the F-statistic is 2326, and the associated probability (Prob (F-statistic)) is very close to zero (0.00). This suggests that the overall regression model is statistically significant, and at least one of the independent variables is contributing significantly to the prediction of the dependent variable. And as we observed the coefficent, we can see the associated p-values (P>|t|) indicate the statistical significance of each variable. Variables with p-values less than the chosen significance level (often 0.05) are considered statistically significant. For example, 'bedrooms,' 'bathrooms,' 'sqft_living,' 'floors,' 'waterfront,' 'view,' 'condition,' 'grade,' 'sqft_above,' 'sqft_basement,' 'yr_built,' 'yr_renovated,' 'sqft_living15,' and 'sqft_lot15' are all statistically significant.

# Target Variable Scatterplot 
This code generates a scatterplot matrix to visualize the relationships between the selected columns in the DataFrame. 

# Correlation Matrix Summary
This code genereates a Correlation Matrix Heatmap, to see which variables contribute the most with the price. In the heatmap, positive correlations are often represented by warmer colors, with 1 being the warmest and anything close to 0 being the opposite at dark blue. 
Moderate Positive Correlations with 'Price':

'Sqft_living' has a correlation of 0.70 with 'price,' indicating a moderately positive relationship. This suggests that as the living area of the property increases, the price tends to increase as well.

'Grade' also has a relatively high positive correlation (0.67) with 'price.' This implies that higher-grade properties tend to have higher prices.

'Sqft_above' (0.61) and 'sqft_living15' (0.59) also show moderate positive correlations with 'price.'

'View' has a positive correlation of 0.40, suggesting that properties with better views tend to have higher prices.

Weak to Moderate Positive Correlations:

'Bathrooms' (0.53) and 'sqft_basement' (0.32) have moderate positive correlations with 'price.' This means that more bathrooms and a larger basement area are associated with higher prices.

'Floors' (0.26) and 'bedrooms' (0.31) have weaker positive correlations with 'price' compared to other features.

Weak Correlations:

'Waterfront' (0.27) and 'sqft_lot15' (0.08) have weak positive correlations with 'price.'

'Condition,' 'yr_built,' 'yr_renovated,' 'sqft_lot,' and 'floors' have correlations close to 0, indicating weak linear relationships with 'price.'
