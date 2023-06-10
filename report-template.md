# Report: Predict Bike Sharing Demand with AutoGluon Solution
#### Divine Gaadi

## Initial Training
### What did you realize when you tried to submit your predictions? What changes were needed to the output of the predictor to submit your results?
All my predictions provided positive prediction values so there was no need to change the negative values to zero befor submission.

### What was the top ranked model that performed?
The top performing model was "WeightedEnsemble_L3" this model performed the best in the 3 experiments. the best kappgle score of 0.4464 was gotten after tuning hyperparameters.

## Exploratory data analysis and feature creation
### What did the exploratory analysis find and how did you add additional features?
* There were more bike rides on a working day and less on a holiday
* The datetime column was split into year, month, day and hour columns and the datetime column was dropped
* Independent features such as "season" and "weather" previously categorized as integers were changed to category data type.
* The number of rented bikes increased at higher temperatures.

### How much better did your model preform after adding additional features and why do you think that is?
After adding addtional features, the kappgle score improved from 1.8124 to 0.4653. The additional features provided new information that was not captured initially. this added information helpmed the model understand the underlying patterns and relationships, leading to better predictions.

## Hyper parameter tuning
### How much better did your model preform after trying different hyper parameters?
After hyper parameter tuning, the kaggle score improved from 0.4653 to 0.4464.

### If you were given more time with this dataset, where do you think you would spend more time?
If provided with additional time to work on this dataset, my intention is to explore further potential outcomes by running AutoGluon for an extended period, creating more features and enhanced hyperparameter tuning.

### Create a table with the models you ran, the hyperparameters modified, and the kaggle score.
|model|hpo1|hpo2|hpo3|score|
|--|--|--|--|--|
|initial|prescribed_values | prescribed_values | presets: high quality | 1.8125 |
|add_features|prescribed_values | prescribed_values | presets: high quality | 0.5091 |
|hpo|GBM & NN | search_strategy:auto |presets: high quality | 0.5171 |

### Create a line plot showing the top model score for the three (or more) training runs during the project.



![model_train_score.png](img/model_train_score.png)

### Create a line plot showing the top kaggle score for the three (or more) prediction submissions during the project.



![model_test_score.png](img/model_test_score.png)

## Summary
* The AutoGluon AutoML framework for tabular predcition was used to incorporated into the bike sharing demand project and it helped in training the data on multiple models to find the best performing model.
* It is important to explore your dataset with different visualizations to get a better understanding of the data and create additional features to improve the model.
* It is also imprtant to train the model using different hyperparameters, although hyperparameter tuning does not always guarantee you will get a better performing model.
