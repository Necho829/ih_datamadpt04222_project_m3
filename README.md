# ih_datamadpt04222_project_m3

CHALLENGE:

Make the best possible diamond price prediction model.

DATA:

diamonds_train.db

LIBRARIES:

- Python 3.7 (conda install python == 3.7)
- Pandas (conda install pandas)
- Sqlalchemy (conda install sqlalchemy)
-Sqlite 3 (conda install sqlite)
- matplotlib
- sklearn

WHAT WE HAVE DONE

-Using SQL commands, we make a new table with all the relevant features of the original Dataset, and create a Dataframe (Pandas).
-Later we have saved the dataframe as CSV to be able to make modifications to it.
-We have made a function to try the outliers and see if the prediction improves significantly.
-Then we import the test dataset and define the target and features to later categorize the features to work on them.
-Later we apply get_dummies to treat the categorical variables and then apply Machine Learning models (train_df and test_df).
-On our two new dataframes, we apply the scaler and train the model using train_test_split.
-After using numerous models, such as linear_model, ElasticNet, GradientBoostingRegressor, we have decided to use RandomForestRegressor, as it gives the best results.

KAGGLE SCORE

So far, the best submissions we have achieved have a score between 580 and 550.
