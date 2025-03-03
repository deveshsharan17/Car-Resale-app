# Car Resale valuation prediction App


---
# About The Project
---
The price of any car depreciates over time and is dependent upon  numerous attributes that determine the resale value of the car in  various cities around the USA. These attributes include year of resale,brand, model, miles driven ,overall condition of the car etc. <br>
Car Resale Valuation Prediction App incorporates all these factors into the pricing model that takes into account the  previous car resale data to determine the most accurate price for your car.
<details>
<summary> More About the Project </summary>
Car Resale Valuation Prediction App is Macchine Learning Model that uses the concepts of pattern recognition, as well as other forms of predictive algorithms, to make judgments on incoming data. 
</details>



## Tech Stack

**Frontend:** `streamlit framework`

**Backend:** `python` 

## Getting Started
### Installation

CatBoost (python installation )


```bash
pip install catboost
```
```bash
pip install streamlit
```
Other Dependencies are: `numpy` `pandas` `seaborn` `os` `pickle` `SciPy` `scikit-learn`

#### Use a python IDE to implement predict-car-price-by-catboost-2.py file.


## Run Locally
#### To separately run the  application on your local host, perform the following steps:

Clone the project


Go to the project directory


Run the following commands to start the server side.
```bash
streamlit run streamlit_app.py
```
## Deployment

the rest API is deployed on streamlit global server and the url is a public address:

Link to the app:-

---
# More About the project
## Roadmap

-  Data acquisition - Required data is downloaded from open-sourced data on the Kaggle - https://www.kaggle.com/datasets/austinreese/craigslist-carstrucks-data?select=vehicles.csv kaggle the dataset contains most all relevant information that Craigslist provides on car sales including columns like price, condition, manufacturer and 19 other categories. 


- Data cleaning and feature engineering- the process of selecting, manipulating, and transforming raw data into features that can be used in supervised learning.
- Model Training - With the help of catboost library, I have used a boosted decision tree algorithm to model resale value w.r.t. vehicle's independent features.<br>
`catboost library` - is a machine learning library used to handle categorical (CAT) data automatically.
This library contains the `CatBoostRegressor` and `CatBoostClassifier` models with a similar interface as scikit-learn models.<br>


<br>

- Streamlit for deploying light ML models- Streamlit is an open source app framework in Python language. It helps us create web apps for data science and machine learning in a short time. It is compatible with major Python libraries such as scikit-learn, NumPy, pandas, Matplotlib etc.

## Future Improvement 
- As soon as a car or model is selected, the dropdown and the value that could be selected for a feature should be updated depending upon the attributes of the car or manufactured selected.
- Although categorical boosting seems to be the best algorithm provided the dataset. Other tree based or SVMs could be tried out. More intensive hyper parameter search could be done using grid search.








