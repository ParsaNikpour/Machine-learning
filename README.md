# Optimization
In this project I build a machine learning model in Jupyter Lab. I used diabetes data from scikit-learn datasets. This program has mutliple sections.

*Section 1

In the first one I code it from scratch. I used linear regression and gradient descent to find the optimal parameters, w and b. 

![1](https://user-images.githubusercontent.com/111052950/184142209-f3a7aeaa-e40a-4131-8fee-c9f88326c8bc.JPG)

First I import the packages and load the data and also, represent it in pandas dataframe.
Look at the "age" column. The values are between -1 and 1. It means that the data has already been preprocessed, so it doesn't need to preprocess it.

![2](https://user-images.githubusercontent.com/111052950/184143015-eb234ff8-15d8-47a3-adc3-70f7230ebe85.JPG)

In the following codes I checked for wrong values in X and y.
And then i made cost function and gradient desent function. The parameters are 5000 iterations and alpha equals to 2. I ran gradient descent a couple of times befor and It gave me those values for w and b. Now as you can see, I run gradient descent one again to find better w and b. After 5000 iterations we finally got ultimate values for b and w.

![3](https://user-images.githubusercontent.com/111052950/184143958-f8712689-ca5b-49eb-a942-2ec757d96bae.JPG)

And here's the result. Predicted values VS y. Who won? I think we won this match. Yeaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaah!!!!


*Section2

In this section we're going to look what scikit-learn will do. Here I used two methods: SGDRegressor and SVR. The next lines of codes are eaaaaaasy. I used fit and then predict. By looking at the results it's obvious that the cost of SGDRegressor is lower that SVR.

![4](https://user-images.githubusercontent.com/111052950/184145434-025d744f-80e8-4432-b859-a7670b8fa799.JPG)
![5](https://user-images.githubusercontent.com/111052950/184145525-d20ec27f-30c8-4811-92a5-f0bbbce524e4.JPG)

