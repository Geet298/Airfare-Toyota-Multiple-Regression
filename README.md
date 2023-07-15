#Project 

In this project, I am working on two separate tasks related to data analysis and predictive modeling using different datasets. 

Task 1: Toyota Corolla Dataset
The dataset, "ToyotaCorolla.csv," contains information about used Toyota Corolla cars on sale in the Netherlands during late summer of 2004. The objective is to predict the price of a used car based on its specifications. 
The descriptions of the variables are as follows:
• Price: Offer price in Euros
• Age: Age in months as of August 2004
• KM: Accumulated kilometers on odometer
• HP: Horsepower
• Met_Color: Metallic color? (Yes = 1, No = 0)
• Automatic: Automatic (Yes = 1, No = 0)
• Doors: Number of doors
• Weight: Weight in kilograms

1. Regression Analysis and Data Partitioning:
   - Explored the purpose of partitioning data into training and validation sets in regression analysis.
   - Described the utilization of the training set for model training and the validation set for assessing model performance.

2. Scatter Plots for Price and Continuous Predictors:
   - Constructed two scatter plots: Price against Age and Price against KM.
   - Plotted Price on the y-axis in both figures.
   - Analyzed the relationship between Price and each continuous predictor.
   - Determined which predictor, Age or KM, is a better predictor for Price in the context of simple linear regression.

3. Multiple Linear Regression:
   - Partitioned the dataset into 80% training and 20% validation sets with a random seed of 77.
   - Ran a multiple linear regression on the training set.
   - Derived the fitted predictive linear equation (with a precision of 4) to predict the price of used cars based on Age and KM.

4. Prediction for a Toyota Corolla Used Car:
   - Utilized the fitted multiple linear regression model to predict the price of a specific Toyota Corolla used car.

5. Mean Absolute Error on the Validation Set:
   - Calculated the mean absolute error (MAE) to assess the performance of the multiple linear regression model on the validation set.

6. Mean Absolute Error on the Training Set:
   - Calculated the mean absolute error (MAE) to evaluate the performance of the multiple linear regression model on the training set.

Task 2: Airfare Prediction on New Routes
In this task, the dataset "Airfares.csv" is provided, which contains real data collected between Q3-1996 and Q2-1997. The objective is to predict average airfare on new routes, considering various variables.

• COUPON: average number of coupons (a one-coupon flight is a non-stop flight, a
two-coupon flight is a one stop flight, etc.) for that route
• NEW: number of new carriers entering that route between Q3-96 and Q2-97
• SW: whether Southwest Airlines serves that route (Yes = 1) or not (No = 0)
• HI: Herfindel Index – measure of market concentration (refer to BMGT 681)
• S_INCOME: starting city’s average personal income
• E_INCOME: ending city’s average personal income
• S_POP: starting city’s population
• E_POP: ending city’s population
• DISTANCE: distance between two endpoint airports in miles
• PAX: number of passengers on that route during period of data collection
• FARE: average fare on that route

1. Model for Average Fare Prediction:
   - Partitioned the data into 70% training and 30% validation sets with a seed of 22.
   - Ran a multiple linear regression on the training set to predict average fare using all other predictors.
   - Determined the fitted coefficient values for the predictors "NEW" and "PAX."

2. Average Fare Prediction for New Route:
   - Utilized the fitted multiple linear regression model to predict the average fare for a specific route with given characteristics.

3. Reduction in Average Fare if Southwest Covers the Route:
   - Predicted the reduction in average fare for the route mentioned in question 2 if Southwest Airlines decides to cover the route using the fitted model.

4. Scatter Plot for Model Evaluation:
   - Created a scatter plot to visualize the relationship between the actual target values and the predicted values of the validation set.
   - Set the x-label to "Predicted values" and the y-label to "Actual values."
   - Commented on the performance of the linear regression model based on the scatter plot.

5. Histogram of Model Residuals/Errors:
   - Created a histogram of the model residuals/errors for the validation set.
   - Set the number of bins to 20.
   - Set appropriate labels for the histogram.

6. Factors Unavailable for Fare Prediction on New Routes:
   - Identified and discussed the factors that would not be available for predicting average fare on new routes before flights start operating on those routes.

7. Analytics Plan for Model Evaluation:
   - Outlined an analytics plan to determine whether a model using only available factors before flights begin on a new route is sufficient or whether it is worthwhile to rebuild the model once flights start operating.

By following these steps, I have worked on analyzing the relationships between variables, building predictive models, making predictions, evaluating model performance, and deriving meaningful insights from the provided datasets.