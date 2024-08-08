# Dutch House Price Project

The goal of the machine learning model is to predict the price of the house in The Netherlands based on the dataset that we have. 

## Data
Data source: [Data source](https://www.kaggle.com/datasets/bryan2k19/dutch-house-prices-dataset) 

The data consists of information retrieved from the largest real estate website in the Netherlands until 2022: [Funda](https://www.funda.nl/en/). The detail of the data can be found in the metadata.

### Metadata
- address : the address of the house.
- city : the city where the house is located.
- price : price of the house.
- lot_size_(m2) : the area of land on which the house is located.
- living_space_size_(m2) : the area of the house. 
- build_year : year when the house built.
- house_type : type of the house.
- roof : type of the house's roof. 
- rooms : total rooms in the house, which consist of a living room and bedroom(s).
- toilet : total toilet(s) and bathroom(s) in the house.
- floors : total floor(s) that the house has.
- energy_label : shows how energy-efficient the house is. Houses with an A-label are the most energy-efficient, while houses with a G-label are the least energy efficient.
- position : location of the house, for example, in the middle of city or on a quiet road and in a residential area.
- garden : types of garden that the house has, for example, front yard, back yard, or side garden.
- estimated_neighbourhood_price_per_m2 : estimated price/m2 of the neighbourhood of the house. 

## Feature Engineering, Scaling, and Selection
### **Feature Engineering** 

In this project, we use One Hot Encoding for all categorical columns consisting city, living_space_size_(m2), house_type, roof, toilet, bathroom, floors, energy_label, position, and garden. Furthermore, we apply Principal Component Analysis (PCA) method used to simplify a large data set into a smaller set while still maintaining significant patterns and trends.

### **Feature Scaling** 
We use normalization and standardization to adjust the range of features in a dataset. The aim is to ensure that all features are on a same scale. 

### **Feature Selection** 
In order to understand the correlation between numericals columns, we use a heat map as our correlation matrix. 
(heatmap picture)

For the categorical columns, we use chi-square test and Cramer V value to identify the correlation of each column with the price category. 
(summary of chi-square test and Cramer V)

## Hyperparameter Tuning and Model Optimization
### **Models Training**

The models that we use in this project are KNN, Random Forest, Adaptive Boosting, Gradient Boosting, and XGBoost. Based on the models' evaluation, it's proved that XGBoost and Gradient Boosting gives highest R2 values and lowest mean absolute error compared to the rest of the models. 
(summary of MAE, MSE, R2 value of all models)

### **Model Optimization**

The models are optimized with hyperparameter tuning and Grid search.  
(summary of MAE, MSE, R2 value of all models)

## Key Findings and Insights
- The best model for predicting the house's price with this dataset is ..
- The model has R-squared value of .. which indicates how well the model predicts future outcome.
- The model has mean absolute error of .. indicating the difference between the prediction and the real value of the house's price.

## Additional links:
- Kanban: [Kanban](https://trello.com/b/VaFoOuYu/kanban-machine-learning)
- Presentation:
