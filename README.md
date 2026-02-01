<div align="center">

# 🩺 Sleep Health & Lifestyle Analysis

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Pandas](https://img.shields.io/badge/Library-Pandas-150458)
![Seaborn](https://img.shields.io/badge/Library-Seaborn-green)
![Matplotlib](https://img.shields.io/badge/Library-Matplotlib-orange)
![Status](https://img.shields.io/badge/Status-Completed-success)

<h3> 🧠 Unlocking the Secrets of Better Sleep using Data Science </h3>

</div>

---

## 📌 Project Overview
Why do some people sleep better than others? Is stress the main enemy, or is it our job?
This project analyzes the sleep patterns and lifestyle habits of **374 individuals** to identify the key factors affecting sleep quality and health.

Using **Python** and advanced statistical visualization, I uncovered actionable insights about the relationship between BMI, occupation, and sleep disorders.

---

## 🔍 Key Insights & Findings

### 1. ⚖️ The Obesity-Insomnia Link
> **Insight:** Analysis reveals a strong correlation between **BMI Category** and **Sleep Disorders**.
> - Individuals with **"Normal"** weight rarely suffer from sleep disorders.
> - **Obese** and **Overweight** individuals account for the majority of *Sleep Apnea* and *Insomnia* cases.



### 2. 📉 Stress vs. Sleep (Correlation Analysis)
> **Insight:** A negative correlation was found between Sleep Duration and Stress Levels.
> - As sleep duration **increases**, stress levels significantly **decrease**.
> - This was confirmed using a Correlation Heatmap.



### 3. 👨‍⚕️ Occupation Impact
> **Insight:** Not all jobs are equal when it comes to rest.
> - **Engineers** tend to have the highest sleep quality and duration.
> - **Sales Representatives** and **Scientists** reported the lowest sleep quality and highest stress.

---

## 🛠️ Technical Approach

### 1. Data Cleaning & Preprocessing
* **Handling Missing Values:** Imputed null values in the `Sleep Disorder` column (NaN → "None") based on domain knowledge.
* **Standardizing Categories:** Fixed inconsistent labels in `BMI Category` (merged "Normal Weight" into "Normal").

### 2. Feature Engineering
* **Blood Pressure Parsing:** Split the complex `126/83` string format into two separate numerical features: `Systolic` and `Diastolic` using vectorized string operations.

### 3. Exploratory Data Analysis (EDA)
* **Correlation Matrix:** Used `seaborn.heatmap` to identify relationships between numerical variables.
* **Distribution Analysis:** Used `boxplots` to detect outliers in sleep quality across different professions.

---

## 🚀 How to Run
1.  Clone the repository.
2.  Install dependencies:
    ```bash
    pip install pandas seaborn matplotlib
    ```
3.  Run the Jupyter Notebook:
    ```bash
    jupyter notebook Sleep_Health_Analysis.ipynb
    ```

---

## 👤 Author
**Reda EL MOTASSADIQ**
* Data Analyst | Python Developer
* *Connecting the dots between Lifestyle & Health.*
