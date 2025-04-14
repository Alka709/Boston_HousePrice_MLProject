# Boston House Price Prediction

This project involves predicting the **median house prices** in Boston suburbs using various regression models. It is a beginner-friendly machine learning project that demonstrates the end-to-end process including data preprocessing, exploratory data analysis (EDA), model training, evaluation, and hyperparameter tuning.

---

### Features:
- **CRIM**: Per capita crime rate by town
- **ZN**: Proportion of residential land zoned for large lots
- **INDUS**: Non-retail business acres per town
- **CHAS**: Charles River dummy variable (1 if tract bounds river)
- **NOX**: Nitric oxides concentration
- **RM**: Average number of rooms per dwelling
- **AGE**: Proportion of owner-occupied units built before 1940
- **DIS**: Distance to employment centers
- **RAD**: Accessibility to radial highways
- **TAX**: Property tax rate
- **PTRATIO**: Pupil-teacher ratio
- **B**: Ethnic diversity index
- **LSTAT**: % lower status population

**Target Variable:**
- **MEDV**: Median value of owner-occupied homes (in $1000s)

---

## Project Workflow

1. **Data Cleaning**
   - Checked for missing and duplicate values
   - Removed outliers (especially in target column `MEDV`)
  
2. **Exploratory Data Analysis (EDA)**
   - Correlation matrix to identify important features
   - Distribution plots and scatter plots for understanding relationships

3. **Modeling**
   - Implemented:
     - Linear Regression
     - Random Forest Regressor
     - Gradient Boosting Regressor
   - Compared models using **Mean Squared Error (MSE)** and **R² Score**

4. **Hyperparameter Tuning**
   - Used `GridSearchCV` to optimize parameters for Random Forest and Gradient Boosting

5. **Model Comparison**
   - Visualized model performance using bar plots for MSE and R²

---

## 📈 Results

| Model                  | MSE         | R² Score   |
|------------------------|-------------|------------|
| Linear Regression      | ~24.29      | ~0.67      |
| Random Forest (Tuned)  | ~9.85       | ~0.86      |
| Gradient Boosting (Tuned) | ~6.18   | ~0.91      |

---

## Files in this Repo

- `Boston_House_Price_Prediction.ipynb`: Jupyter notebook with full code and explanations
- `README.md`: Project overview
- (Optional) `requirements.txt`: List of required libraries

---

## Tools & Libraries

- Python
- Jupyter Notebook
- pandas, numpy
- matplotlib, seaborn
- scikit-learn

---

## Future Improvements

- Try more advanced models like XGBoost or LightGBM
- Perform feature engineering (interaction terms, polynomial features)
- Deploy model using Flask or Streamlit

---

## Contact

Made with ❤️ by Alka Santhosh  
Feel free to reach out for suggestions or collaborations!
