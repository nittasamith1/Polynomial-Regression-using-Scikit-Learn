# Polynomial Regression using Scikit-Learn

## 📌 Project Overview

This project demonstrates the implementation of **Polynomial Regression** using Python and Scikit-Learn.

Polynomial Regression is used when the relationship between the independent variable and dependent variable is **non-linear**. Unlike Linear Regression, Polynomial Regression fits a curved line to the data.

This project includes:
- Dataset generation
- Data visualization
- Polynomial feature transformation
- Train-test split
- Model training
- Prediction
- Accuracy evaluation
- Graph plotting

---

# 📖 What is Polynomial Regression?

Polynomial Regression is a type of regression analysis where the relationship between variables is modeled as an nth-degree polynomial.

Polynomial Regression equation:

```math
y = b_0 + b_1x + b_2x^2 + ... + b_nx^n
```

Example for degree 2:

```math
y = b_0 + b_1x + b_2x^2
```

It is useful when data follows a curved trend instead of a straight line.

---

# 🚀 Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-Learn

---

# 📂 Libraries Required

Install required libraries using:

```bash
pip install numpy pandas matplotlib scikit-learn
```

---

# 📊 Dataset Information

The dataset is generated manually using a quadratic equation with random noise.

Equation used:

```math
Y = 0.5X^2 + 3X + 10
```

Random noise is added to make the dataset more realistic.

---

# ⚙️ Project Workflow

## Step 1: Import Libraries
Import all required Python libraries.

## Step 2: Create Dataset
Generate non-linear data using NumPy.

## Step 3: Visualize Dataset
Plot the original dataset using Matplotlib.

## Step 4: Polynomial Feature Transformation
Convert normal features into polynomial features using:

```python
PolynomialFeatures(degree=2)
```

## Step 5: Train-Test Split
Split the dataset into training and testing sets.

## Step 6: Train Model
Train the Polynomial Regression model using Linear Regression.

## Step 7: Predictions
Predict values for test data.

## Step 8: Evaluation
Evaluate the model using:
- MAE
- MSE
- RMSE
- R² Score

## Step 9: Visualization
Plot the polynomial regression curve.

## Step 10: Predict New Values
Predict output for new input values.

---

# 📈 Evaluation Metrics

## MAE (Mean Absolute Error)

Measures average absolute errors.

```math
MAE = \frac{1}{n}\sum |y - \hat{y}|
```

---

## MSE (Mean Squared Error)

Measures average squared errors.

```math
MSE = \frac{1}{n}\sum (y - \hat{y})^2
```

---

## RMSE (Root Mean Squared Error)

Square root of MSE.

```math
RMSE = \sqrt{MSE}
```

---

## R² Score

Measures model accuracy.

```math
R^2 = 1 - \frac{\sum(y-\hat{y})^2}{\sum(y-\bar{y})^2}
```

---

# 📌 Train and Test Accuracy

- **Training Accuracy** measures how well the model fits training data.
- **Testing Accuracy** measures how well the model performs on unseen data.

Good Model:
- High train accuracy
- High test accuracy
- Small difference between both

---

# 📉 Output Graph

The graph shows:
- Blue dots → Original data points
- Red curve → Polynomial Regression fitted curve

---

# 📷 Example Output

```python
Training Accuracy : 0.98
Testing Accuracy  : 0.96
```

---

# 📁 Project Structure

```bash
PolynomialRegression/
│
├── PolynomialRegression.ipynb
└── README.md
```

---

# ▶️ How to Run

1. Clone the repository

```bash
git clone <repository-link>
```

2. Open project folder

```bash
cd PolynomialRegression
```

3. Install dependencies

```bash
pip install -r requirements.txt
```

4. Run Jupyter Notebook

```bash
jupyter notebook
```

---

# 🔥 Applications of Polynomial Regression

- Salary Prediction
- Stock Market Trend Analysis
- Population Growth Prediction
- Weather Forecasting
- Sales Forecasting
- Machine Learning Curve Fitting

---

# 🎯 Advantages

- Models non-linear relationships
- Better fitting for curved data
- Easy to implement
- Improves prediction accuracy

---

# ⚠️ Disadvantages

- Can overfit with high-degree polynomials
- Computationally expensive for large datasets
- Sensitive to outliers

---

# 📚 Conclusion

This project successfully demonstrates the implementation of Polynomial Regression using Scikit-Learn.

The model effectively learns non-linear relationships and provides accurate predictions using polynomial feature transformation.

Polynomial Regression is a powerful technique when linear models fail to fit curved data patterns.

---

Developed using Python and Scikit-Learn for Machine Learning practice and academic learning.

---
