# 🧠 Heart Disease Analysis & Visualization

> **A Comprehensive Exploratory Data Analysis (EDA) on Cardiovascular Health Trends**

---

## 📊 Project Overview

Predictive healthcare analytics is one of the most impactful applications of Data Science. This project performs an in-depth **Exploratory Data Analysis (EDA)** on patient records to identify the physiological markers most closely associated with heart disease.

### 🎯 Objectives

* **Identify Correlations:** Which features (e.g., Cholesterol, Max Heart Rate) drive heart disease?
* **Data Storytelling:** Create high-fidelity visualizations that make complex medical data intuitive.
* **Preprocessing:** Map categorical encodings (0, 1) to human-readable labels for better interpretability.

---

## 🔍 Dataset Deep-Dive

The analysis is based on the `heart.csv` dataset, featuring 14 critical clinical attributes.

### Featured Attributes:

* **Target:** `0` (Healthy) vs `1` (Heart Disease).
* **CP:** Chest pain type (4 levels).
* **Thalach:** Maximum heart rate achieved.
* **Chol:** Serum cholesterol in mg/dl.

---

## 📈 Analysis Highlights

We didn't just plot data; we looked for the *story* behind the numbers.

### 1. Categorical Distribution

Used **Countplots** to analyze the balance of the dataset across `sex`, `cp` (chest pain), and `target`.

### 2. Continuous Variable Variance

Utilized **Boxplots** and **Stripplots** to detect outliers and distribution spreads for `thalach` (Heart Rate) and `age`.

### 3. Multi-Feature Comparisons

Leveraged **Matplotlib subplots** to visualize how the presence of heart disease fluctuates across different demographics and clinical findings simultaneously.

---

## 🛠️ Tech Stack & Environment

| Component | Technology | Role |
| --- | --- | --- |
| **Language** | Python 3.9 | Main logic and processing. |
| **Data Handling** | Pandas | Cleaning, mapping, and filtering. |
| **Visualization** | Seaborn & Matplotlib | High-level statistical and custom plots. |
| **Environment** | Jupyter Notebook | Iterative analysis and documentation. |

---

## 🚀 How to Explore

1. **Clone the Repo:**
```bash
git clone https://github.com/YourUsername/heart-disease-analysis-eda.git

```


2. **Install Dependencies:**
```bash
pip install pandas seaborn matplotlib

```


3. **Run the Analysis:**
Open `extensive-analysis-visualization-with-python.ipynb` in Jupyter or VS Code.

---

## 📁 Project Structure

```bash
📦 heart-disease-analysis-eda
 ┣ 📜 heart.csv          # Raw clinical data
 ┣ 📜 extensive-analysis.ipynb  # Main EDA Notebook
 ┗ 📜 README.md          # Project documentation

```

---

## 🧡 Acknowledgments & License

* **Data Source:** UCI Machine Learning Repository.
* **License:** Distributed under the MIT License.

---
