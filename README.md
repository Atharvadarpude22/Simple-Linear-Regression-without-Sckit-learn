# 📈 Simple Linear Regression – Salary Prediction Based on Experience

This project demonstrates how to build a **Simple Linear Regression model** completely **from scratch** using Python and NumPy, and then compares it with scikit-learn’s `LinearRegression`.

We use a dataset containing:

* `Years of Experience`
* `Salary`

The goal is to **predict salary based on experience** using a straight-line equation.

---

## 🧠 Mathematical Intuition Behind Linear Regression

At its core, simple linear regression tries to find the **best-fitting line** for a set of points on a 2D plane.

The equation of the line is:

$$
\hat{y} = mx + c
$$

Where:

* $\hat{y}$: Predicted salary
* $x$: Years of experience
* $m$: Slope of the line
* $c$: Intercept of the line

---

### 🎯 How Do We Find `m` and `c`?

We use the **Least Squares Method** to minimize the distance between actual points and predicted points.

$$
m = \frac{\sum (x_i - \bar{x})(y_i - \bar{y})}{\sum (x_i - \bar{x})^2}
$$

$$
c = \bar{y} - m \bar{x}
$$

Where:

* $\bar{x}$: Mean of input (experience)
* $\bar{y}$: Mean of output (salary)

This gives us the slope `m` and the intercept `c` that define the best-fit line.

---

## 🔍 What This Project Shows

1. **Custom Implementation**:

   * Linear Regression model built manually using only `numpy` and `pandas`.
   * Step-by-step calculation of slope and intercept.
   * Error measured using **Mean Error (ME)**.

2. **Library Comparison**:

   * The same problem is solved using **scikit-learn's** `LinearRegression`.
   * Performance is compared using **Mean Absolute Error (MAE)**.

3. **Data Visualization**:

   * A scatter plot of the data points.
   * The regression line overlaid to visually assess fit.

---

## 🎓 Why This Matters

Understanding how linear regression works *without* libraries is essential for:

* Building **intuition behind ML algorithms**
* Improving your **mathematical foundation**
* Debugging or customizing ML models
* Prepping for **interviews** or **exams** like GATE, ML courses, or coding assessments

---

## ✅ Concepts Covered

* Mean, variance, and error functions
* Loss minimization using least squares
* Prediction using learned parameters
* Performance evaluation (ME vs MAE)
* Visual interpretation of model accuracy

---

## 🙌 Final Thought

This project is a great hands-on way to move from **just using machine learning tools** to **actually understanding how they work** — step by step, from logic to math to code.

If you’re serious about mastering ML, start with the basics — just like this. 💡

---


