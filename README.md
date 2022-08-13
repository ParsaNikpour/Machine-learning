# Machine Learning
In this project I built a regression machine learning model in Jupyter Lab. I used diabetes data from scikit-learn datasets. This program has mutliple sections:

*Section 1

I code the model from scratch. I used linear regression and gradient descent to find the optimal values for parameters w and b. 

![1](https://user-images.githubusercontent.com/111052950/184142209-f3a7aeaa-e40a-4131-8fee-c9f88326c8bc.JPG)

First I import the packages and load the data and also, represent it in pandas dataframe.
Look at the "age" column. The values are between -1 and 1. It means that the data has already been preprocessed, so it doesn't need to preprocess it.

![2](https://user-images.githubusercontent.com/111052950/184143015-eb234ff8-15d8-47a3-adc3-70f7230ebe85.JPG)

In the following codes I checked for wrong values in X and y.
And then i made cost function and gradient desent function. The parameters are 5000 iterations and alpha equals to 2. I ran gradient descent a couple of times befor and It gave me those values for w and b. Now as you can see, I run gradient descent one again to find better w and b. After 5000 iterations we finally got ultimate values for b and w.

![3](https://user-images.githubusercontent.com/111052950/184143958-f8712689-ca5b-49eb-a942-2ec757d96bae.JPG)

And here's the result. Predicted values VS y.

*Section2

In this section we're going to use scikit-learn. Here I used two methods: SGDRegressor and SVR.



And finally we can see values of w and b in SGDR method.


*Section 3
Tensorflow
