# **Classification thanks to the SVM model with 7 years of ozone data with Machine Learning**
I developed 2 machine learning software that predict and classify ozone day and non-ozone day. The working principle of the two is similar but there are differences. I got the dataset from ics.icu. Each software has a different mathematical model, Gaussian RBF and Linear Kernel, and classifications are visualized in different ways. I would be happy to present the software to you!

_Example:_ `model_ozone = PCA(n_components=72).fit(X_train)`
 
`model = svm.SVC(kernel='rbf', gamma=0.05, C=3)`

`model_ozone = svm.SVC(kernel='linear', C=3)`

**I am happy to present this software to you!**

`#Accuracy: 0.9602739726027397` Linear Model

`#Auc Roc Curve Score:  0.5617836676217765` Linear Model

`#Auc Roc Curve Score:  0.5` RBF Model

`#Precision Score:  88.06896551724138` Linear Model

`#Recall Score:  56.178366762177646` Linear Model

`#F1 Score:  59.79183681221629` Linear Model

`#Precision Score:  47.80821917808219` RBF Model

`#Recall Score:  50.0` RBF Model

`#F1 Score:  48.87955182072829` RBF Model


#Linear Confusion Matrix #[[1669    7]
                          [ 115   13]]
#Gauss RBF Confusion Matrix #[[1676    0]
                            [ 128    0]]


Data Source: [DataSource]
###**The coding language used:**

`Python 3.9.6`

###**Libraries Used:**

`Sklearn`

`Pandas`

`Numpy`

`Pylab`

`Matplotlib`
### **Developer Information:**

Name-Surname: **Yiğit Çitören**

Contact (Email) : **ycitoren@gmail.com**

LinkedIn : **[https://www.linkedin.com/in/yi%C4%9Fit-%C3%A7it%C3%B6ren-729293274/][LinkedinAccount]**

[LinkedinAccount]: https://www.linkedin.com/in/yi%C4%9Fit-%C3%A7it%C3%B6ren-729293274/

[DataSource]: https://archive.ics.uci.edu/ml/index.php

<img src="https://raw.githubusercontent.com/emirhanai/Classification-thanks-to-the-SVM-model-with-7-years-of-ozone-data-with-Machine-Learning/main/ozone-normal-day-classification-WSR0-WSR1.png" alt="ozone-normal-day-classification-WSR0-WSR1">
<img src="https://github.com/emirhanai/Classification-thanks-to-the-SVM-model-with-7-years-of-ozone-data-with-Machine-Learning/blob/main/ozone-normal-day-classification-2.png?raw=trueg" alt="ozone-normal-day-classification-2">
<img src="https://github.com/emirhanai/Classification-thanks-to-the-SVM-model-with-7-years-of-ozone-data-with-Machine-Learning/blob/main/ozone-normal-day-classification-1.png?raw=true" alt="ozone-normal-day-classification-1">
