# machine-learning-challenge

In this Machine Learning challenge, I used the Kepler Exoplanet Data from: [Kepler Exoplanet Data](https://www.kaggle.com/nasa/kepler-exoplanet-search-results/data). I tried 7 different machine learning models and a few variations of different variables within those models, along with train & test samples, to try to predict the koi_disposition of whether the object is confirmed as a planet, a candidate for a planet, or false-positive for a planet. The machine learning models I chose plus the accuracy they returned were: <img src="/machine learning files/ML_Challenge_Model_Accuracy.jpg" alt="Machine Learning Challenge Model Accuracy">

The best model is Random Forest Classifier in the "machine learning files" folder, titled "ML Random Forest Classifier.ipynb."

The file MachineLearningModelRatings.xlsx in the "machine learning files" folder includes a Pivot Chart with the bar graph displayed above.

Details: These independent variables gave the best results for the different combinations I tried:
koi_score \
koi_period \
koi_time0bk \
koi_impact \
koi_duration \
koi_depth \
koi_prad \
koi_teq \
koi_insol \
koi_steff \
koi_slogg \
koi_srad \
ra \
dec \
koi_kepmag

If you would like to install these files, you will need Jupyter Notebook to open the
ipynb files, which contain all of the machine learning models in Python code.