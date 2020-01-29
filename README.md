# machine-learning-challenge

In this Machine Learning challenge, I used the Kepler Exoplanet Data from: https://www.kaggle.com/nasa/kepler-exoplanet-search-results/data. I tried 7 different machine learning models and a few variations of different variables within those models, along with train & test samples, to try to predict the koi_disposition of whether the object is confirmed as a planet, a candidate for a planet, or false-positive for a planet. The machine learning models I chose plus the accuracy they returned were:

Random Forest Classifier: 87.2 %
Neural Network:           82.4 %
Decision Tree:            82.2 %
kNN:                      80.1 %
Logistic Regression:      65.8 %
Support Vector Machine:   49.7 %
Linear Regression:        35.3 %

The best model is the Random Forest Classifier in the Jupyter Notebook titled "ML Random Forest Classifier."

The file MachineLearningModelRatings.xlsx includes a Pivot Chart with bar graphs for a visual display of the rating of each model.

Details: These independent variables gave the best results for the different combinations I tried:
koi_score
koi_period
koi_time0bk
koi_impact
koi_duration
koi_depth
koi_prad
koi_teq
koi_insol
koi_steff
koi_slogg
koi_srad
ra
dec
koi_kepmag
