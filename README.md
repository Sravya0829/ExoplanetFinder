# ExoplanetFinder
Using a NASA dataset from the Kepler Space Telescope, trained various machine learning algorithms to determine if a star has an exoplanet using it's light curve.

Created a KNeighborsClassifier model that uses 7 nearest neighbors. 
Found accuracy scores: 
train accuracy = 0.9927
test accuracy = 0.9912
Used confusion matrices to analyze the results.

Created a Logistic Regression model
Found accuracy scores: 
train accuracy = 0.9272
test accuracy = 0.6508
Used confusion matrices to analyze the results

Applied multiple different augmentation techniques to this dataset
Normalization: scaling data so all points lie between 0 and 1.
SMOTE: generates new data for the minority class to help balance the dataset so that the model doesn't always predict the majority class.

Reran the original KNN classifier model on Augmented data to get:
Accuracy scores: 
train accuracy = 0.9442
test accuracy = 0.8824
Analyzed using confusion matrices

Creared MLP nueral network model.

Created along with InspiritAI.
