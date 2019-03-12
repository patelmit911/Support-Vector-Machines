# Support-Vector-Machines
The Iris flower data set or Fisher's Iris data set is a multivariate data set introduced by Sir Ronald Fisher in the 1936 as an example of discriminant analysis. 
The data set consists of 50 samples from each of three species of Iris (Iris setosa, Iris virginica and Iris versicolor), so 150 total samples. Four features were measured from each sample: the length and the width of the sepals and petals, in centimeters.
The iris dataset contains measurements for 150 iris flowers from three different species.
The three classes in the Iris dataset:
- Iris-setosa (n=50)
- Iris-versicolor (n=50)
- Iris-virginica (n=50)
The four features of the Iris dataset:
- sepal length in cm
- sepal width in cm
- petal length in cm
- petal width in cm

Now to find the optimal parametrs(C, gamma) of SVM, I did a grid search on some range of parameters. The best score was for C = 10, gamma = 0.1. Finally tested the model on test data to obtain precision and recall both to be 1. Hence the model's performance was very favourable for these paramters.  
