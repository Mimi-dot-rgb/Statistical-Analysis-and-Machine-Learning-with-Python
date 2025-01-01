# Statistical Analysis and Machine Learning with Python

This project demonstrates various statistical and machine learning techniques using Python. It is divided into five parts, each focusing on a different aspect of data analysis and modeling, including hypothesis testing, time-series analysis, clustering, and regression.

---

## Project Overview

### **Part 1: Hypothesis Testing**
- **Task:** Compare groups in the Abalone dataset (Female, Infant, Male) and identify statistically separable groups using a p-value cutoff of 0.05.
- **Gene-Disease Association:** Determine the statistical significance of the association between gene X and disease Y using journal article data.

### **Part 2: Time-Series Analysis**
- **Dataset:** `homework.8.flow_data.csv`
- **Tasks:**
  - Convert time data to a datetime index.
  - Visualize data and calculate a 14-day rolling average for a specific column.
  - Plot the rolling average for the year 2010.

### **Part 3: Hierarchical Clustering**
- **Dataset:** Iris data.
- **Tasks:**
  - Perform hierarchical clustering using the Ward method.
  - Visualize clusters using a dendrogram.
  - Generate clusters at a specified depth and add cluster assignments back to the dataset.

### **Part 4: KMeans Clustering**
- **Dataset:** Iris data.
- **Tasks:**
  - Perform KMeans clustering on petal length and width data.
  - Calculate the sum of squared errors (SSE).
  - Visualize clusters and centroids on a scatter plot.
  - Add cluster assignments back to the original dataset.

### **Part 5: Linear Regression**
- **Dataset:** `insurance.csv`
- **Tasks:**
  - Add a binary column for smoker status.
  - Generate a correlation table.
  - Build a linear regression model to predict charges based on smoker status.
  - Evaluate the model using R² and display the regression equation.

---

## Technologies Used
- **Programming Language:** Python
- **Libraries:** pandas, numpy, scipy, matplotlib, seaborn, sklearn, statsmodels
- **Tools:** Jupyter Notebook
