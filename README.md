# Prediction-of-Product-Sales

By: Deidre Hunt

Business Problem:
What products at a grocery store has the most impact on sales?

Data:
The data shows that some items were sold more than others and that item visibility played a role in sales.  The target of the project was outlet_sales and the features of the assignment were: Item_Weight, Item_Visibility, Item_MRP, and Outlet Establishment Year.  

Methods:
Regression Models were used to predict sales such as Linear Regression Model and Random Forest Trees.

Results:
Based upon the data, we were able to see that Item Weight, Item MRP and Item Visibility played a much greater role on sales than Item Fat Content or Item Type. 

In order to analyze the data, we used Random Forest and Linear Regression Model. The Random Forest Model showed better results on the training data than the Linear Regression Model.  Using GridSearch,the training data, the Random Forest Model showed 0.94 and on the test data, the results indicated 0.56. On the other hand, the Linear Regression Model the training and test data were at 56.4, which was relatively the same.
Random Forest Models are powerful and they have numerous hyperparameters to improve their performance. When we used GridSearch CV, the data showed the training data was similar to the Random Forest Model, which indicates that when it is tuned, data works similar.
Random Forest Models are powerful and they have numerous hyperparameters to improve their performance. When we used GridSearch CV, the data showed the training data was similar to the Random Forest Model, which indicates that when it is tuned, data works similar.

![download](https://github.com/ddy623/Prediction-of-Product-Sales/assets/129712664/fe24a491-5982-4114-9b68-94a8dfb36e14)
The data shows that the Item_Type has variation across the data. Some items sold more than others.

![download](https://github.com/ddy623/Prediction-of-Product-Sales/assets/129712664/d1d67329-674a-4e03-af09-bb645477ed11)
The data shows that Item_MRP is at 300.
