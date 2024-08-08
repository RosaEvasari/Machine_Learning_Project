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

## Machine Learning models
### **1. Numerical columns**

[R_squared](R_squared_score_comparison_numerical.png)

### **2. Numerical and Categorical columns**
#### 2.1. Without Feature Engineering

#### 2.2. With Feature Engineering

#### 2.3. Apply PCA and Without Feature Engineering


## Key Findings and Insights
- The best model for predicting the house's price with this dataset is ..
- The model has R-squared value of .. which indicates how well the model predicts future outcome.
- The model has mean absolute error of .. indicating the difference between the prediction and the real value of the house's price.

## Additional links:
- Kanban: [Kanban](https://trello.com/b/VaFoOuYu/kanban-machine-learning)
- Presentation:
