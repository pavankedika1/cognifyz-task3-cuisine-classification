# 🍽️ Cuisine Classification Using Machine Learning
## 📌 Project Overview
This project focuses on classifying restaurants based on their cuisine type using Machine Learning techniques.
The model analyzes restaurant features and predicts the primary cuisine category of a restaurant.

The project demonstrates the complete machine learning workflow, including data preprocessing, model training, evaluation, and performance analysis.
---
## 🎯 Objective
Develop a Machine Learning model to classify restaurants into different cuisine categories based on restaurant attributes and characteristics.
---
## 📂 Dataset
The dataset contains information about restaurants, including:
* Restaurant Name
* Country Code
* City
* Locality
* Cuisines
* Average Cost for Two
* Currency
* Has Table Booking
* Has Online Delivery
* Price Range
* Votes
* Aggregate Rating
### Target Variable
**Cuisines**
For classification purposes, only the primary cuisine was considered when a restaurant offered multiple cuisines.
---
## 🛠️ Project Workflow
### 1. Data Preprocessing
* Loaded the dataset using Pandas.
* Removed records with missing cuisine values.
* Handled missing values in feature columns.
* Encoded categorical variables using One-Hot Encoding.
* Converted cuisine labels into numerical format using Label Encoding.

### 2. Train-Test Split
* Split the dataset into:
  * 80% Training Data
  * 20% Testing Data
    
### 3. Model Training
* Selected **Random Forest Classifier** as the classification algorithm.
* Trained the model on the training dataset.

### 4. Model Evaluation
The model was evaluated using:
* Accuracy
* Precision
* Recall
* Classification Report

### 5. Performance Analysis
The model's performance was analyzed across different cuisine categories.
Challenges identified include:
* Class imbalance among cuisine categories.
* Limited samples for rare cuisines.
* Multi-cuisine restaurants creating classification ambiguity.
* Similar restaurant features across different cuisines.
---

## 🤖 Machine Learning Algorithm
### Random Forest Classifier
Random Forest is an ensemble learning algorithm that builds multiple decision trees and combines their predictions to 
improve classification performance and reduce overfitting.
---

## 💻 Technologies Used
* Python
* Pandas
* Scikit-Learn
* NumPy
---

## 📊 Evaluation Metrics
* Accuracy Score
* Precision Score
* Recall Score
* Classification Report
---

## 📈 Results
The Random Forest Classifier successfully classified restaurants into cuisine categories.

### Key Findings
* Common cuisines achieved higher prediction accuracy.
* Rare cuisines showed lower classification performance.
* Class imbalance affected overall prediction quality.
* The model performed best on cuisine categories with larger training samples.
---

## 🚀 How to Run
### Install Required Libraries
```bash
pip install pandas numpy scikit-learn
```

### Run the Project
```bash
python Task-3.py
```
---
## 🎓 Learning Outcomes
Through this project, I gained practical experience in:
* Data Preprocessing
* Feature Engineering
* Classification Algorithms
* Random Forest Classification
* Model Evaluation
* Performance Analysis
* Bias and Challenge Identification
---

## 📁 Project Structure
```text
cognifyz-task3-cuisine-classification/
│
├── Dataset.csv
├── Task-3.py
├── README.md

```
---
## 👨‍💻 Author
**Pavan Kedika**
Machine Learning Internship Project
Cognifyz Technologies
