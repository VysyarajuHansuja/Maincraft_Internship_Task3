# AI/ML Internship – Task 3
## Model Validation, Overfitting Control & Hyperparameter Tuning

This project is part of the **Artificial Intelligence & Machine Learning Internship**. The objective is to improve machine learning model reliability by validating model performance, detecting overfitting, applying cross-validation, tuning hyperparameters, and selecting the best-performing regression model for California Housing Price Prediction.

---

## Project Objective

The goal of this project is to:

- Detect overfitting in machine learning models.
- Perform model validation using **5-Fold Cross-Validation**.
- Optimize model performance using **GridSearchCV**.
- Compare regression models using **RMSE** and **R² Score**.
- Select the best model based on accuracy and generalization ability.
- Save the trained model for future deployment.

---

## Dataset

**Dataset:** California Housing Dataset (Scikit-learn)

- Total Samples: **20,640**
- Input Features: **8**
- Target Variable: **HousePrice (Median House Value)**

### Features

- MedInc
- HouseAge
- AveRooms
- AveBedrms
- Population
- AveOccup
- Latitude
- Longitude

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Joblib
- Jupyter Notebook

---

## Project Workflow

1. Import required libraries
2. Load the California Housing Dataset
3. Explore and preprocess the dataset
4. Apply StandardScaler
5. Split data into training and testing sets
6. Train baseline regression models
7. Detect overfitting
8. Perform 5-Fold Cross-Validation
9. Tune hyperparameters using GridSearchCV
10. Evaluate the optimized model
11. Compare model performance
12. Visualize results
13. Save the trained model using Joblib

---

## Models Implemented

- Linear Regression
- Ridge Regression
- Decision Tree Regressor
- Tuned Decision Tree Regressor (GridSearchCV)

---

## Evaluation Metrics

The models were evaluated using:

- Root Mean Squared Error (RMSE)
- R² Score
- 5-Fold Cross-Validation RMSE

---

## Hyperparameter Tuning

The Decision Tree model was optimized using **GridSearchCV** with parameters such as:

- `max_depth`
- `min_samples_split`
- `min_samples_leaf`

The best parameter combination was selected based on cross-validation performance.

---

## Results

The optimized Decision Tree model demonstrated better generalization after hyperparameter tuning and achieved improved performance compared to the baseline models.

---

## Future Improvements

- Evaluate ensemble models such as Random Forest and XGBoost.
- Perform RandomizedSearchCV for faster hyperparameter optimization.
- Apply advanced feature engineering techniques.
- Deploy the trained model using Streamlit or Flask.
- Build an end-to-end machine learning pipeline.

---

## Key Learnings

- Understanding overfitting and underfitting.
- Importance of model validation.
- Practical implementation of Cross-Validation.
- Hyperparameter tuning using GridSearchCV.
- Model evaluation using RMSE and R² Score.
- Saving trained models with Joblib for deployment.

---

## Author

**Vysyaraju Hansuja**

B.Tech – Computer Science & Engineering  
Veer Surendra Sai University of Technology (VSSUT), Burla

GitHub: https://github.com/VysyarajuHansuja
LinkedIn: www.linkedin.com/in/vysyaraju-hansuja-720518323

---

## Internship

**Artificial Intelligence & Machine Learning Internship**

**Task 3 – Model Validation, Overfitting Control & Hyperparameter Tuning**
