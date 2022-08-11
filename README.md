# Optimization
In this project I build a machine learning model in Jupyter Lab. I used diabetes data from scikit-learn datasets. This program has mutliple sections.

*Section 1

I code the model from scratch. I used linear regression and gradient descent to find the optimal parameters, w and b. 

![1](https://user-images.githubusercontent.com/111052950/184142209-f3a7aeaa-e40a-4131-8fee-c9f88326c8bc.JPG)

First I import the packages and load the data and also, represent it in pandas dataframe.
Look at the "age" column. The values are between -1 and 1. It means that the data has already been preprocessed, so it doesn't need to preprocess it.

![2](https://user-images.githubusercontent.com/111052950/184143015-eb234ff8-15d8-47a3-adc3-70f7230ebe85.JPG)

In the following codes I checked for wrong values in X and y.
And then i made cost function and gradient desent function. The parameters are 5000 iterations and alpha equals to 2. I ran gradient descent a couple of times befor and It gave me those values for w and b. Now as you can see, I run gradient descent one again to find better w and b. After 5000 iterations we finally got ultimate values for b and w.

![3](https://user-images.githubusercontent.com/111052950/184143958-f8712689-ca5b-49eb-a942-2ec757d96bae.JPG)

And here's the result. Predicted values VS y. Who won? I think we won this match. Yeaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaah!!!!


*Section2

In this section we're going to use scikit-learn. Here I used two methods: SGDRegressor and SVR. The next lines of codes are eaaaaaasy. Fit and then predict. By looking at the results it's obvious that the cost of SGDRegressor is lower that SVR.

Predicted values for SGDR:
![4](https://user-images.githubusercontent.com/111052950/184145434-025d744f-80e8-4432-b859-a7670b8fa799.JPG)

Predicted values for SVR:
![5](https://user-images.githubusercontent.com/111052950/184145525-d20ec27f-30c8-4811-92a5-f0bbbce524e4.JPG)

And finally we can see values of w and b in SGDR method.


*Section 3
Tensorflow
4 dense layers with:
1) 50 units, relu activation
2) 30 units, relu activation
3) 20 units, relu activation
4) 1 units, linear activation

And here's the summary:

![6](https://user-images.githubusercontent.com/111052950/184198869-d6210285-199b-4062-8f92-28f088a86d0b.JPG)

Loss function: MeanSquaredError
Optimizer: Adam(learning_rate=0.01)
epochs = 4

After training we have:
Loss: 38.5859

And the final result:

![7](https://user-images.githubusercontent.com/111052950/184199809-cedf7a2a-822a-488a-96db-2af550ed472f.JPG)
