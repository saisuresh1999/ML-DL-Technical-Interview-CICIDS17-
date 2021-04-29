# ML-DL-Technical-Interview-Problem 1

To begin with, the CICIDS17, which was tedious to understand, and finally, I came up with my points.

Initially, after reading the "Toward Generating a New Intrusion Detection Dataset and Intrusion Traffic Characterization" paper, in a wider perspective, I concluded that it is a problem of Multi-class classification problem. So obviously I was into the models like Support vector machines, Naive Bayes, k-nearest neighbours, Neural networks, and Decision Trees. Also in the paper, they have used around 7 ML algorithms, in which Random Forest Algorithm was having a good F1 score(0.97). Since, Random Forest itself is an ensemble of many decision trees, that made a conviction to be a good choice for the given dataset. With the reference of a couple of research papers and online resources, I also came up with the ML/DL models to support my perspective, where I tried Multinomial Naive Bayes, Random Forest Classifier, Neural Network, and SVM model. In my approach, I first combined and cleaned the given dataset thereafter, I considered 2 cases, where 1st case will be considering all labels, and the other case is just considering 2 labels which will be attacked state and benign state. 

Since it's a multiclass classification problem, the evaluation metrics I consider are, F1 score because in this problem the False Negatives and False Positives are crucial but accuracy is also taken into account. So by considering the F1 score as a metric for performance, RF's(Binary labels) F1 score is 0.99, RF's(All labels) F1 score is 0.86 which better than other models. 

So, I conclude Random Forest Classifier is the most suitable model for the given problem among the multiclass classification models.     

Now, coming to whether Deep Learning models are more effective than the Machine Learning model. In my point of view, I prefer it depends on the problem but since Deep Learning models are having a powerful Feature Engineering stage, DL models seem to be ahead of ML models because, for ML models the feature engineering is done by us whereas, as I said earlier DL has powerful Feature Engineering stage. Also, the early stopping callback, tuning of the model hyperparameters, changing of the hidden layer activation function, dropout, loss function and optimizer should increase accuracy to some extent while using DL models in such ways it can learn and make intelligent decisions on its own. 

But in this problem of Intrusion Detection System, since it is very crucial to choose the parameters and architecture of the neural network, so ML model (RF classifier) takes ahead on DL models. 



