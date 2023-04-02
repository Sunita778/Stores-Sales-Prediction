*Project Title:*
Stores Sales Prediction

*Tech:*
Machine Learning

*Domain:*
Sales & Marketing

### Problem Statement:
Nowadays, shopping malls and Big Marts keep track of individual item sales data in
order to forecast future client demand and adjust inventory management. In a data
warehouse, these data stores hold a significant amount of consumer information and
particular item details. By mining the data store from the data warehouse, more
anomalies and common patterns can be discovered.

Approach: The classical machine learning tasks like Data Exploration, Data Cleaning,
Feature Engineering, Model Building and Model Testing. Try out different machine
learning algorithms that’s best fit for the above case.

Results: You have to build a solution that should able to predict the sales of the
different stores of Big Mart according to the provided dataset.


### **About Dataset**
We have train (8523) and test (5681) data set, train data set has both input and output
variable(s). We need to predict the sales for test data set.

- `Item_Identifier`: Unique product ID
- `Item_Weight`: Weight of product
- `Item_Fat_Content`: Whether the product is low fat or not
- `Item_Visibility`: The % of total display area of all products in a store allocated to the particular product
- `Item_Type`: The category to which the product belongs
- `Item_MRP`: Maximum Retail Price (list price) of the product
- `Outlet_Identifier`: Unique store ID
- `Outlet_Establishment_Year`: The year in which store was established
- `Outlet_Size`: The size of the store in terms of ground area covered
- `Outlet_Location_Type`: The type of city in which the store is located
- `Outlet_Type`: Whether the outlet is just a grocery store or some sort of supermarket
- `Item_Outlet_Sales`: Sales of the product in the particulat store. This is the outcome variable to be predicted.