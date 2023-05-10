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

## Machine Learning Methods:

	•	Linear Regression Model
	•	Simple Regression Tree Model	
	•	Decision Tree Regressor Model
	•	Tuned Decision Tree Regressor Model
	•	Random Forest Regressor Model
	•	Tuned Random Forest Regressor Model

## Linear Regression Model

We built a linear regression model to predict sales based on the available features. The model was trained and evaluated using the following metrics:

- R^2 Score: 0.5791
- Root Mean Squared Error (RMSE): 1069.5154

## Simple Regression Tree Model

- R^2 Score: 0.1743
- Root Mean Squared Error (RMSE): 1498.0634

## Decision Tree Regressor Model

A decision tree regressor model was implemented to predict sales. The model was trained and evaluated using the following metrics:

- R^2 Score: 0.6145
- RMSE: 1456.8912

## Tuned Decision Tree Regressor Model

To improve the performance of the decision tree model, hyperparameter tuning was performed using grid search. The best parameters were selected based on the R^2 score. The performance of the tuned model is as follows:

- R^2 Score: 0.6279
- RMSE: 1423.7801

## Random Forest Regressor Model

We also utilized a random forest regressor model to predict sales. The model was trained and evaluated using the following metrics:

- R^2 Score: 0.7954
- RMSE: 1012.4567

## Tuned Random Forest Regressor Model

Hyperparameter tuning was performed on the random forest model using grid search. The best parameters were selected based on the R^2 score. The performance of the tuned model is as follows:

- R^2 Score: 0.6112
- RMSE: 1028.0056

- The Final Model Chosen was the Random Forest Regressor Model as our final model due to its superior performance. It achieved the highest R^2 score of 0.7954, indicating that it explains a significant portion of the variance in the sales data. Additionally, it has the lowest RMSE value of 1012.4567, suggesting that it has a smaller average prediction error compared to other models.


# Recommendations

Recommendation would be to deploy and use the Random Forest Regressor Model for sales prediction tasks. It has demonstrated strong predictive capabilities and is expected to provide accurate sales forecasts. However, continuously monitoring and evaluating the model's performance as new data becomes available. This will help identify any changes in the underlying patterns and ensure the model remains reliable and effective.

## Conclusion and Future Work

In this analysis, we compared the performance of different regression models for sales prediction. The results showed that the tuned random forest regressor model performed the best in terms of both R^2 score and RMSE.

For future work, additional feature engineering techniques can be explored to improve the model's performance. Furthermore, gathering more data or incorporating external factors could also enhance the accuracy of the sales prediction.




## Limitations:

	•	The limitations of this analysis include the limited scope of the dataset and the lack of information on external factors that may impact sales. In future analyses, it would be beneficial to include additional data sources and external factors such as economic indicators or marketing campaign


## For Further Information

For any additional questions, please contact: 
#### Peter Tran 
#### hdtran103@gmail.com
