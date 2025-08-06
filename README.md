# 🍽️ Restaurant ML Project – Cognifyz Technologies Internship

This repository showcases the hands-on machine learning and data analysis work I completed during my **Machine Learning Internship at Cognifyz Technologies** (Aug 2025). The project involves solving real-world business problems in the restaurant domain using regression, classification, recommendation systems, and spatial visualization.

---

## 📌 Tasks Overview

### ✅ Task 1 – Restaurant Rating Prediction
**Objective**: Predict the **aggregate rating** of a restaurant based on various input features.

#### 🔧 Workflow:
- Preprocessed data by handling null values, encoding categorical variables, and dropping irrelevant columns
- Selected and trained regression models: **Linear Regression** and **Random Forest Regressor**
- Evaluated model performance using metrics like **R² score**, **Mean Squared Error (MSE)**, and **Mean Absolute Error (MAE)**

#### 🎯 Results:
- Best model: **Random Forest Regressor**
- Accuracy (R²): ~78%
- Identified key factors influencing restaurant ratings: **price range**, **votes**, **online delivery availability**

---

### ✅ Task 2 – Restaurant Recommendation System
**Objective**: Build a content-based recommendation system to suggest restaurants based on user preferences.

#### 🔧 Workflow:
- Cleaned and encoded key categorical variables like `Cuisines`, `City`, and `Price Range`
- Defined a custom recommendation function using cosine similarity on user-defined preferences (e.g., cuisine type, rating, price)
- Suggested top 5 matching restaurants for given sample input

#### 🎯 Results:
- Accurate and context-aware recommendations based on cuisine similarity and rating
- Enabled filtering by **city**, **budget**, and **preferred cuisines**

---

### ✅ Task 3 – Cuisine Classification
**Objective**: Build a machine learning model to classify restaurants based on their cuisine type.

#### 🔧 Workflow:
- Extracted primary cuisine labels from multi-cuisine fields
- Encoded categorical features (city, delivery options, etc.)
- Trained a **Random Forest Classifier**
- Used **SMOTE** to handle class imbalance

#### 📊 Evaluation:
- Accuracy: ~52%
- Most accurate for: **North Indian**
- Metrics: Precision, Recall, F1-Score, Confusion Matrix
- Challenges: multi-label data and class imbalance

---

### ✅ Task 4 – Geospatial Visualization
**Objective**: Visualize the geographical distribution of restaurants and their ratings using interactive maps.

#### 🔧 Workflow:
- Used **Folium** to map restaurants based on latitude and longitude
- Color-coded markers by **Aggregate Rating**
- Integrated popups to show restaurant names and ratings
- Generated an interactive HTML map for exploration

#### 🗺️ Results:
- Visualized clusters of high-rated restaurants in New Delhi
- Helped identify geographic trends and business potential zones

---

## 🛠️ Tools & Technologies
- **Languages & Libraries**: Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Plotly, Folium
- **ML Techniques**: Regression, Classification, SMOTE, Content-based Filtering
- **Evaluation Metrics**: R² Score, MSE, MAE, Accuracy, Precision, Recall, F1-Score
- **Visualization**: Folium (Map), Seaborn & Matplotlib (EDA, Evaluation)

---

## 📁 Project Files
- `Restaurant_cognifyz.ipynb` – Main implementation file
- `Dataset.csv` – Restaurant dataset
- `rating_map.html` – Interactive map (generated via Folium)

---

## 📚 Key Learnings
- Applied real-world machine learning workflows: preprocessing → modeling → evaluation → deployment
- Solved classification, regression, and recommendation problems
- Gained hands-on experience with SMOTE, Label Encoding, Cosine Similarity, and Geospatial Mapping

---

## 🏢 Internship Info
**Company**: Cognifyz Technologies  
**Role**: Machine Learning Intern  
**Duration**: August 2025  
**Domain**: Restaurant Industry Data – AI/ML Use Cases

---


🎯 **Feel free to explore the code, test the models, and clone the repo for learning purposes!**
