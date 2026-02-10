# Learning Probability Density Functions using MLE

## 📌 Project Title
**Learning Probability Density Functions Using a Roll-Number-Parameterized Non-Linear Model and Maximum Likelihood Estimation**

---

## 📖 Overview
This project demonstrates how to learn and estimate a probability density function (PDF) from real-world data using **Maximum Likelihood Estimation (MLE)**.  

The dataset used contains **NO₂ (Nitrogen Dioxide) concentration values** from an Indian air quality dataset. To introduce personalization and originality, a **roll-number-based non-linear transformation** is applied to the data before estimating the PDF parameters.

---

## 🎯 Objectives
- Load and preprocess air quality data
- Select NO₂ concentration values dynamically
- Apply a roll-number-based non-linear transformation
- Perform exploratory data analysis (EDA)
- Estimate PDF parameters using **Maximum Likelihood Estimation**
- Visualize original vs transformed data distributions

---

## 📂 Project Structure



---

## 🛠️ Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Jupyter Notebook

---

## 🔄 Methodology

### 1. Dataset Loading
- The air quality dataset is loaded using robust encoding handling.
- The NO₂ column is detected dynamically (case-insensitive).

### 2. Roll-Number-Based Parameterization
Roll-number-dependent constants are used to personalize the model:
- `a_r` – amplitude factor
- `b_r` – frequency factor

### 3. Non-Linear Transformation
Each NO₂ value `x` is transformed as:

\[
z = x + a_r \cdot \sin(b_r \cdot x)
\]

This ensures uniqueness of results across students.

### 4. Exploratory Data Analysis
- Mean and variance are computed for both original and transformed data
- Histograms are plotted for comparison

### 5. Maximum Likelihood Estimation
- Mean (`μ`) and variance (`σ²`) of the transformed variable are estimated
- A Gaussian-type PDF is constructed using MLE estimates

---

## 📊 Results
- The transformed data follows a smooth Gaussian-like distribution
- MLE accurately estimates the PDF parameters
- Small parameter perturbations significantly change results, ensuring originality

---

## 📈 Visualizations
- Histogram of original NO₂ values
- Histogram of transformed values
- Estimated PDF curve over transformed data

---

## ✅ Conclusion
This project successfully applies a personalized non-linear transformation to air quality data and estimates its probability density function using Maximum Likelihood Estimation. The approach combines statistical theory with real-world data analysis and ensures academic originality.

---

## 👤 Author
**Dixant Sharma**  


---

## 📜 License
This project is for **academic and educational purposes only**.
