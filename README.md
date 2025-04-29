
# About the dataset
Dataset can be downloaded from [here](https://www.kaggle.com/rohanrao/air-quality-data-in-india)

## Attributes in the dataset
- **City**: City
- **Date**: Date
- **PM2.5**: Particulate Matter 2.5-micrometer in ug / m3
- **PM10**: Particulate Matter 10-micrometer in ug / m3
- **NO**: Nitric Oxide in ug / m3
- **NO2**:Nitric Dioxide in ug / m3
- **NOx**:Any Nitric x-oxide in ppb
- **CO**:Carbon Monoxide in mg / m3
- **SO2**:Sulphur Dioxide in ug / m3
- **O3**:Ozone in ug / m3
- **Benzene**:Benzene in ug / m3
- **Toluene**:Toluene in ug / m3
- **Xylene**:Xylene in ug / m3
- **AQI**:Air Quality Index
- **AQI_Bucket**:Air Quality Index bucket




**Air Quality Prediction**

**GOAL**

The goal of this project is to predict Air Quality Index (AQI ) form features as particulate matter (PM2.5 and PM10), Nitrogen Oxide (NO), Nitric Dioxide (NO2), Carbon Monoxide (CO), Sulphur Dioxide (SO2), Ozone (O3) etc.

**DATASET**

Dataset can be downloaded from [here](https://www.kaggle.com/rohanrao/air-quality-data-in-india).

**WHAT I HAD DONE**
- Step 1: Data Exploration
- Step 2: Data Cleaning
- Step 3: Data visualization
- Step 4: Data training
- Step 5: Model Creation
- Step 6: Performance Evaluation


**MODELS USED**
-  Linear Regression
-  Lasso Regression
-  Ridge Regression
-  Decision Tree Regressor



**LIBRARIES NEEDED**
- pandas
- numpy
- matplotlib
- seaborn
- sklearn (For data traning, importing models and performance check)


**CONCLUSION**
- By using Linear Regression model 
 ```python
    Accuracy achieved :  78.81
 ``` 
 - By using Lasso Regression model 
 ```python
    Accuracy achieved :  78.81
 ``` 
 - By using Ridge Regression model 
 ```python
    Accuracy achieved :  78.81
 ``` 
 - By using Decision Tree Regressor model 
 ```python
    Accuracy achieved :  99.91
 ``` 
* Accuracy of Regression models- Linear regression, lasso regression and rigde regression is almost same. 

* Whereas accuracy of decision tree regressor is higher and root mean sqaure error is least.

* Decision tree regressor is more efficient model.
