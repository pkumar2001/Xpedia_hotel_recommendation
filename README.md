# Kaggle: Expedia Hotel Recommendations
**Competition Link:** https://www.kaggle.com/c/expedia-hotel-recommendations
## Model Description
(https://raw.githubusercontent.com/mandalsubhajit/Kaggle--Expedia-Hotel-Recommendations/master/Model%20Flow.png)
## System Specifications:
* Windows 10
* 4 cores
* 8 GB RAM
* Python 3
* 10 GB Free Disk Space where the files would be saved


## Code Details:
* 0_leakage.py : Leakge Solution
* 1_random_forest.py : Random Forest
* 2_xgboost.py : XGBoost
* 3_sgd_classifier.py : SGDClassifier
* 4_naive_bayes.py : Naive Bayes
* blend_models.py : Blending models 1-4 using weighted average of predicted probabilities
* combine_results.py : Stack output from blending over the leakage solution
* run_loop.cmd : batch file to run codes in loop, e.g. run_loop 1_random_forest.py 10. This will run the code 10 times.
