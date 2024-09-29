# ds_hw_20
Homework 20 Submission


Credit Analysis Summary Report

The purpose of the analysis was to utilize various techniques to train and evaluate a model based on loan risk. I used a dataset of historical lending activity from a peer-to-peer lending services company to build a model to ideally identify the creditworthiness of borrowers.

Results:

Train Metrics

    • Accuracy score - .99
    • Precision score - .85
    • Recall Score - .98

Test Metrics

    • Accuracy score - .99
    • Precision score - .87
    • Recall Score - .98


Although there is a major imbalance in the data when looking at loan status the linear regression still did a very good job of identifying the probability of loan status. I thought this would be more pronounced when comparing the train and test datasets, however they were very similar and I didn't recognize signs of being overfit. This suggests the  relationships of the features to the target are linear. In this case because we are looking at features that are linear, a linear regression is a simple and effective model to use. To improve upon this we could retest the data after applying different regularization strategies to see how that would impact the fit of the model.
