# Cybersecurity-Analytics

This project aims to build a network intrusion detector using machine learning methods, a predictive model capable of distinguishing between intrusions (attacks) and normal connections.

From the 'Dealing with class imbalance' part, the code below shows the frequency counts and percentages of the five classes, indicating that dealing with an imbalanced dataset. Most machine learning algorithms work best when the number of samples in each class are about equal. This is because most algorithms are designed to maximize accuracy and reduce error. When comparing the confusion matrix for each of the three models above, we see that decision tree has the lowest error rates, but this model performed very bad in predicting the u2r class. 346 records of probe class were incorrectly classified as u2r class. Therefore, sorely looking at the overall error rate could be misleading sometimes.
