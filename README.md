# Project_PREDICTING_TIME_TAKEN_TO_PAY_OFF_LOAN

## About Dataset
The dataset includes customers who have paid off their loans, who have been past due and put into collection without paying back their loan and interests, and who have paid off only after they were put in collection. The original dataset contains 113937 rows and 81 columns out of which 12 features of intrest were selected.Eight hundred and seventy-one data points were removed from the analysis due to inconsistencies or missing information.


Dataset source: [here](https://www.kaggle.com/datasets/nurudeenabdulsalaam/prosper-loan-dataset)

## About Training

The process started with understanding the features and relationship with the target using various data exploration techniques.
Feature Engineering and model selection was done in 4 experiments where each experiment has a different combination of feature engineering, resampling, and feature selection techniques. This led to a total of 6 unique algorithms and 24 trained models.

After initial training, the best two models were selected and ensembled for improved model performance.

Hyperparameter tuning was done using Randomized Search to select the best tuning parameters.

The best experiment preprocessing pipeline was selected to train the final model's preprocessor and the ensemble algorithm was then fitted to the preprocessed data.

Learning curves were utilized to measure model performance in terms of overfitting or underfitting.
