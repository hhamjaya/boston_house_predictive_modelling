# Data Science Lab 2

Use a supervised learning approach to build a predictive model where the output is “MEDV - Median value of owner-occupied homes in $1000’s”
Dataset: Boston Dataset

percapitacrimeratebytown proportionofresidentiallandzonedforlotsover25,000sq.ft.
proportionofnon-retailbusinessacrespertown CharlesRiverdummyvariable(=1iftractboundsriver;0otherwise) nitricoxidesconcentration(partsper10million)

## Dataset
Features on the Boston Dataset
1. CRIM: Per capita crime rate by town.
2. ZN: Proportion of residential land zoned for large lots (over 25,000 sq. ft.).
3. INDUS: Proportion of non-retail business acres per town.
4. CHAS: Charles River dummy variable (1 if tract bounds river; 0 otherwise).
5. NOX: Nitric oxides concentration (parts per 10 million).
6. RM: Average number of rooms per dwelling.
7. AGE: Proportion of owner-occupied units built prior to 1940.
8. DIS: Weighted distances to five Boston employment centers.
9. RAD: Index of accessibility to radial highways.
10. TAX: Full-value property tax rate per $10,000.
11. PTRATIO: Pupil-teacher ratio by town.
12. LSTAT: Percentage of lower status of the population.
13. MEDV: Median value of owner-occupied homes in $1000s (the target variable for prediction).


## Step 0 – Visualization and EDA:
In this initial step, the dataset is visually explored and subjected to Exploratory Data Analysis (EDA). Visualizations and statistical analyses are employed to understand the distribution of features, identify potential outliers, and explore relationships between variables. This step lays the foundation for subsequent decision-making in the modeling process.

## Step 1 – Data Processing and Choosing the Supervised Learning Approach:
Data processing involves handling missing values, scaling features, and encoding categorical variables. Additionally, based on the nature of the problem (regression, classification, etc.), a supervised learning approach is chosen. For the Boston Housing Dataset, which involves predicting housing prices, a regression approach is suitable.

## Step 2 – Training & Test Dataset:
The dataset is divided into two subsets: a training set used to train the machine learning model, and a test set employed to evaluate the model's performance on unseen data. Commonly, an 80-20 or 70-30 split is applied, with a larger portion designated for training to ensure an adequate model learning process.

## Step 3 – Train the Model:
A machine learning model, such as a Linear Regression model, is chosen and trained using the training dataset. The model learns the patterns and relationships within the data, adjusting its parameters to make accurate predictions. The choice of the model depends on the nature of the problem and the characteristics of the dataset.

## Step 4 – Performance Evaluation:
The trained model is evaluated using the test dataset to assess its predictive performance. Common regression metrics, such as Mean Squared Error (MSE) and R-squared value, are computed. These metrics quantify how well the model generalizes to new, unseen data. Visualization techniques, like scatter plots, may also be employed to compare actual vs. predicted values and gain insights into the model's behavior. This step is crucial for determining the effectiveness and reliability of the chosen machine learning model.

## Overall Feedback:
Your assignment covers all needed sections. Well done! I especially appreciated you used shap library. 