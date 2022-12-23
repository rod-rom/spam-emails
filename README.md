# spam-emails
Classifying emails messages as spam or ham. 

## Conclusions for Project 1
It appears that the Random Forest model would be a better fit to classifying spam emails than the traditional Decision Tree model. The Decision Tree model is practical but can be inaccurate in some cases which Random Forest focuses on solving by ensembling multiple decision trees to reach a classification

## Conclusions for Project 2
Fusion classifiers and ensemble classifiers are helpful machine learning algorithms that can be used to improve the accuracy of classifying data. Although, from experimentation, AdaBoost tends to underperform compared to fusion classifiers when there is not enough training data. This is most likely due to the fact that during reweighting the samples, not enough wrongly classified samples are being overrepresented and correctly classified samples are underrepresented. When compared against Random Forests, the fusion classifier obtained a lesser classification accuracy. This outcome was expected due to the number of trees set. The majority vote consisted of 1000 “judges”, while for the fusion model there were 3 “judges”. Making use of ensemble methods and majority vote is a powerful tool that can be used to easily improve the accuracy of your models
