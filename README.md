# Black-Friday-Analysis


The main objective of this project is to Predict the purchasing power of the customers.

Sub questions regarding this project are as follows.
 1) What are we doing ?
 2) Why are we doing this ?
 3) Our Target Customers
 4) What have we done?
 
 After proper analysis, these are conclusions made the dataset.
 
##1) What are we doing ?
With this growing market of retail, we are going to do study the data from the black friday sales for Retail industry. We will put some lights on data to study the cases of markets demand and people's purchasing power.

##2) Why are we doing this ?
We are doing this for multiple reasons :-
a) To determine the strenght of purchasing power according to different section of the socity so that Retail Market can follow accoringly.
b) Companies should be aware of the product as in to which section they need to target according to the project Categories.

##3) Target Customers :-
We are doing this for the retail industry to determine their demand, their sales, purchasing power of the customers and puting the product categories correct for the competive sale.

##4) What have we done?

comparision between different models :-

1)Linear regression 2)Decision Tree 3)Accuracy Score 4)Accuracy Score
Conclusion

In this project, the blackfriday dataset has been explored. While EDA revealed some interesting relationships among different features, for the purpose of predicting customer's Purchase, the top three features useful included Product_Category_1, Product_ID and User_ID. With a roughly tuned Random Forest model with max_depth = 9 and n_estimators = 300, the RMSR for predicting Purchase of this model was shown to be ~2911.
However, if the goal is to predict Purchase for the new customer who have never been in the store, those customer-specific and product-specific information cannot be utilized. In this case, only the low-level features can be utilized to train the model. In this case, the model perfornace of the test set was ~4876.
