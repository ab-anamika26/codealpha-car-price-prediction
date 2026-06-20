# codealpha-car-price-prediction

# 🚗 Car Price Prediction using Machine Learning

## 📖 Overview

Car Price Prediction is a Machine Learning project that estimates the selling price of a used car based on its specifications and historical data. The project demonstrates an end-to-end machine learning workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and prediction.

The objective is to build a regression model capable of predicting a car's selling price using features such as manufacturing year, present price, kilometers driven, fuel type, transmission type, and ownership details.

---

## 🎯 Objectives

* Analyze and understand the used car dataset.
* Perform data cleaning and preprocessing.
* Visualize relationships between different features.
* Build a Machine Learning regression model.
* Evaluate model performance using standard regression metrics.
* Predict the selling price of a used car based on user-provided features.

---

## 📊 Dataset Information

The dataset contains information about used cars and their selling prices.

### Features

| Feature       | Description                                |
| ------------- | ------------------------------------------ |
| Car_Name      | Name of the car                            |
| Year          | Manufacturing year                         |
| Selling_Price | Selling price of the car (Target Variable) |
| Present_Price | Current showroom price                     |
| Driven_kms    | Total distance driven (in kilometers)      |
| Fuel_Type     | Fuel type of the vehicle                   |
| Selling_type  | Dealer or Individual seller                |
| Transmission  | Manual or Automatic transmission           |
| Owner         | Number of previous owners                  |

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Joblib
* Google Colab / Jupyter Notebook

---

## 📈 Exploratory Data Analysis

The following visualizations were created to understand the dataset:

* Selling Price Distribution
* Manufacturing Year vs Selling Price
* Present Price vs Selling Price
* Driven Kilometers vs Selling Price
* Fuel Type vs Selling Price
* Transmission vs Selling Price
* Correlation Heatmap
* Actual vs Predicted Selling Price

---

## ⚙️ Machine Learning Workflow

1. Data Collection
2. Data Loading
3. Data Exploration
4. Data Cleaning
5. Exploratory Data Analysis (EDA)
6. Feature Engineering
7. Label Encoding
8. Feature Selection
9. Train-Test Split
10. Model Training using Linear Regression
11. Model Prediction
12. Performance Evaluation
13. Model Saving
14. Future Price Prediction

---

## 🤖 Machine Learning Model

**Algorithm Used:** Linear Regression

Linear Regression was selected because the target variable (**Selling Price**) is continuous. The model learns the relationship between the input features and the selling price to make accurate predictions for unseen data.

---

## 📊 Model Evaluation

The model performance was evaluated using the following regression metrics:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

These metrics help measure prediction accuracy and overall model performance.

---

## 📂 Project Structure

```text
Car Price Prediction/
│
├── Car_Price_Prediction.ipynb
├── car_data.csv
├── cleaned_car_data.csv
├── car_price_prediction_model.pkl
├── price_distribution.png
├── year_vs_price.png
├── present_price_vs_selling_price.png
├── driven_kms_vs_price.png
├── fuel_type_vs_price.png
├── transmission_vs_price.png
├── correlation_heatmap.png
├── actual_vs_predicted.png
├── README.md
└── requirements.txt
```

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/car-price-prediction.git
```

Navigate to the project directory:

```bash
cd car-price-prediction
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

Run the Jupyter Notebook or Google Colab notebook.

---

## 📌 Results

* Successfully cleaned and preprocessed the dataset.
* Performed comprehensive exploratory data analysis.
* Built a Linear Regression model for price prediction.
* Achieved reliable prediction performance using regression evaluation metrics.
* Generated predictions for unseen car data.

---

## 🔮 Future Enhancements

* Implement advanced regression algorithms such as Random Forest, XGBoost, and Gradient Boosting.
* Perform hyperparameter tuning to improve model accuracy.
* Develop an interactive web application using Flask or Streamlit.
* Deploy the trained model on a cloud platform for real-time predictions.

---

## 📚 Learning Outcomes

This project provided practical experience in:

* Data Cleaning and Preprocessing
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Label Encoding
* Regression Modeling
* Model Evaluation
* Model Serialization using Joblib
* End-to-End Machine Learning Workflow

---

## 👩‍💻 Author

**Anamika A B**

B.Tech Graduate | Machine Learning & Data Science Enthusiast

GitHub: https://github.com/ab-anamika26

LinkedIn: https://www.linkedin.com/in/anamikaab/

---

## 📄 License

This project was developed for educational purposes as part of the **CodeAlpha Machine Learning Internship**.
