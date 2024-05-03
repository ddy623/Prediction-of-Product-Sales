# Prediction-of-Product-Sales

By: Deidre Hunt

Business Problem:
What products at a grocery store has the most impact on sales? The products were dairy, soft drinks, meat, fruits and vegetables,household items, baking goods, snack and frozen foods, breakfast, health and hygiene products, hard drinks, canned food, breads, starchy foods, and seafood. It also included products that were considered as other (e.g.miscellaneous products).

Data:
The data shows that some items were sold more than others and that item visibility played a role in sales.  The target of the project was outlet_sales and the features of the assignment were: Item_Weight, Item_Visibility, Item_MRP, and Outlet Establishment Year.  

Methods:
This project has two components. The first is an Exploratory Data Analysis and the second component consists of using Machine Learning to analyze the data.  

Exploratory Data Analysis is a method used to analyze and summarize data sets. With this method, we were able to see variation across the data and some items sold more than others.  The data shows that Fruits and Vegetables, Snack Foods, and Household items were the highest among items sold. See figure 1.

Another method used was Machine Learning. Machine Learning is a branch of artificial intelligence(AI) that focuses on using data and algorithms. The methods that were used were Regression models, which were Linear Regression and Random Forest Tree Models.  

Results:
Based upon the data, we were able to see that Item Weight, Item MRP and Item Visibility played a much greater role on sales than Item Fat Content or Item Type, as this was indicated in the Random Forest Tree Model( See Figure 3). However, the Linear Regression Model using coefficients indicated that high among Item_MRP, Item_Seafood, and Item_Bread, which means these three items had the most impact on sales (See Figure 4). 





![download](https://github.com/ddy623/Prediction-of-Product-Sales/assets/129712664/1a3bf351-0562-4e17-ba19-a4eeec5816cd)


Figure 1. The data shows that Item_Type shows variations among items sold. Fruits and Vegetables sold more than any other item.



![download](https://github.com/ddy623/Prediction-of-Product-Sales/assets/129712664/a8f7edf6-4598-4335-8f05-c32b5b23d7fd)



Figure 2. The data shows that the Item_MRP is about 300.

(https://github.com/ddy623/Prediction-of-Product-Sales/assets/129712664/67f3b6f6-29b7-47c6-8860-768b1f724cd7)



![download](https://github.com/ddy623/Prediction-of-Product-Sales/assets/129712664/0af870b4-9981-4f94-8b1b-0793af788bfc)



Figure 3. Model shows the coefficients using Linear Regression. It shows that Item_MRP, Item_Type_Seafood and Item_Type_Bread played a role on the impact of sales.

                      


![download](https://github.com/ddy623/Prediction-of-Product-Sales/assets/129712664/7a73b990-a4f2-432e-b80f-a415a5a287c0)


Figure 4. Model shows which features were impact sales based upon the Random Forest Trees.  It indicates that Item_MRP, Item_Visibility and Item_Weight also had an impact on sales.

