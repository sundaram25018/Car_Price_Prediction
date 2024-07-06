# Car_Price_Prediction
This project aims to build a machine learning model to predict the prices of cars based on various features. The dataset used contains information about car attributes and their prices. The goal is to provide an accurate prediction model that can be used for pricing new and used cars.

Table of Contents
Introduction
Dataset
Installation
Usage
Model
Results
Contributing
License
Introduction
Predicting car prices is crucial for various stakeholders, including car dealers, buyers, and sellers. This project uses machine learning algorithms to predict car prices based on features like make, model, year, mileage, and more.

Dataset
The dataset used in this project is a collection of car listings with various attributes:

Make: Manufacturer of the car (e.g., Toyota, Honda)
Model: Specific model of the car (e.g., Corolla, Civic)
Year: Year of manufacture
Mileage: Number of miles driven
Price: Price of the car
... (other relevant features)
You can download the dataset (https://www.kaggle.com/datasets/sukhmandeepsinghbrar/car-price-prediction-dataset) or use your own dataset.

Model
The project uses various machine learning algorithms, such as:

"Random Forest" 
"Extra Trees" 
"Ada Boost",
"Gradient Boosting"
"Linear Regression",
"XGBoost"
The best-performing model is selected based on evaluation metrics like RMSE, MAE, and R².

![algo](https://github.com/sundaram25018/Car_Price_Prediction/assets/122205914/cee238a7-647d-4fcb-962e-ff8454922139)


Conclusion
Conclusion¶ The tree-based ensemble methods (Random Forest, Extra Trees, and XGBoost) show the best performance in terms of both MSE and 𝑅2 . They effectively capture the variance in the target variable and provide accurate predictions.

Extra Trees and Random Forest have the best performance metrics overall, with Extra Trees slightly outperforming Random Forest.

Gradient Boosting also performs well, though slightly behind Extra Trees and Random Forest.

XGBoost performs similarly to Gradient Boosting, slightly better in some cases. AdaBoost and Linear Regression perform significantly worse than the other models, with higher MSE and lower 𝑅2 scores.
