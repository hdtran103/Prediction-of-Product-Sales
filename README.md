# Prediction-of-Product-Sales
Increasing Sales in Retail Stores

Analysis of Product and Store Variables Impact on Sales
Author: Peter Tran

Business problem:
The retail company wants to increase its sales and profit margins. To achieve this goal, they need to understand which product and store variables have the most significant impact on sales.

Data:
The data used in this analysis is from the sales data of a retail company. 
The dataset contains 8523 observations and 12 variables, including product and store variables.

Methods:
 The following steps were taken to prepare and analyze the data:
	•	The 'Item_Identifier' column was dropped from the dataset.
	•	The categorical variables were one-hot encoded.
	•	The data was split into training and testing sets.
	•	Missing values in the data were imputed using mean imputation.
	•	Two models were built to predict sales: linear regression and decision tree regression.


Results:
Visual 1: Correlation Between Item_MRP and Item_Outlet_Sales
￼

- The scatter plot shows a clear positive correlation between the price of a product and its sales volume. Customers are willing to pay more for higher-quality or more desirable products.

Visual 2 : Average Sales by Store Location
￼
- The bar plot shows significant variation in sales volume across different store locations. Some stores consistently perform better than others, and some regions have higher overall sales volumes than others. This suggests that there may be regional or demographic differences in customer preferences or purchasing behavior.

Model:
- The decision tree regression model was selected as the final model as it had a higher R-squared value and lower RMSE compared to the linear regression model.
- The final model had an R-squared value of 0.37 and an RMSE of 1433.33. This means that the model can explain 37% of the variation in sales and has an average error of $1433.33 in predicting sales.

Recommendations:
Based on the analysis, the retail company can increase sales and profit margins by focusing on the following:
	•	Increasing the prices of high-quality or more desirable products.
	•	Identifying the stores and regions that consistently perform better and investing in those areas.
	•	Understanding regional or demographic differences in customer preferences and purchasing behavior.


Limitations & Next Steps:
The limitations of this analysis include the limited scope of the dataset and the lack of information on external factors that may impact sales. 
n future analyses, it would be beneficial to include additional data sources and external factors such as economic indicators or marketing campaigns.


For further information:
For any additional questions, please contact : hdtran103@gmail.com
