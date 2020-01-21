# Sales_data_Analysis_Machine_Learning
Exploratory Data Analysis and Building the linear model for Predicting the outlet sales.

# Problem Statement

Machine Learning

Consider a data set (Sales_Dataset.csv) related to sales of items in shops. The fields in Sales_Dataset.csv data set are:

Item_Identifier: Code given to items
Item_Weight: Weight of an item
Item_Fat_Content: Fat content of the item like low, high etc
Item_Visibility: A continuous value indicating the visibility of the item for a customer
Item_Type: Type of the item like dairy, vegetables etc
Item_MRP: Maximum retail price of the item
Outlet_Identifier: Code given to outlets
Outlet_Establishment_Year : Year of establishment of an outlet
Outlet_Size: Size of an outlet like medium, high etc.
Outlet_Location_Type: Location of the outlet in a city like Tier1, 2 etc.
Outlet_Type: Type of the outlet like supermarket, grocery shop etc.

Item_Outlet_Sales: Sale value of an item in outlet. It is a target variable.


Tasks:
•	Use the Sales_Dataset.csv file for fitting the models (Divide this file into training set and testing set)
•	Treat the missing values appropriately
•	Convert the categorical data into numerical data appropriately, if necessary.
•	Normalize the data, if required.
•	Fit linear regression model and compute RMSE and R-Square.
•	Apply regularization techniques on the data to check whether they are better than the basic linear model. Loop through various regularization parameters to display and compare R-Square.
•	Fit the residual plots in all cases.
•	Give your analysis on which of the independent variables have significant impact on the Sales of an outlet. Call it as a best model.
•	Using this best model, predict the values of sales for the data given in the file Test.csv and compute RMSE

NOTE:
•	Give brief explanation about each task that you are going to do.
•	Draw Graphs when and where required and give interpretation of such graphs.
•	Graphs must have proper labels and legends. 
•	At the end of task, give your analysis on the entire dataset, about features, their importance etc.
