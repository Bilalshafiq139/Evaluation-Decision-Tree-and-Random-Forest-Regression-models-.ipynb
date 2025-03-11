# Evaluation-Decision-Tree-and-Random-Forest-Regression-models-.ipynb
Model Comparison: Decision Tree vs. Random Forest Regression



# Model Comparison: Decision Tree vs. Random Forest Regression

## Overview
This repository contains a Python script that compares the performance of **Decision Tree Regression** and **Random Forest Regression** in predicting **students' GPA (Grade Point Average)** based on various academic and extracurricular factors.

---

## **Problem Statement**
Educational institutions and researchers need accurate models to predict student performance. This project aims to compare **Decision Tree Regression** and **Random Forest Regression** to determine which model provides better accuracy and generalization for predicting GPA.

### **Dataset Description**
The dataset used in this project is from [**Kaggle: Students Performance Dataset**](https://www.kaggle.com/datasets/rabieelkharoua/students-performance-dataset) and includes features such as:
- **Demographic Details** (Age, Gender, Ethnicity, Parental Education)
- **Study Habits** (Weekly Study Time, Absences, Tutoring)
- **Parental Involvement** (Support Level)
- **Extracurricular Activities** (Sports, Music, Volunteering)
- **Academic Performance** (GPA and Grade Classification)

---

## **How the Script Works**
1. **Data Preparation**:
   - Loads the dataset and removes irrelevant columns (e.g., `StudentID`).
   - Handles missing values using mean imputation.
   - Scales continuous features (e.g., `StudyTimeWeekly`, `Absences`).
2. **Model Training**:
   - Trains a **Decision Tree Regressor** and a **Random Forest Regressor** using an 80-20 train-test split.
3. **Model Evaluation**:
   - Evaluates both models using:
     - **Mean Squared Error (MSE)**
     - **R-squared Score (R²)**
     - **Mean Absolute Error (MAE)**
4. **Visualization**:
   - **Predicted vs. Actual GPA** for both models.
   - **Feature Importance** analysis for the Random Forest model.
5. **Report Writing**:
   - Summarizes the performance of both models and identifies the best-performing approach.

---

## **Dependencies**
Ensure you have the following Python libraries installed:
```sh
pip install numpy pandas matplotlib scikit-learn
```

---

## **How to Run the Script**
1. Clone the repository:
   ```sh
   git clone <repository_url>
   ```
2. Navigate to the project folder:
   ```sh
   cd <project_folder>
   ```
3. Run the Python script:
   ```sh
   python evaluation_&_selection_(compare_the_performance_of_decision_tree_and_random_forest_regression_models).py
   ```
4. Follow the output to view model comparison results.

---

## **Contributing**
Contributions are welcome! Feel free to fork this repository and submit a pull request with improvements or additional features.


