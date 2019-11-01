# Predict-useful-life-of-machine-using-ANN
This repository predicts remaining useful life of machine using ANN.

In this project we tried to implement results of above paper named "ANN pump life prediction.pdf"

FFNN is used as ANN and LM algorithm is used to train neural network.
To use LM algorithm pyrenn library is imported using pyrenn.py in repository.
# Dataset
Dataset consists of recordings of 4 bearings every 10 minutes.

# Results
This program shows RMS and Kurtosis graph for each bearing.
Weibull Distribution is used, so weibull parameters are calculated. weibull shape and scale parameters are calculated while location parameter is kept fixed.
Results of test and validation set are shown also training and validation errors of proposed model are calculated.
