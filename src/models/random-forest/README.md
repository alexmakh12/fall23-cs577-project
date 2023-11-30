

#### Train: Random Forest r<sup>2</sup>:  0.9634

#### Test : Random Forest r<sup>2</sup> :  0.7259

These features go unused in this model

-   **date**: Outside of the scope of this study. Is factor of environment and not home
-   **sqft_living**: Sum of sqft_above and sqft_basement, so those 2 already contain sqft_living
-   **floors**: Number of floors is already contained in sqft_living
-   **yr_renovated**: Most entries will have zero value because those homes are not renovated
-   **lat[titude], long[itude], zipcode, date**: Miniscule variation in these features in this localed dataset


![Grade is the most significant feature](./random_forest_r_squared.png "Random Forest r^2")
![Grade is the most significant feature](./price_distribution.png "Price Distribution")

Most homes cost under $1mm, but there are some that extend into the multimillion.
Price skews to the right