<p align = "center"> 
  <img src = "https://raw.githubusercontent.com/coding-dojo-data-science/CodingDojo_Images/main/data-science.jpg">
</p>


# Increasing Sales in Retail Stores

## Analysis of Product and Store Variables Impact on Sales

#### Peter Tran

##### Choosing a career path in data science can be challenging, especially for those seeking remote work and high salaries. With numerous options available, it can be difficult to determine the best path to take.

## Data Dictionary

<p align = "center"> 
  <img src = "https://raw.githubusercontent.com/coding-dojo-data-science/Project1_Exemplar/main/DS%20Salaries%20Data%20Dictionary.png">
</p>

Data: The data used in this analysis is from the sales data of a retail company. The dataset contains 8523 observations and 12 variables, including product and store variables.

## Methods: The following steps were taken to prepare and analyze the data:
	•	The 'Item_Identifier' column was dropped from the dataset.
	•	The categorical variables were one-hot encoded.
	•	The data was split into training and testing sets.
	•	Missing values in the data were imputed using mean imputation.
	•	Two models were built to predict sales: linear regression and decision tree regression.




 ## Correlation Between Item_MRP and Item_Outlet_Sales
 
<p align = "center"> 
  <img src = "https://github.com/hdtran103/Prediction-of-Product-Sales/blob/main/Visual%201%20Item%20MRPvsOutletSales.png">
</p>

##### The scatter plot shows a clear positive correlation between the price of a product and its sales volume. Customers are willing to pay more for higher-quality or more desirable products.

## Average Sales by Store Location

<p align = "center"> 
  <img src = "https://github.com/hdtran103/Prediction-of-Product-Sales/blob/main/outlet%20distribution.png">
</p>

##### The bar plot shows significant variation in sales volume across different store locations. Some stores consistently perform better than others, and some regions have higher overall sales volumes than others. This suggests that there may be regional or demographic differences in customer preferences or purchasing behavior.

## Model:

	•	The decision tree regression model was selected as the final model as it had a higher R-squared value and lower RMSE compared to the linear regression model.
	•	The final model had an R-squared value of 0.37 and an RMSE of 1433.33. 
	•	This means that the model can explain 37% of the variation in sales and has an average error of $1433.33 in predicting sales.


## Limitations:

	•	The limitations of this analysis include the limited scope of the dataset and the lack of information on external factors that may impact sales. In future analyses, it would be beneficial to include additional data sources and external factors such as economic indicators or marketing campaigns.

## Recommendations:
#### Based on the analysis, the retail company can increase sales and profit margins by focusing on the following:

	•	Increasing the prices of high-quality or more desirable products.
	•	Identifying the stores and regions that consistently perform better and investing in those areas.
	•	Understanding regional or demographic differences in customer preferences and purchasing behavior.


## For Further Information

For any additional questions, please contact: 
#### Peter Tran 
#### hdtran103@gmail.com
