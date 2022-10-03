# Road-Time-series

This repository helps in performing time series prediction on Road Dataset of nearly 25Kms

Objective-

To perform predictions of Parameter 9-13 from the given dataset for every Section.

Methodology Used-

Transformed the Data into Train and Test Dataset, by extracting 10th year data for para 9-13 for every section. 
Then scaled the input using Standard scaler.
After that we Used Tensorflow to implement 3 Layer ANN.
Scaled data rmse is 1.93

