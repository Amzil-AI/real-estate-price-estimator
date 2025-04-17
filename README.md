# Real Estate Price Estimation using CRISP-DM

This project implements a real estate price estimation engine, following the CRISP-DM methodology. The goal to net sale price of its characteristics and location.

---

## 1. Business Understanding

The project aims to automate and improve the precision of real estate valuation. It targets both professionals and individuals, by using actual sales to train predictive models. 


### Goals : 
- Estimates real estate prices using machine learning
- Align technical goals with business priorities
- Improve valuation automation and accessibility

---
## 2. Data Understanding

The dataset used includes : 
- DVF (Official real estate transaction in France)
- INSEE price indexes (to adjust for inflation)
- Geospatial data (distance to city center, altitude, ect.)
- Socioeconomic indicators (median income, crime rate, population density)

---

### 3. Data Preparation

- Cleaning: removing outliers and incomplete entries
- Normalization using INSEE indexes
- Merging datasets by geolocation
- Features engineering: amenities, state of property, ect.

---

### 4. Modeling

Models tested:
- Linear Regression
- Random Forest & XGboost
- Multilayer Perception (MLP)


---

## 5. Evaluation 

Evaluation metrics:
- RMSE (Root Mean Squared Error)
- MAE (Mean Absolute Error)

---


## 6. Deployment

The final model can be integrated into an API or WEB interfaces to allow real-time property price estimation.




Add README

























