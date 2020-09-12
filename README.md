# KNOW-I - STRAWHATS 
## WINE-QUALITY-ANALYSIS 🍷
The objective of this project is to predict the quality of wine (White and Red) using various attributes such as acidity, residual sugar, pH, sulphur dioxide, density, alcohol, etc. The model is trained using Logistic Regression, Random Forest Classifier(RFC) and SVC  algorithms which gives an accuracy of 93%.

The dataset was taken from Kaggle
## JUSTIFICATION 📝
#### ADVANTAGES OF LOGISTIC REGRESSION

It is very efficient, does not require too many computational resources, it’s highly interpretable, it doesn’t require input features to be scaled, it doesn’t require any tuning, it’s easy to regularize, and it outputs well-calibrated predicted probabilities.

Logistic regression does work better when you remove attributes that are unrelated to the output variable as well as attributes that are very similar (correlated) to each other.

Logistic Regression is easy to implement and very efficient to train.

#### ADVANTAGE OF USING RFC
It is a very efficient algorithm,which can run on huge datasets.

It has methods for balancing error in class population unbalanced data sets.

Also, since we have selected the most important features for the model, it gives a greater accuracy.

#### WHY NAIVE BAYES GAVE A LOWER ACCURACY

"Naive" means independent, which means all the features should be independent of each other, since the algorithm takes only conditional probability. But, in our dataset, we cannot completely assume that all the features are completely mutually independent. Hence, it gave a lower accuracy.

Another reason is, if a categorical variable has a category in the test dataset, which was not observed in training dataset, then the model will assign a zero  probability and will be unable to make a prediction.
