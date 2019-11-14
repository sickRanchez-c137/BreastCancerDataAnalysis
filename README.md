# BreastCancerDataAnalysis
The data set obtained from Kaggle at https://www.kaggle.com/uciml/breast-cancer-wisconsin-data/data. This repository demonstrates some basic data analysis operations to be performed in python using numpy, patplotlib and pandas.

The jupyter notebook file can be found at [pynb file](BreastCancerDataAnalysis.ipynb).

Following table shows the different classification techniques used.

| Classification Method |
|------|
| Random Forest (Gini) |
| Random Forest (Entropy) |
| Multi Layer Perception (ReLU) |
| Multi Layer Perception (tanh) |
| Multi Layer Perception (sigmoid) |
| SVM NuSVC |
| SVM LinearSVC |
| SVM SVC Linear |
| SVM SVC RBF |
| Gaussian Naive Bayes |
| Decision Tree (Gini) |
| Decision Tree (Entropy) |
| Logistic Regression |
| KNN |

## Results
After analyzing the accuracy of all the models, the conclusion reached are:
* KNN with p=2 and num of neighbour at 5% of total data sets gives 98.2% accuracy
* Multi Layer Perceptron with tanh activation with 12 hidden layers gives 98.2% accuracy on Validation Set
