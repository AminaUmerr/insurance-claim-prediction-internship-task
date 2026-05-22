# Insurance Claim Prediction using Linear Regression

## Project Overview

This project focuses on predicting **medical insurance claim charges** based on an individual's personal and medical information. The aim is to estimate insurance costs using **Machine Learning (Linear Regression)** and analyze the factors that significantly affect medical insurance charges.

This project was completed as part of the **Data Science & Analytics Internship Task**.

---

## Objective

The objective of this project is to:

- Predict **medical insurance claim amounts (`charges`)**
- Build a **Linear Regression model**
- Understand the impact of:
  - **Age**
  - **BMI (Body Mass Index)**
  - **Smoking Status**
- Evaluate model performance using:
  - **MAE (Mean Absolute Error)**
  - **RMSE (Root Mean Squared Error)**

---

## Dataset Information

### Dataset Used
**Medical Cost Personal Dataset**

The dataset contains personal and medical details of individuals and their insurance charges.

### Features in Dataset

| Feature | Description |
|----------|-------------|
| age | Age of the individual |
| sex | Gender of the individual |
| bmi | Body Mass Index |
| children | Number of dependents |
| smoker | Smoking status |
| region | Residential area |
| charges | Medical insurance charges (Target Variable) |

---

## Technologies & Libraries Used

The following Python libraries were used:

- **Python**
- **Pandas** → Data loading and preprocessing
- **NumPy** → Numerical computations
- **Matplotlib** → Data visualization
- **Seaborn** → Statistical visualization
- **Scikit-Learn** → Machine learning model building

---

## Project Workflow

The project was completed in the following stages:

### 1. Data Loading
- Loaded dataset using **Pandas**
- Displayed dataset structure and summary statistics

### 2. Data Understanding
- Examined:
  - Dataset shape
  - Column names
  - Data types
  - Statistical summary

### 3. Data Cleaning & Preparation
- Checked for missing values
- Removed duplicate records
- Converted categorical variables into numerical format using **One-Hot Encoding**

### 4. Exploratory Data Analysis (EDA)
Several visualizations were created to understand data patterns and relationships.

#### Age vs Insurance Charges
- Scatter plot used to analyze relationship between age and insurance cost.

#### BMI vs Insurance Charges
- Visualized how BMI affects medical charges.

#### Smoking Status vs Charges
- Box plot used to compare smoker and non-smoker insurance expenses.

#### Correlation Heatmap
- Identified feature relationships and strongest correlations.

---

## Machine Learning Model

### Model Used
**Linear Regression**

Linear Regression was used to predict insurance charges based on personal and medical information.

### Train-Test Split
The dataset was divided into:

- **80% Training Data**
- **20% Testing Data**

This ensures fair evaluation of model performance.

---

## Model Evaluation

The model performance was evaluated using:

### 1. Mean Absolute Error (MAE)
Measures the average prediction error between actual and predicted values.

### 2. Root Mean Squared Error (RMSE)
Measures model prediction accuracy while penalizing larger errors.

---

## Key Insights

From the analysis:

- **Smoking status** has the strongest impact on insurance charges.
- Individuals who smoke tend to have **significantly higher medical expenses**.
- **Age** shows a positive relationship with insurance charges.
- Higher **BMI** tends to increase insurance costs.

---

## Project Structure

```text
insurance-claim-prediction
│── data
│   └── insurance.csv
│
│── notebook
│   └── insurance_claim_prediction.ipynb
│
│── images
│
│── README.md
```

---

## How to Run the Project

### Step 1: Clone Repository

```bash
git clone <your-repository-link>
```

### Step 2: Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Step 3: Open Jupyter Notebook

Run:

```bash
jupyter notebook
```

Open:

```text
insurance_claim_prediction.ipynb
```

Run all notebook cells.

---

## Results

The Linear Regression model successfully predicted insurance charges and demonstrated how important lifestyle and demographic factors influence medical insurance costs.

The project successfully fulfilled all internship task requirements, including:

✔ Data Cleaning  
✔ Exploratory Data Analysis (EDA)  
✔ Data Visualization  
✔ Linear Regression Modeling  
✔ MAE Evaluation  
✔ RMSE Evaluation  
✔ Conclusion & Insights

---

## Author

Amina Umer Dar
Data Science & Analytics Intern
