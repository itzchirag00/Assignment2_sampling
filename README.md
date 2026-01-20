# Assignment2_sampling Chirag Sood(102317142) 
1.First, the dataset is visualized in a clean and structured manner using YData-Profiling to understand feature distributions, correlations, and overall data quality.

2.From the visualization, the count of each class in the target (Class) feature is examined, which clearly shows that the dataset is imbalanced.

3.The dataset is then split into training and testing sets.

4.Sampling techniques are applied only on the training data because the test data should remain unseen and should represent real-world data.

5.Sampling is performed on the training data to improve model learning by balancing the classes and adding meaningful samples.

6.Five sampling techniques are used:

a.Random Over Sampling

b.Random Under Sampling

c.SMOTE

d.Tomek Links

e.NearMiss

7.Five machine learning models are used:

a.Logistic Regression

b.KNN

c.Random Forest

d.Decision Tree

e.SVM

8.Tomek Links gives higher accuracy for SVM, Logistic Regression, and KNN because it removes data points from both classes that lie very close to each other, reducing noise near the decision boundary.

9.Random Under Sampling gives low accuracy because it removes too many samples from the majority class, leading to loss of information and underfitting.

10.NearMiss also performs poorly since it is an under-sampling technique and removes important majority class data.

11.Random Over Sampling balances the dataset by repeating minority class samples, but this causes overfitting due to duplicate data points.

12.SMOTE gives mixed results and shows less overfitting compared to random oversampling because it generates synthetic minority class samples instead of duplicating existing ones.
