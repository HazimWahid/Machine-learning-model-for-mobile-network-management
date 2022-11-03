# Machine-learning-model-for-mobile-network-management
hazim's work...
The current practice of mobile network management involves human interaction and
human work ranging from conducting drive tests that can evaluate mobile network
performance and coverage to diagnosing customer complaints. Predictive network
analytics related to network management involves predicting network performance at
locations or times in which no direct measurement data is available or solving missing
values in the data measurement when conducting the drive test. One of the major
challenges when applying machine learning is to identify the best algorithm from a
variety of algorithms to solve a problem. This study aims to propose the best machine
learning algorithm for predicting mobile network performance. This can be achieved by
comparing several types of machine learning algorithms in predicting mobile network
performance. The methodology includes drive test measurement for data collection,
exploratory data analysis, data preparation, and applying machine learning algorithms
to predict mobile network performance. Since the throughput feature has a strong
correlation with the signal strength performance, it is the targeted parameter in network
performance prediction. Three machine learning algorithms were tested in this study
which are random forest, Gaussian process regression, and K-Nearest Neighbor (KNN)
for throughput prediction. Based on the results and analysis of the evaluation metric
comparison, it shows that the random forest model is the best model that comes with
the highest performance prediction with the R2
score of 0.7919 followed by KNN 0.66
and Gaussian process regression 0.34. The random forest also gets the lowest value for
the evaluation metric error. Random forest achieved the best result because of an
additional layer of randomness that can lessen the variance thus increasing the model
accuracy. Using the hyperparameter tuning technique to adjust the number of trees in
the forest and the value for the depth of each tree in the forest, it will increase the random
forest model performance and accuracy. Based on the feature importance list of the
random forest model, the location of the measurement and signal-to-noise ratio (SNR)
feature plays an important role that affecting network performance prediction.
