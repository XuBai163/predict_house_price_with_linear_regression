# predict_house_price_with_linear_regression
This is a small project that builds a linear regerssion which predicts the house price. The project is taught by Flare Zhao in his course, "Python 3 Intro to Artificial Intelligence".

There are in total 5 factors which might affect the housing price: size, income, number of rooms, house age, area of population. Each of these factors are shown visually with the price.

The first linear regression model is trained on only one factor, the size. A prediction is made based on the original data and the results are evaluated with mean squared error and r2 score. The prediction linear function is also visually displayed with the original data (size). 

The second linear regression model is trained on all five factors. A prediction is then made, the results were also evaluated. The predicted results and actual data were both displayed on the same figure.

Finally, a prediction is made on random testing data, [65000,5,5,30000,200].

