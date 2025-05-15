# Student-Performance-Prediction-Using-Linear-Regression

This project analyzes and predicts student performance using **Linear Regression**, with preprocessing, visualization, residual analysis, and **regularization techniques** (Ridge and Lasso). The dataset includes variables like study hours, sleep, previous scores, and extracurricular activities.


##  Dataset

- **File**: `Student_Performance.csv`
- **Features**:
  - `Hours Studied`
  - `Previous Scores`
  - `Extracurricular Activities`
  - `Sleep Hours`
  - `Sample Question Papers Practiced`
  - `Performance Index` (Target)


## Technologies Used

- **Python 3.8+**
- Libraries:
  - `pandas`, `numpy`
  - `matplotlib`, `seaborn`, `plotly`
  - `scikit-learn`, `scipy`


##  Project Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/student-performance-regression.git
   cd student-performance-regression

2. **Install required packages**:
   ```bash
   pip install -r requirements.txt
   
  Ensure your dataset file is named Student_Performance.csv and placed in the root folder.

3. **Run the notebook or Python file to execute all parts**:
   ```bash
   python student_performance_analysis.py

## Project Breakdown

**Part 1: Data Preprocessing & EDA**
- Check for missing values

- Encode categorical variables

- Scale features using StandardScaler

**Visualize:**

- Histograms of performance

- Scatter plots

- Correlation heatmap

---
  

**Part 2: Linear Regression**

**Simple Linear Regression:**

- Only Hours Studied vs Performance Index

**Multiple Linear Regression:**

- Uses all features

- Coefficients printed

---


**Part 3: Evaluation Metrics:**

- MAE, MSE, RMSE

- R² and Adjusted R²

---

**Part 4: Residual Analysis**

- Residual plots

- Histogram

- Q-Q plot to check normality of residuals

---


**Part 5: 3D Visualization**

- 3D regression plane using plotly with:

- Hours Studied & Previous Scores

---


**Part 6: Regularization**
- RidgeCV with best alpha selected via cross-validation

- LassoCV with alpha tuning

- Evaluates both regularized models using the same metrics

---


**Output:**

Visual insight into the influence of factors like study hours, sleep, and practice on performance


**Comparison between:**

- Simple vs. multiple linear regression

- Ridge vs. Lasso regression

- Interactive 3D visualization of regression surface


