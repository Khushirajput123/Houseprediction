# California House Price Prediction using XGBoost
This project predicts **house prices in California** using machine learning. The dataset is obtained from **Scikit-learn’s California Housing dataset** and the model is trained using the **XGBoost Regressor**.
The dataset contains **20,640 records and 8 features**, which describe different characteristics of housing areas.
## Dataset
The dataset is loaded in Google Colab using:
`sklearn.datasets.fetch_california_housing()`
### Features
| Feature    | Description                             |
| ---------- | --------------------------------------- |
| MedInc     | Median income of households in the area |
| HouseAge   | Median age of houses                    |
| AveRooms   | Average number of rooms per house       |
| AveBedrms  | Average number of bedrooms per house    |
| Population | Total population in the area            |
| AveOccup   | Average number of occupants per house   |
| Latitude   | Geographic latitude of the location     |
| Longitude  | Geographic longitude of the location    |

### Target
* **House Value** – Median house price in the area
## Model Used: XGBoost Regressor
XGBoost (Extreme Gradient Boosting) is a powerful **ensemble machine learning algorithm** used for regression and classification tasks.
It works by building multiple decision trees sequentially, where each new tree **corrects the errors of the previous trees**. This process improves prediction accuracy and reduces model errors.
### Why XGBoost?
* Handles large datasets efficiently
* High prediction accuracy
* Prevents overfitting using regularization
* Widely used in machine learning competitions
---
## Model Performance
**Training Performance**
* R² Score: **0.94**
**Testing Performance**
* R² Score: **0.83**
The R² score shows how well the model explains the variance in house prices. A value closer to **1** indicates better prediction performance.
## Tools and Libraries
* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost
## Objective
The objective of this project is to demonstrate a **regression machine learning pipeline** including data loading, training an XGBoost model, and evaluating predictions for house price estimation.
