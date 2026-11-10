🚗 **CAR PRICE PREDICTION USING MACHINE LEARNING ALGORITHM**

📌 **Project Overview**

This project aims to predict the price of a car based on its technical specifications and features using Machine Learning algorithms. Various regression models were trained and evaluated to determine the most accurate model for price prediction.

🎯 **Objectives**

Analyze factors affecting car prices.
Perform data preprocessing and feature engineering.
Train multiple regression models.
Compare model performance using evaluation metrics.
Identify the most important features influencing car prices.

📊 **Dataset**

The project uses the CarPrice Dataset, which contains information about various car attributes such as:

Car Name
Fuel Type
Aspiration
Wheelbase
Car Length
Car Width
Car Height
Curb Weight
Engine Size
Horsepower
Highway MPG
City MPG
Price

🛠 **Technologies Used**

Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Jupyter Notebook

🔍 **Data Preprocessing**

The following preprocessing steps were performed:

Handling skewness
Label Encoding
Feature Scaling
Train-Test Split
Feature Selection

🤖 **Machine Learning Models Used**

Decision Tree Regressor
Random Forest Regressor
Gradient Boosting Regressor
Support Vector Regressor (SVR)

⚙️ **Hyperparameter Tuning**

Hyperparameter tuning was performed using RandomizedSearchCV with 5-fold cross-validation to optimize model performance.

Example tuned parameters:

n_estimators
max_depth
min_samples_split
min_samples_leaf
max_features
bootstrap

📈 **Model Evaluation Metrics**

The following metrics were used:

R² Score
Mean Absolute Error (MAE)
Root Mean Squared Error (RMSE)

***Best Model Performance (Random Forest Regressor)***

Metric	Value
R² Score	95%
MAE	1304
RMSE	1840.99

⭐ **Feature Importance**

The most influential features identified by the Random Forest model are:

Feature	Importance (%)
Engine Size	55.48
Curb Weight	29.44
Highway MPG	4.63
Horsepower	3.14
Car Name	2.15

The results indicate that Engine Size and Curb Weight are the primary factors affecting car prices.

📋 **Results**
Random Forest Regressor achieved the highest predictive performance.
The model explains approximately 95% of the variability in car prices.
Hyperparameter tuning reduced prediction errors and improved model generalization.
Engine Size and Curb Weight were found to be the most significant predictors.

📌 **Conclusion**

This project successfully developed a machine learning model capable of predicting car prices with high accuracy. The Random Forest Regressor achieved the best performance with an R² score of 95%, MAE of 1304, and RMSE of 1840.99. The findings demonstrate the effectiveness of machine learning techniques in estimating vehicle prices and supporting data-driven decision-making in the automotive industry.

👩‍💻 **Author**

Hyruniza C K
