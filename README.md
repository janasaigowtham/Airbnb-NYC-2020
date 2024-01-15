![GitHub Logo](Airbnb.png)
# Airbnb-NYC-2020

Task:
Predict the price of U.S. AirBnB rentals.
Evaluate the solution with reproduceable low root-mean-squared error (RMSE) based on cross-validation.

Data:
As of October 2020, the dataset has 226030 rows and 17 columns of Airbnb listings in the U.S.
The dataset includes NaNs, and data is of mixed types.

The average price is about $219.72.
Minimum night averages between 4 and 5.
There are 4 categories of room type: Entire home/apt, Private room, Shared room, and Hotel room.

There is minimal correlation between price and other columns in the dataset.

Added a column (state). Grouped prices into ranges to improve model performance.

Models:
Linear and multple linear regressions did not perform well for this datase.
KNN regression performed better and so did decision tree.
KNN classifier performed best.
