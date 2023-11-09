# Prediction-of-Product-Sales

By: Deidre Hunt

Business Problem:
What products at a grocery store has the most impact on sales? 

Data:
The data shows that some items were sold more than others and that item visibility played a role in sales.  The target of the project was outlet_sales and the features of the assignment were: Item_Weight, Item_Visibility, Item_MRP, and Outlet Establishment Year.  

Methods:
This project has two components. The first is an Exploratory Data Analysis and the second component consists of using Machine Learning to analyze the data.

Based upon Exploratory Data Analysis, we are able to see that there is variation across the data and some items sold more than others.  The data shows that Fruits and Vegetables, Snack Foods, and Household items were the highest among items sold. See figure 1.

Using Machine Learning, we analyze the data using Regression Models.  The Regression models to predict sales, which were Linear Regression and Random Forest Trees.

Results:
Based upon the data, we were able to see that Item Weight, Item MRP and Item Visibility played a much greater role on sales than Item Fat Content or Item Type, as this was indicated in the Random Forest Tree Model( See Figure 3). However, the Linear Regression Model using coefficients indicated that high among Item_MRP, Item_Seafood, and Item_Bread, which means these three items had the most impact on sales (See Figure 4). 


In order to analyze the data, we used Random Forest Trees and Linear Regression Model.   Using GridSearch,the training data, the Random Forest Model showed 0.94 and on the test data, the results indicated 0.56. On the other hand, the Linear Regression Model the training and test data were at 56.4, which was relatively the same.  

The Random Forest Model showed better results on the training data than the Linear Regression Model. Random Forest Models are powerful and they have numerous hyperparameters to improve their performance. When we used GridSearch CV, the data showed the training data was similar to the Random Forest Model, which indicates that when it is tuned, data works similar.
Random Forest Models are powerful and they have numerous hyperparameters to improve their performance. When we used GridSearch CV, the data showed the training data was similar to the Random Forest Model, which indicates that when it is tuned, data works similar.

![download](https://github.com/ddy623/Prediction-of-Product-Sales/assets/129712664/8f790cdc-e9fe-4642-8fdc-0129dc6b6e7e)
Figure 1. The data shows that Item_Type shows variations among items sold. Fruits and Vegetables sold more than any other item.



![download](https://github.com/ddy623/Prediction-of-Product-Sales/asset
Figure 2. The data shows that the Item_MRP is about 300.


![download](https://github.com/ddy623/Prediction-of-Product-Sales/assets/129712664/3bc92f15-07c1-42a4-b7fb-f5b0ac4b3b15)


Figure 3. Model shows the coefficients using Linear Regression. It shows that Item_MRP, Item_Type_Seafood and Item_Type_Bread impact Sales.

                      


![download](https://github.com/ddy623/Prediction-of-Product-Sales/assets/129712664/a62e56ca-5c30-4770-a3c7-ebdbe25e8593)
Figure 4. Model shows which features were impact sales based upon the Random Forest Trees.  It indicatees that Item_MRP, Item_Visibility and Item_Weight impact sales.

