##Results
Balanced Accuracy Scores ranged from 0.533 - 0.779
Confusion Matrices were all over the place
Precision for high-risk ranged from 0.01-0.88
Precision for low-risk ranged from 0.99-1.00 (so all models great at this)
Recall for high-risk ranged from 0.38-0.74
Recall for low-risk ranged from 0.40-1.00
F1 for high-risk ranged from 0.01-0.53
F1 for low-risk ranged from 0.57-1.0
Random Oversampling

![alt text]https://github.com/Betsy-Kalkwarf/Credit_Risk_Analysis/blob/main/Metrics/Random%20Oversampling.png

SMOTE

![alt text]https://github.com/Betsy-Kalkwarf/Credit_Risk_Analysis/blob/main/Metrics/SMOTE%20Oversampling.png

Cluster Centroid Oversampling

![alt text]https://github.com/Betsy-Kalkwarf/Credit_Risk_Analysis/blob/main/Metrics/Cluster%20Centroid%20Undersampling.png

SMOTEENN

![alt text]https://github.com/Betsy-Kalkwarf/Credit_Risk_Analysis/blob/main/Metrics/SMOTEENN%20Combo.png

Balanced Random Forest

![alt text]https://github.com/Betsy-Kalkwarf/Credit_Risk_Analysis/blob/main/Metrics/BalancedRandomForest.png

AdaBoost

![alt text]https://github.com/Betsy-Kalkwarf/Credit_Risk_Analysis/blob/main/Metrics/AdaBoost.png

##Summary
Overall, the machine learning algorithms were much better at predicting low-risk than high-risk. This is partially because there was a lot more data for low-risk. Most of the algorithms had balanced accuracy scores under 70%, which don’t seem like good enough models for creditors measuring their risk. The only model I would consider using is the Balanced Random Forest with a balanced accuracy score of 0.779 but the precision for high-risk is very low at 0.03. Overall, I would suggest trying more models and maybe combining algorithms together to find better accuracy, precision, and recall.


