# Linear and logistic regression using statsmodels

The directory structure: 

```
├── README.md          <- The README file.
├── data
├── notebooks          <- Jupyter notebooks.
├── requirements.txt   <- The requirements file for reproducing the analysis environment.

```

### Installing development requirements
------------

pip install -r requirements.txt

# Linear and logistic regression using statsmodels 

## Description of the project

### Predicting the prices of houses in the Taiwan real estate dataset:
(A) Determine the relationship between house price per area and the number of nearby convenience stores using the Taiwan real estate dataset
- the independent (explanatory) variable: n_convenience (number of bearby convience stores)
- the dependent (response) variable: price_twd_msq (price per meter square using Taiwan dollars)

(B) Determine the relationship between house price per area and the distance to the nearest MRT (metro) station using the Taiwan real estate dataset
- the independent (explanatory) variable: dist_to_mrt_m (the distance to the nearest MRT (metro) station)
- the dependent (response) variable: price_twd_msq (price per meter square using Taiwan dollars)

(C) Determine the relationship between house price per area and the age of the houses using the Taiwan real estate dataset
- the independent (explanatory) variable: house_age_years (the age of the houses in years)
- the dependent (response) variable: price_twd_msq (price per meter square using Taiwan dollars)

### The fish database
(A) Determine the mass of the fish using the species as a categorical explanatory variable & prove that the coefficients relative to zeros are indeed the mean mass per species

(B) For the Bream species, predict the mass from the length

(C) For the Perch species, predict the mass from the length - nonlinear relationship

(D) For the Roach species, predict the mass from the length - Find extreme values and determine the leverage and influence


### Facebook advertising
(A) Predicting the number of impressions based on the amount of spent money on Facebook advertising 

(B) Predicting the number of Clicks based on the number of impressions 

### Churn prediction
Predict customer churn using the time as the last purchase
- Calculate the odds ratio and the log odds ratio
- Quantify the predictions

## Dependencies
* requirements.txt contains all prerequisites
* pip 23.3.1 and Python 3.11.6
