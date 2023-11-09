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


![download](https://github.com/ddy623/Prediction-of-Product-Sales/assets/129712664/1a3bf351-0562-4e17-ba19-a4eeec5816cd)


Figure 1. The data shows that Item_Type shows variations among items sold. Fruits and Vegetables sold more than any other item.



![download](https://github.com/ddy623/Prediction-of-Product-Sales/assets/129712664/a8f7edf6-4598-4335-8f05-c32b5b23d7fd)



Figure 2. The data shows that the Item_MRP is about 300.

(https://github.com/ddy623/Prediction-of-Product-Sales/assets/129712664/67f3b6f6-29b7-47c6-8860-768b1f724cd7)



![download](https://github.com/ddy623/Prediction-of-Product-Sales/assets/129712664/0af870b4-9981-4f94-8b1b-0793af788bfc)



Figure 3. Model shows the coefficients using Linear Regression. It shows that Item_MRP, Item_Type_Seafood and Item_Type_Bread played a role on the impact of sales.

                      


![download](https://github.com/ddy623/Prediction-of-Product-Sales/assets/129712664/7a73b990-a4f2-432e-b80f-a415a5a287c0)


Figure 4. Model shows which features were impact sales based upon the Random Forest Trees.  It indicatees that Item_MRP, Item_Visibility and Item_Weight also had an impact on sales.

