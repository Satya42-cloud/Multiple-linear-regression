# Multiple-linear-regression

## Objective:
The primary objective of this analysis is to perform a multiple linear regression (MLR) analysis to predict the price of Toyota Corolla cars based on various attributes provided in the dataset. The analysis involves exploratory data analysis (EDA), model building, performance evaluation, and regularization techniques.

## Dataset Description:
The dataset includes the following variables:

- Age: Age of the car in years
- KM: Accumulated kilometers on the odometer
- FuelType: Type of fuel used (Petrol, Diesel, CNG)
- HP: Horse Power of the car
- Automatic: Whether the car is automatic (1 = Yes, 0 = No)
- CC: Cylinder volume in cubic centimeters
- Doors: Number of doors
- Weight: Weight of the car in kilograms
- Quarterly_Tax: Quarterly tax amount
- Price: Offer price in Euros
  
## Tasks
### Exploratory Data Analysis (EDA) and Preprocessing
- Conduct exploratory data analysis to gain insights into the dataset.
- Generate summary statistics and visualizations for each variable to understand distributions and relationships.
- Perform data preprocessing tasks such as handling missing values, encoding categorical variables, and scaling numerical features.

### Data Splitting
- Split the dataset into training and testing sets (e.g., 80% training and 20% testing) to evaluate model performance.

### Model Building
- Develop a multiple linear regression model using the training dataset.
- Build a minimum of three different MLR models to compare performance.
- Interpret the coefficients of the models to understand the impact of each attribute on the car price.

### Model Evaluation
- Evaluate the performance of the models using appropriate metrics such as R-squared, Mean Absolute Error (MAE), Mean Squared Error (MSE), or Root Mean Squared Error (RMSE) 
  on the testing dataset.

### Regularization Techniques
Apply Lasso (L1 regularization) and Ridge (L2 regularization) methods to the models to address overfitting and enhance model generalization.
Compare the performance of regularized models with the baseline MLR models.
