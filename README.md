# Fuel Consumption Prediction Using Multiple Regression

## Description
This project uses Multiple Linear Regression to predict fuel consumption based on various vehicle attributes. It demonstrates how multiple features such as engine size, transmission type, and vehicle class can be used together to model fuel efficiency.

---

## Dataset Information

The dataset contains 739 entries and 15 columns with vehicle specifications and fuel consumption data:

- **Model year:** Year the vehicle model was released (int)  
- **Make:** Manufacturer of the vehicle (object)  
- **Model:** Vehicle model name (object)  
- **Vehicle class:** Category of vehicle (object)  
- **Engine size (L):** Engine displacement in liters (float)  
- **Cylinders:** Number of engine cylinders (int)  
- **Transmission:** Transmission type (object)  
- **Fuel type:** Type of fuel used (object)  
- **City (L/100 km):** Fuel consumption in city driving (float)  
- **Highway (L/100 km):** Fuel consumption on highway (float)  
- **Combined (L/100 km):** Combined fuel consumption (float)  
- **Combined (mpg):** Combined miles per gallon (int)  
- **CO2 emissions (g/km):** Carbon dioxide emissions (int)  
- **CO2 rating:** Emission rating (int)  
- **Smog rating:** Smog rating score (int)

---

## Methodology
- Data preprocessing including encoding categorical variables and feature scaling  
- Splitting the data into training and testing sets  
- Building a Multiple Linear Regression model to predict combined fuel consumption  
- Evaluating the model using metrics like Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R²)  
- Analyzing the significance of predictors and interpreting model coefficients  

---

## Results
The multiple regression model effectively predicts fuel consumption, highlighting the impact of key vehicle features on fuel efficiency.

---

## Usage

Clone the repository and install dependencies:

```bash
git clone https://github.com/AbuOmayed/fuel-consumption-prediction.git
cd fuel-consumption-prediction
pip install -r requirements.txt
jupyter notebook notebooks/fuel_consumption_multiple_regression.ipynb
