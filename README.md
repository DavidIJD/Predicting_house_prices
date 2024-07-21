# Predicting_house_prices
# Findings
* Unique Floor Values:
    * Counted the number of houses with unique floor values and converted the result to a DataFrame.
* Waterfront and Price Outliers:
    * Created a boxplot to determine whether houses with a waterfront view have more price outliers compared to those without.
* Correlation Analysis:
    * Used a regression plot to determine that sqft_above is positively correlated with price.
* Linear Regression on sqft_living:
    * Fitted a linear regression model using sqft_living as the feature to predict price.
    * Calculated the R^2 value, indicating the model's goodness of fit.
* Multiple Linear Regression:
    * Fitted a linear regression model using multiple features: floors, waterfront, lat, bedrooms, sqft_basement, view, bathrooms, sqft_living15, sqft_above, grade, sqft_living.
* Pipeline Creation:
    * Created a pipeline with scaling, polynomial feature transformation, and linear regression to predict price.
    * Calculated the R^2 value of the pipeline model.
* Train-Test Split:
    * Split the dataset into training and testing sets with a 15% test size.
* Ridge Regression:
    * Fitted a Ridge regression model with a regularization parameter of 0.1 using the training data.
    * Calculated the R^2 value using the test data.
* Polynomial Transformation and Ridge Regression:
    * Performed a second-order polynomial transformation on the training and testing data.
    * Fitted a Ridge regression model with a regularization parameter of 0.1.
    * Calculated the R^2 value using the test data after polynomial transformation.
The R^2 values obtained in the different steps indicate the model's performance and goodness of fit, helping to determine the best approach for predicting house prices in King County.
<img width="1789" alt="question 1" src="https://github.com/user-attachments/assets/578b1707-9a15-4bb2-a6f2-1acc89365594">
<img width="1505" alt="Question 2" src="https://github.com/user-attachments/assets/28694f70-b5ae-4287-b7ee-be353185b946">
<img width="1499" alt="Question 3" src="https://github.com/user-attachments/assets/0ac36d8e-f08f-4bd9-b20c-2fd9dbbc4faa">
<img width="1491" alt="Question 4" src="https://github.com/user-attachments/assets/540373ac-e7bd-4000-87ef-126c189f0ee5">
<img width="1473" alt="question 5" src="https://github.com/user-attachments/assets/2dbb2c3a-2dcc-4908-98ed-13490a948410">
<img width="1467" alt="question 6" src="https://github.com/user-attachments/assets/7bed777b-b600-48b9-b3c5-46b62df3c771">
<img width="1502" alt="question 7" src="https://github.com/user-attachments/assets/17da2acf-5fc6-4371-8888-f1d2df018e66">
<img width="1506" alt="question 8" src="https://github.com/user-attachments/assets/049640eb-272f-41f7-9174-17446066b762">
<img width="1491" alt="question 9" src="https://github.com/user-attachments/assets/e781a5af-6f2d-43f5-90b3-2f348c1be79e">
<img width="1478" alt="question 10" src="https://github.com/user-attachments/assets/3a0b9d3d-0912-4001-818e-cc8b7ba2505f">
