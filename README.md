# 572_Data_Mining
CSE 572 Data Mining Projects

Part 1:
Handle asynchronous temporal data, interpolate and clean the data, and then calculate 36 metrics based set ranges during each day and the average percentage of each metric’s values for all days

Part 2:
Find all locations in insulin data file where patient records carbs intake and a 2 hour window after without any more recorded carbs. Then find indexes of 2 hour chunks of time after where no food was recorded. This is done for 2 patients, the data is combined, cleaned, interpolated. Then the features are extracted and a machine learning algorithm is trained on the feature matrix. Different models were tested and evaluated using recall, precision, and F1 score using k-fold validation to pick the best model.
The model is then saved and used again on a test file, where data is read, features extracted, and then predictions are outputted in a csv file.