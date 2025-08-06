# 🍽️ Restaurant ML Internship Project – Cognifyz Technologies

This repository contains hands-on machine learning and data analysis tasks completed as part of my **Machine Learning Internship at Cognifyz Technologies** (Aug 2025). The project involves building intelligent systems using real-world restaurant data for classification, recommendation, prediction, and visualization.

---

## 📂 Project Tasks

### 🔢 Task 3 – Cuisine Classification
**Objective**: Classify the type of cuisine a restaurant serves (e.g., North Indian, Chinese, Fast Food) using structured features.

#### 📊 Workflow:
- Cleaned the restaurant dataset and handled missing values
- Extracted the primary cuisine from multiple-cuisine entries
- Encoded categorical features such as city, currency, etc.
- Applied **Random Forest Classifier** to predict cuisine
- Used **SMOTE** to address class imbalance
- Evaluated using accuracy, precision, recall, F1-score, and confusion matrix

#### ✅ Results:
- Achieved ~52% model accuracy
- Performed best on "North Indian" cuisine
- Key challenges: class imbalance, multiple labels in cuisine field

---

### 🗺️ Task 4 – Geospatial Restaurant Visualization
**Objective**: Visualize restaurant locations and rating patterns on a real-world map.

#### 📊 Workflow:
- Used `Folium` and `Plotly` to create interactive map-based visualizations
- Plotted restaurant locations using latitude and longitude
- Color-coded markers based on **aggregate rating**
- Enabled interactive zooming, popups with restaurant details, and clustering

#### ✅ Results:
- Created a clean, zoomable map interface to explore restaurant distribution
- Useful for identifying top-rated restaurant clusters in cities like **New Delhi**
- Enhanced understanding of geographic trends in restaurant quality

---

## 🛠️ Tools & Technologies
- **Languages & Libraries**: Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Plotly, Folium, Imbalanced-learn (SMOTE)
- **ML Models**: Random Forest (Classification), Feature Engineering
- **Visualization**: Interactive map (Folium), Data plots (Seaborn/Matplotlib)

---

## 📁 Project Files
- [`Restaurant_cognifyz.ipynb`](./Restaurant_cognifyz.ipynb): Main implementation notebook
- [`Dataset.csv`](./Dataset.csv): Cleaned and preprocessed dataset
- Interactive map HTML (generated from Folium – optionally shared as `.html`)

---

## 💡 Key Learnings
- Built classification models with real-world noisy and imbalanced data
- Learned spatial visualization techniques for location-based insights
- Gained experience in handling categorical variables and encoding
- Applied practical evaluation metrics and confusion matrix analysis

---

## 🎓 Internship Details
- **Company**: Cognifyz Technologies  
- **Role**: Machine Learning Intern  
- **Duration**: August 2025  
- **Focus**: Real-world application of machine learning, classification, and geospatial visualization

---

📌 Tags: `#CognifyzTechnologies #MachineLearning #Python #Classification #SMOTE #Folium #DataVisualization #MLInternship #GitHubProjects`
