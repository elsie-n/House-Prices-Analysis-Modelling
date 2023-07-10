# House Prices Analysis/Modelling(Predictive)
### The Data

This project uses the King County House Sales dataset, which can be found in  `kc_house_data.csv` in the data folder in this repo. The description of the column names can be found in `column_names.md` in the same folder. As with most real world data sets, the column names are not perfectly described,a description of what the columns used mean;

The dropped columns include:

* date
* view
* sqft_above
* sqft_basement
* yr_renovated
* zipcode
* lat
* long
* sqft_living15
* sqft_lot15

### Business Problem

The main purpose of the project is to develop a pricing algorithm to help set/predict a target price for the houses in the agency. The goal is to save the company some time and to help ensure consistency in pricing with consideration of the attributes the house has to offer.

Also identify the variable that impact the price of the house the most.

### Datascience process
The process used in the projectv was OSEMN some of the steps included;

#### Scrubbing and Cleaning

some of the things solved included;

- Missing values

- Multicolinearity

- Normalization

#### Exploring the data

- Explored the distribution of prices 

- The relationship between price and other varibales

- Identified the categorical variables in the dataset.

#### Modelling the data

The models used in the project were linear regression model ,multiple regression model and polynomial model.The model that 
stood out with the best price prediction was the polynomial model after two iterations.

#### Interpretation

The Rsqd of both the training data and testing data seem to be at close range this is verified by the graph of the overfitting of both sets having a good fit. Meaning the model is efficient.To increase the efficiency of the pricing the should be itterated as seen from the Rsqd iteraction which is higher meaning the relation of the attributed to the pricing higher ,upto 3 iterations.
