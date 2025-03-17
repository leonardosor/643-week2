This script executes XGBoost model for a Kaggle competition that ultimately classifies the survivors of the Titanic shipwreck except that it has been modified for a space version of the disaster. https://www.kaggle.com/competitions/spaceship-titanic/overview

The feat_eng.py file will clean up and perform basic feature engineering. Whereas the model.py file with take that processed data and train an XGBoost model.

The output of the model.py includes a trained model that can be used to run inference on unseen data. The required libraries are: numpy pandas sklearn xgboost optuna argparse

Usage:

main.py C:Users\user_name\Documents\space_titanic\data\train.csv
