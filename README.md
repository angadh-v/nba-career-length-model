# nba-career-length-model
found this nice dataset on Kaggle (https://www.kaggle.com/datasets/yakhyojon/national-basketball-association-nba). 1300 players and their stats and a binary field that tells if the player has been in the league for more than 5 years or not. The idea is to fit a model that predicts the value of the binary column based on other stats. 
Used several popular supervised learning algorithms: Logistic regression, Decision tree, Random forest, Multinomial Naive Bayes, Support Vector Machines, Gradient Boosting, K-Nearest Neighbours, Linear Discriminant Analysis and Multi Layer Perceptron based classifiers. 
Messed around with test-train splits (20 to 40 percent) and model parameters to slightly optimise performance. Finally compared the quality of different models using standard metrics like Precision, accuracy, f1 scores and confusion matrices.
Further steps: try to fit a deep learning model.
