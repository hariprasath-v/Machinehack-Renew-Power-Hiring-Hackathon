# Machinehack-Renew-Power-Hiring-Hackathon

### Competition hosted on <a href="https://machinehack.com/hackathons/renew_power_hiring_hackathon/overview">Machinehack.com</a>

# About

### Create a model to get an ideally functioning turbine’s expected rotor bearing temperature.

### Final Score is 0.01852

### Evaluation Metric is MAPE.

### File information
 
 * machinehack-renew-power-hiring-hackathon_eda.ipynb
    #### Basic Exploratory Data Analysis
    #### Packages Used,
        * seaborn
        * Pandas
        * Numpy
        * Matplotlib
* machinehack-renew-power-hiring-hackathon-model.ipynb
    #### Data Pre-processing and model. 
    #### Packages Used,
        * Sklearn
        * Pandas
        * Numpy
        * Matplotlib
        * pycaret    
     #### Compared multiple regression models using pycaret’s compare_models function. Then took the top 3 models based on the           MAPE then blend the model by using pycaret blend_models function. 
     #### [For more detailed information about the model.](https://github.com/hariprasath-v/Machinehack-Renew-Power-Hiring-Hackathon/blob/main/Approach_Machinehack-Renew-Power-Hiring-Hackathon.pdf)
     

### Xgboost Regressor Residual Plot
![Alt text](https://github.com/hariprasath-v/Machinehack-Renew-Power-Hiring-Hackathon/blob/main/Model%20Visualization%20Charts/Voting%20Regressor%20Residual%20Plot.png)

### Xgboost Prediction Error Plot
![Alt text](https://github.com/hariprasath-v/Machinehack-Renew-Power-Hiring-Hackathon/blob/main/Model%20Visualization%20Charts/Voting%20Regressor%20Prediction%20Error%20Plot.png)

### Top 3 Models
![Alt text](https://github.com/hariprasath-v/Machinehack-Renew-Power-Hiring-Hackathon/blob/main/Model%20Visualization%20Charts/Voting%20Regressor%20Models.PNG)

### Xgboost Feature Importance Plot
![Alt text](https://github.com/hariprasath-v/Machinehack-Renew-Power-Hiring-Hackathon/blob/main/Model%20Visualization%20Charts/Feature%20Importance%20Plot-%20%20%20Xgboost%20Regressor.png)

### SHAP - Xgboost Feature Importance Plot
![Alt text](https://github.com/hariprasath-v/Machinehack-Renew-Power-Hiring-Hackathon/blob/main/Model%20Visualization%20Charts/SHAP%20Feature%20Importance%20Plot%20-%20Xgboost%20Regressor.png)

### Rotor bearing temperature distribution - train and test data
![Alt text](https://github.com/hariprasath-v/Machinehack-Renew-Power-Hiring-Hackathon/blob/main/Model%20Visualization%20Charts/Rotor%20bearing%20temperature%20of%20train%20and%20test%20data.png)
