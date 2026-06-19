# Ice-Cream-Sales-Prediction-Using-Linear-Regression

Predicting ice cream sales profits based on temperature using Simple Linear Regression. This project demonstrates how machine learning can be used to understand the relationship between temperature and ice cream sales and predict future sales based on temperature values.

---

## Project Overview

This project uses **Simple Linear Regression** to analyze the relationship between temperature and ice cream sales profits. The model learns patterns from historical data and predicts expected sales profit for new temperature values.

The project covers:

- Data Loading
- Data Exploration
- Correlation Analysis
- Data Visualization
- Model Training
- Model Evaluation
- Prediction

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn

---

## Workflow

### 1. Data Loading
- Imported the dataset using Pandas.
- Checked the dataset structure and data types.

### 2. Data Exploration
- Analyzed dataset information.
- Checked for missing values.
- Studied feature distributions.

### 3. Correlation Analysis
- Examined the relationship between temperature and ice cream sales profit.
- Identified a strong positive correlation.

### 4. Data Visualization
- Created scatter plots to visualize the relationship between temperature and sales.
- Observed a clear upward trend indicating a linear relationship.

### 5. Train-Test Split
- Split the dataset into training and testing datasets.
- Used the training dataset for model learning and testing dataset for performance evaluation.

### 6. Model Training
- Applied Simple Linear Regression using Scikit-Learn.
- Trained the model on the training dataset.

### 7. Model Evaluation
The model performance was evaluated using the **R² Score (Coefficient of Determination)**.

| Metric | Score |
|----------|----------|
| Training R² Score | `<TRAIN_R2_SCORE>` |
| Testing R² Score | `<TEST_R2_SCORE>` |

**Interpretation:**
- An R² score close to 1 indicates excellent model performance.
- A small difference between training and testing R² scores suggests that the model generalizes well and is neither overfitting nor underfitting.
- The model successfully captures the relationship between temperature and ice cream sales profit.

### 8. Prediction
- Used the trained model to predict ice cream sales profit for new temperature values.
- Compared actual values with predicted values.

---

## Results

The model successfully identifies a positive linear relationship between temperature and ice cream sales profit.

### Key Findings

- Higher temperatures generally lead to increased ice cream sales.
- The scatter plot confirms a strong positive linear trend.
- The regression line effectively fits the data.
- The training and testing R² scores indicate good predictive performance.
- The small difference between train and test scores shows that the model generalizes well to unseen data.

---

## Conclusion

This project demonstrates the application of **Simple Linear Regression** for predicting ice cream sales based on temperature. The model achieved strong performance with high R² scores on both training and testing datasets, indicating that it effectively captures the underlying relationship in the data.

Since the difference between the training and testing R² scores is minimal, the model is considered a **good fit**, showing strong generalization ability without significant overfitting or underfitting.

---

## Future Improvements

- Collect more data for improved accuracy.
- Experiment with Polynomial Regression for non-linear relationships.
- Deploy the model using Flask or Streamlit.
- Create an interactive dashboard for sales forecasting.

---
