# Titanic-Dataset-Logistic-Regression

## Introduction:
This project aims to predict the survival outcome of passengers on the Titanic using logistic regression. In order to achieve this, we perform exploratory data analysis, clean the dataset, impute missing values, select features, and train a logistic regression model.

## Dataset Description:
The Titanic dataset contains information about the passengers who were onboard the Titanic when it sank, including their age, gender, ticket class, fare, and whether or not they survived. The dataset has 891 observations and 12 features.

## Data Preprocessing:
We perform data preprocessing to clean the data and handle missing values. This involves imputing missing values for the Age and Embarked features, dropping the Cabin feature due to its high percentage of missing values, and converting categorical variables to numerical variables using pd.get_dummies.

## Feature Selection:
We perform feature selection to select the most relevant features for the logistic regression model. This involves using correlation to determine which features are most strongly associated with the target variable.

## Model Training and Evaluation:
We split the dataset into training and testing sets, and train a logistic regression model on the training set. We then evaluate the model's performance on the testing set using metrics such as accuracy, precision, recall, and F1 score.

## Future Work:
In future work, we could explore additional feature engineering techniques to further improve the model's performance. For example, we could try extracting the Title (Dr., Mr., Mrs., etc.) from the Name feature and using it as a feature, or using the Cabin letter as a feature. We could also investigate whether there is any useful information we can extract from the Ticket feature.

By performing these steps, we can build a logistic regression model that can predict the survival outcome of passengers on the Titanic with reasonable accuracy.





