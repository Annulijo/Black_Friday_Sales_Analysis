# BLACK FRIDAY SALES ANALYSIS

## Project Statement
<p> Black Friday is an informal name for the Friday following Thanksgiving Day in the United States, which is celebrated on the fourth Thursday of November. Retailers experience a significant surge in sales during Black Friday, driven by consumer behavior that is influenced by various factors. However, accurately predicting the total purchase amount for individual customers remains challenging due to the complex interplay of these factors. The goal of this project is to develop a machine learning model that can predict the purchase amounts during Black Friday based on customer demographics, product details, and other relevant features. By leveraging this predictive model, retailers can better understand consumer behavior, optimize inventory, and improve targeted marketing strategies.</p>

###  EDA:
* Around 75% of purchases are made by male consumers, indicating that they are the primary contributors to sales for the retail store. On average, men spend more on purchases compared to women, a trend that is further emphasized when analyzing the total purchase value.
* Analyzed the relationship between Purchase and Marital Status reveals that single men tend to spend the most during Black Friday, while men's spending decreases after marriage, likely due to increased responsibilities.
* Consumers aged 25-40 are the highest spenders, according to the Age feature analysis.
* The Stay_In_Current_City_Years column shows that people who have lived in the city for just one year spend the most. This is likely because those who have been in the city for over four years are more settled and less inclined to make new purchases, unlike newer residents who tend to buy more.
* While City B contributes the most to overall sales income, the specific product analyzed is purchased more frequently in City C.

### Data Preparation
* Used LabelEncoder for encoding the categorical columns like Age, Gender and City_Category
* Used get_dummies form Pandas package for converting categorical variable State_In_Current_Years into dummy/indicator variables.
* Filled the missing values in the Product_Category_2 and Product_Category_3

### Modeling Phase
- Splitted dataset into into random train and test subset of ratio 80:20
- Implemented multiple supervised models such as Linear Regressor, Decision Tree Regressor, Random Forest Regressor.

### Evaluation Metric
Root Mean Square Error (RMSE) is a standard way to measure the error of a model in predicting quantitative data. It’s the square root of the average of squared differences between prediction and actual observation.

## Technologies Used
- Python
- Pandas
- Scikit-learn
- XGBoost
- Jupyter Notebook

### Conclusion
Implanted multiple supervised models such as Linear Regressor,Decision Tree Regressor, Random Forest Regressor and XGBOOST Regressor. Out of these supervised models, based on the RMSE scores XGBOOST Regressor was the best performer with a score of 2853.
