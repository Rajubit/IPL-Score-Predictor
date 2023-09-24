# IPL-Score-Predictor
Developed a python based web application which Predicts the score of the batting team by analysing their previous performance

![ipl_teams](https://github.com/Rajubit/IPL-Score-Predictor/assets/99663437/2ec5b7b5-0a6f-4cf2-b9ce-403d9dcb070c)

# Overview
* I have IPL matches records from year 2008 to 2020.
* I have trained machine learning model for 8 teams which were playing in year 2021.
* Here i have performed hyperparameter tunning on various model and i got Random Forest as best model for this problem statement.
* Gradient Booost algorithm gives 0.850539 r2_score & 1.632532 MAE on train dataset and 0.871335 r2_score & 6.438084 MAE on test dataset.
* Random Forest algorithm gives 0.672894 r2_score & 11.296707 MAE on train dataset and 0.681484 r2_score & 12.173585 MAE on test dataset.
* Difference of train dataset MAE and test dataset MAE is 4.805552 for Gradient Boost.
* Difference of train dataset MAE and test dataset MAE is 0.876878 for Random Forest.
* Here accuracy or r2_score of Gradient Boost algorithm is higher than Random Forest but Random Forest's MAE difference between train and test dataset is lower than Gradient Boost.
* If i select Gradient Boost algorithm which has high r2_score then our model will not perform stable as it performed on train dataset because MAE difference between train and test dataset is high that's why it might generate overfitting issue.
* If i select Radom Forest algorithm which does not have high r2_score still it will perfrom stable as it performed on train dataset because MAE difference between train and test dataset is low.
* Here i have selected Random Forest algorithm with it's hyperparamter which best fit for this problem statement with around 68% of accuracy.
* Application developed using Flask, Javascript, Bootstrap, CSS and HTML

# Data Source
* In this project i have used IPL dataset from kaggle, you can get it from [here](https://www.kaggle.com/datasets/patrickb1912/ipl-complete-dataset-20082020).

# How to use
* Select venue, batting team, bowling tean and fill the inputs with proper information then click on predict button you will get predicted score of batting team.

# Technologies Used
HTML, CSS, Javascript, Bootstrap, Flask, Numpy, matlotlib etc.




