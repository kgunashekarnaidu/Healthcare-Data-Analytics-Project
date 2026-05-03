#  Healthcare Analytics: Cancer Patient Data (2015–2024)

##  Project Overview

This project focuses on **data preprocessing and exploratory data analysis (EDA)** of a global cancer patient dataset spanning **2015 to 2024**. The goal is to uncover meaningful insights, prepare the data for modeling, and enable predictive analytics for cancer severity.

---

## Objectives

* Understand and explore the structure of the dataset
* Clean and preprocess raw healthcare data
* Handle missing values and outliers
* Encode categorical variables for machine learning
* Perform exploratory data analysis to identify trends and patterns
* Prepare the dataset for predictive modeling

---

##  Dataset Description

The dataset contains **global cancer patient records** with **15 features**, including:

* `Patient_ID` – Unique identifier
* `Age` – Patient age
* `Gender` – Male/Female
* `Country_Region` – Geographic location
* `Year` – Year of record (2015–2024)
* `Genetic_Risk` – Genetic predisposition level
* `Air_Pollution` – Environmental exposure
* `Alcohol_Use` – Consumption level
* `Smoking` – Smoking habits
* `Obesity_Level` – Health condition indicator
* `Cancer_Type` – Type of cancer
* `Cancer_Stage` – Stage of cancer
* `Treatment_Cost_USD` – Treatment expenses
* `Survival_Years` – Survival duration
* `Target_Severity_Score` – **Target variable**

### Target Variable

**Target_Severity_Score**

* Represents the severity of the disease
* Higher values → More severe condition
* Lower values → Less severe condition
* Used as the dependent variable for predictive modeling

---

##  Technologies Used

* **Python**
* **NumPy** – Numerical computations
* **Pandas** – Data manipulation
* **Matplotlib & Seaborn** – Data visualization

---

##  Project Workflow

### 1. Data Understanding

* Identified dataset structure and feature roles
* Defined objective and target variable

### 2. Data Inspection

* Checked dataset shape and structure
* Explored data types and summary statistics

### 3. Data Cleaning

* Handled missing values
* Ensured consistency in data

### 4. Outlier Handling

* Detected anomalies using statistical methods
* Applied appropriate treatments

### 5. Encoding Categorical Variables

* Used **One-Hot Encoding** for:

  * `Gender`
  * `Cancer_Type`
  * `Cancer_Stage` (treated as categorical despite ordinal nature)

---

##  Exploratory Data Analysis (EDA)

* Distribution analysis of key features
* Correlation analysis between variables
* Visualization of trends across years and regions
* Identification of factors influencing severity

---

##  Potential Applications

* Predictive modeling for cancer severity
* Healthcare risk assessment
* Cost analysis and optimization
* Public health insights and policy-making

---

##  Project Structure

```
├── Healthcare Analytics of cancer patient data (2015-2024).ipynb
├── global_cancer_patients_2015_2024.csv
└── README.md
```

---

##  How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```
2. Install dependencies:

   ```bash
   pip install numpy pandas matplotlib seaborn
   ```
3. Open the Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

---

## Future Improvements

* Build machine learning models for severity prediction
* Perform feature engineering
* Deploy as a web-based analytics dashboard
* Integrate real-time healthcare datasets

