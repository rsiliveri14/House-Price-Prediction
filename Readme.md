**🏠 House Price Prediction** 

This project uses a machine learning pipeline built with real-world housing data to predict house prices. The objective is to make an accurate and scalable predictive system that can assist homeowners, real estate agents, and investors in estimating property values based on multiple features such as location, size, condition, and more.

**👥 Authors**

Rohith Vardhan Siliveri ([rsiliveri@binghamton.edu](mailto:rsiliveri@binghamton.edu))

**📊 Features**

* Regression-based price prediction using multiple algorithms  
* Hyperparameter tuning with GridSearchCV for improved model accuracy  
* Evaluation metrics, including R² Score, MAE, MSE, and RMSE  
* Input-based prediction using serialized .pkl models  
* Exploratory Data Analysis (EDA) and correlation heatmap  
* Comparative analysis of five models: Linear Regression, KNN, Decision Tree, Random Forest, and XGBoost

**🛠️ Technologies Used**

* Python  
* Pandas, NumPy  
* scikit-learn  
* XGBoost  
* Matplotlib, Seaborn  
* Jupyter Notebook  
* joblib (for model saving)

**🧪 Modules**

* Data Preprocessing: Feature selection, handling missing values, encoding, and scaling  
* Model Training: Implementation and training of multiple regression models  
* Hyperparameter Tuning: GridSearchCV to find optimal parameters  
* Model Evaluation: Statistical evaluation and error analysis  
* Prediction Interface: Input feature values and output predicted house price using the trained XGBoost model