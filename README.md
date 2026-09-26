# 🏠 Property Price Estimator using Machine Learning

## 📌 Project Overview

This project presents a Machine Learning-based Property Price Estimation System developed using Python and Scikit-Learn. The primary objective of this project is to predict residential property prices based on various property characteristics such as area, number of bedrooms, bathrooms, house age, garage availability, garden area, distance from the city center, and location.

The project demonstrates the complete machine learning workflow, including data preprocessing, feature engineering, model training, evaluation, and interpretation of results.

---

## 🎯 Project Objectives

- Predict property prices using Machine Learning techniques.
- Analyze the influence of different property features on house prices.
- Apply data preprocessing and feature engineering methods.
- Evaluate model performance using regression metrics.
- Develop practical skills in supervised machine learning.

---

## 📊 Dataset Description

The dataset contains information about residential properties and their corresponding prices.

### Features Used

| Feature | Description |
|----------|-------------|
| Area_sqft | Property area in square feet |
| Bedrooms | Number of bedrooms |
| Bathrooms | Number of bathrooms |
| HouseAge_years | Age of the property |
| Garage | Garage availability |
| GardenArea_sqft | Garden area in square feet |
| DistanceToCity_km | Distance from city center |
| Location | Property location |
| Price_Lakh | Target variable (House Price) |

---

## 🛠 Data Preprocessing

Several preprocessing techniques were applied before training the machine learning model:

- Removal of unnecessary columns (HouseID)
- Dataset inspection and validation
- Feature selection
- One-Hot Encoding of categorical variables
- Creation of numerical feature matrix
- Train-Test Split (80:20 ratio)

---

## 🔄 Machine Learning Workflow

### Step 1: Data Collection
Property dataset loaded into Google Colab using Pandas.

### Step 2: Data Cleaning
Checked dataset quality and removed unnecessary information.

### Step 3: Feature Engineering
Prepared relevant features for model training.

### Step 4: Encoding Categorical Variables
Applied One-Hot Encoding to the Location feature.

### Step 5: Train-Test Split
Separated the dataset into training and testing subsets.

### Step 6: Model Training
Trained a Linear Regression model using Scikit-Learn.

### Step 7: Prediction
Generated property price predictions using the trained model.

### Step 8: Model Evaluation
Evaluated model performance using regression metrics.

### Step 9: Feature Importance Analysis
Analyzed the impact of each feature on property prices.

---

## 🤖 Machine Learning Model

### Algorithm Used

**Linear Regression**

Linear Regression was selected because it is one of the most widely used supervised machine learning algorithms for predicting continuous numerical values.

---

## 📈 Model Performance

The trained model achieved the following performance metrics:

| Metric | Value |
|----------|----------|
| R² Score | 0.93 |
| Mean Absolute Error (MAE) | 24.25 |
| Root Mean Squared Error (RMSE) | 31.72 |

### Performance Interpretation

- The model explains approximately **93%** of the variance in house prices.
- The low MAE indicates that prediction errors are relatively small.
- The RMSE value demonstrates strong predictive capability.
- Overall, the model shows excellent performance for property price estimation.

---

## 🔍 Feature Importance Analysis

The most influential features affecting property prices are:

| Rank | Feature |
|--------|----------|
| 1 | Location (Dhaka) |
| 2 | Garage Availability |
| 3 | Bedrooms |
| 4 | Bathrooms |
| 5 | Property Area |

### Insights

- Properties located in Dhaka tend to have higher prices.
- Garage availability significantly increases property value.
- Houses with more bedrooms and bathrooms generally have higher prices.
- Property size contributes positively to house price.

---

## 🧠 Machine Learning Concepts Applied

This project demonstrates the practical application of:

- Data Preprocessing
- Feature Engineering
- One-Hot Encoding
- Train-Test Split
- Linear Regression
- Model Evaluation
- Feature Importance Analysis
- Predictive Analytics

---

## 📂 Project Structure

```text
Property_Price_Estimator/
│
├── Property_Price_Estimator.ipynb
├── README.md
├── Dataset.csv
└── requirements.txt
```

---

## ⚙️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn
- GitHub

---

## 🚀 Installation

Install the required libraries:

```bash
pip install pandas numpy matplotlib scikit-learn
```

---

## ▶️ How to Run

1. Open Google Colab.
2. Upload the notebook file.
3. Upload the dataset.
4. Run all notebook cells.
5. View predictions and evaluation metrics.

---

## 📸 Project Output

### Model Evaluation Results

```text
R² Score = 0.93
MAE = 24.25
RMSE = 31.72
```

### Top Influential Features

```text
Location_Dhaka
Garage
Bedrooms
Bathrooms
Area_sqft
```

---

## 💡 Real-World Applications

This project can be applied in:

- Real Estate Price Prediction
- Property Valuation Systems
- Housing Market Analysis
- Real Estate Investment Planning
- Property Recommendation Systems

---

## 🏆 Skills Demonstrated

✔ Data Cleaning

✔ Data Preprocessing

✔ Feature Engineering

✔ Data Analysis

✔ Machine Learning

✔ Linear Regression

✔ Model Evaluation

✔ Predictive Analytics

✔ Python Programming

✔ Data Visualization

✔ GitHub Project Management

---

## 📚 References

- Scikit-Learn Documentation
- Pandas Documentation
- NumPy Documentation
- Matplotlib Documentation
- Google Colab Documentation

---

## 🎓 Academic Information

**Student Name:** Snigdha Akter Asha

**Program:** PGD in Data Science and Machine Learning

**Project Title:** Property Price Estimator using Machine Learning

**Institution:** Daffodil International Professional Training Institute

---

## 📜 Conclusion

This project successfully demonstrates the implementation of a Machine Learning-based Property Price Estimation System using Linear Regression. Through effective data preprocessing, feature engineering, and model evaluation, the model achieved an R² score of approximately 93%, indicating strong predictive performance.

The analysis revealed that location, garage availability, bedrooms, and bathrooms are among the most significant factors influencing property prices. The project highlights how machine learning techniques can be applied to real-world real estate problems and support data-driven decision-making.

---

### ⭐ Thank you for visiting this project repository.
