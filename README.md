# Kaggle-The-Porto-Seguro-Competition


Competition to build a model that can be used to predict whether or not a driver insured with
Porto Seguro will file an insurance claim. Basic instructions for the Kaggle challenge, including training
and test data sets, can be found here: https://www.kaggle.com/c/porto-seguro-safe-driver-prediction. After
downloading and unzipping the training.csv and test.csv files, you will use the training set to build and
validate a model that can predict whether or not a driver will file a claim.
The training and test files contain the same predictors. The only difference is that the test set does not
contain target labels. The Kaggle competition provides the following information about the anonymized
features:
• In the train and test data, features that belong to similar groupings are tagged as such in the feature
names (e.g., ind, reg, car, calc).
• In addition, feature names include the postfix bin to indicate binary features and cat to indicate
categorical features.
• Features without these designations are either continuous or ordinal. Values of -1 indicate that the
feature was missing from the observation.
• The target column signifies whether or not a claim was filed for that policy holder.
Your task is to use the training set in order to predict results for the holdout test set. After selecting your
final model, you will generate predictions for the test set and save the predictions to a file that is formatted
exactly like the sample_submission.csv file contained in the competition zip download. After saving the CSV
containing your predictions, you will upload your predictions to Kaggle and submit them to the competition.
