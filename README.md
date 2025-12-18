# ShadowFox-Intermediate
**Project Overview**
This project aims to predict the selling price of used cars using Machine Learning techniques.
The model analyzes various car features and provides an approximate selling price to help sellers and buyers make informed decisions.

**Problem Statement**
Determining the fair selling price of a used car is challenging due to multiple influencing factors such as car age, fuel type, kilometers driven, ownership history, and transmission type.
This project uses Machine Learning regression models to predict car prices accurately based on historical data.

**Machine Learning Approach**
Type: Supervised Learning
Algorithm Used: Random Forest Regressor
Evaluation Metrics:
R² Score
Mean Absolute Error (MAE)
Dataset Description
The dataset contains information about used cars with the following features:

**Feature Name	Description**
Car_Name	Name of the car
Year	Year of manufacture
Selling_Price	Selling price of the car (target variable)
Present_Price	Current showroom price
Kms_Driven	Total kilometers driven
Fuel_Type	Petrol / Diesel / CNG
Seller_Type	Dealer / Individual
Transmission	Manual / Automatic
Owner	Number of previous owners

**Technologies Used**
Python 3.11
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
VS Code / Jupyter Notebook

**How to Run the Project**
Install Required Libraries
pip install pandas numpy matplotlib seaborn scikit-learn
Run the Notebook
Open car_price_prediction.ipynb in VS Code or Jupyter Notebook
Ensure car_data.csv is in the same folder
Click Run All

**Model Performance**
Achieved high R² score (~0.9) indicating good prediction accuracy
Low Mean Absolute Error

**Sample Prediction**
The model can predict the selling price based on:
Present price
Kilometers driven
Fuel type
Seller type
Transmission
Ownership
Car age

**Conclusion**
This project demonstrates how Machine Learning can be effectively used to predict used car prices with good accuracy. It can be further extended by deploying the model as a web application or enhancing accuracy with hyperparameter tuning.

**Future Enhancements**
Deploy using Flask or Streamlit
Add real-time user input
Try other regression models
Perform hyperparameter tuning

Author
Haasini Duddela
Machine Learning Enthusiast
