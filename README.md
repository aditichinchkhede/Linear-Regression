# Linear Regression: Education vs Salary

## 📌 Project Overview

This project demonstrates a simple **Linear Regression** model to
predict salary based on years of education.

The project uses a small sample dataset where: - **Independent variable
(X):** Education - **Dependent variable (Y):** Salary

The model is built using **Ordinary Least Squares (OLS)** with
`statsmodels`, and its predictions are evaluated using **Mean Squared
Error (MSE)** and **Mean Absolute Error (MAE)**.

## 📊 Dataset

The project uses the following sample data:

    Education   Salary
  ----------- --------
            1      200
            2      300
            3      400
            4      500
            5      600

Here, salary increases linearly with education.

## 🧠 Methodology

The project follows these steps:

1.  Import the required Python libraries.
2.  Create the independent (`edu`) and dependent (`salary`) variables.
3.  Visualize the relationship between education and salary using a
    scatter plot.
4.  Add a constant to the independent variable for the OLS model.
5.  Train a Linear Regression model using `statsmodels`.
6.  Generate salary predictions.
7.  Plot the regression line against the original data.
8.  Evaluate the model using MSE and MAE.

## 🛠️ Technologies & Libraries

-   Python
-   NumPy
-   Matplotlib
-   Seaborn
-   Statsmodels
-   Scikit-learn

## 📈 Model

The regression relationship in this example is:

**Salary = 100 + 100 × Education**

For example, with an education value of `4.5`, the model gives a
predicted salary of `550`.

The project also demonstrates prediction using the trained OLS model.

## 📏 Model Evaluation

Two regression evaluation metrics are used:

### Mean Squared Error (MSE)

MSE measures the average squared difference between actual and predicted
values.

### Mean Absolute Error (MAE)

MAE measures the average absolute difference between actual and
predicted values.

Because the sample data follows an exact linear relationship, the
prediction error is effectively zero.

## 📉 Visualization

The project creates: - A scatter plot showing the relationship between
education and salary. - A regression line showing the fitted linear
relationship.

## ▶️ How to Run

### 1. Clone the repository

``` bash
git clone <your-repository-url>
cd <your-repository-name>
```

### 2. Install dependencies

``` bash
pip install numpy matplotlib seaborn statsmodels scikit-learn
```

### 3. Run the Python file

``` bash
python "23_july.py"
```

## 📁 Project Structure

``` text
.
├── 23_july.py
└── README.md
```

## 🎯 Learning Objectives

This project helps demonstrate the fundamentals of:

-   Independent and dependent variables
-   Linear regression
-   Ordinary Least Squares (OLS)
-   Regression line visualization
-   Making predictions with a trained model
-   Mean Squared Error
-   Mean Absolute Error

## 👤 Author

**Aditi**

------------------------------------------------------------------------

⭐ If you found this project useful, feel free to star the repository!
