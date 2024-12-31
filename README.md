# Titanic Survival Prediction  

This repository contains a comprehensive project for predicting survival outcomes on the Titanic dataset using machine learning techniques. The primary goal is to classify passengers as survivors or non-survivors based on their characteristics such as age, gender, class, and more.  

## Models Implemented  
We have trained and evaluated the following machine learning models to compare their performance:  

1. **K-Nearest Neighbors (KNN)**  
   - A simple and intuitive algorithm that predicts survival based on the majority vote of nearest neighbors.  
   
2. **Support Vector Machine (SVM)**  
   - A powerful classification model that finds the optimal hyperplane to separate survivors from non-survivors.  

3. **Random Forest**  
   - An ensemble learning method using multiple decision trees to enhance prediction accuracy and reduce overfitting.  

## Features of the Project  
- **Data Preprocessing**: Handling missing data, feature engineering, and normalization for optimal model performance.  
- **Exploratory Data Analysis (EDA)**: Visualizations and statistical analysis to understand the dataset.  
- **Model Training & Evaluation**: Training the models and evaluating them using metrics like accuracy, precision, recall, and F1-score.  
- **Comparison of Models**: A detailed comparison of the models’ performances to identify the best approach for this dataset.  

## Dataset  
The Titanic dataset is sourced from [Kaggle](https://www.kaggle.com/c/titanic), a widely used benchmark dataset for binary classification problems.  

## Repository Structure  
- `data/`: Contains the Titanic dataset.  
- `notebooks/`: Jupyter notebooks for data preprocessing, model training, and evaluation.  
- `src/`: Python scripts for modular and reusable code.  
- `results/`: Model performance metrics and visualizations.  
- `README.md`: Detailed project description and instructions for use.  

## How to Run  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/your-username/titanic-survival-prediction.git  
   cd titanic-survival-prediction  
