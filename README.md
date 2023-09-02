# InstagramReach

This is a regression model trained on the data stored in the csv file uploaded here. This model takes various columns of the dataset, checks its relationship with the dependent variable(Followers)
and predicts the same for an unknown value( a part of the test set).
On implementation it was found that without hyperparameter tuning, the random_forest_regression provided the best result. But, it was only later that I found that the PassiveAgressiveRegressor is the 
best suited model for this kind of data where data is added continuously and hence it has provided me the best result so far.
