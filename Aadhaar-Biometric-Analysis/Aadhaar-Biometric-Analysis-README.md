# Aadhaar Biometric Authentication Analysis

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=flat-square)

---

## 📌 Project Overview

This project analyzes **Aadhaar biometric authentication transaction data** across India using a dataset of **1.86 million+ records** from UIDAI. The goal was to study how biometric authentication usage is distributed across different states, union territories, and regions of India, and to identify patterns and trends in the data.

---

## 🎯 Objective

- Understand the distribution of Aadhaar biometric transactions across India
- Compare authentication usage by **state**, **union territory**, and **region**
- Classify Indian states into geographic regions (North, South, East, West, etc.)
- Prepare clean, structured data for time-based trend analysis
- Visualize key insights through charts and grouped summaries

---

## 📂 Project Structure

```
Aadhaar-Biometric-Analysis/
│
├── notebook.ipynb          # Main analysis notebook
├── README.md               # Project documentation
└── data/                   # Dataset folder (not uploaded due to size)
    └── aadhaar_data.csv    # Combined dataset (1.86M+ records)
```

---

## 📊 Dataset Details

| Feature | Details |
|---|---|
| Source | UIDAI — Aadhaar Biometric Authentication Data |
| Records | 1.86 Million+ rows |
| Format | Multiple CSV files (combined) |
| Key Columns | Date, State, District, Pincode, Biometric Count (Age Group 1), Biometric Count (Age Group 2) |

---

## 🔧 Tech Stack

| Tool | Purpose |
|---|---|
| Python | Core programming language |
| Pandas | Data loading, cleaning, and manipulation |
| NumPy | Numerical operations |
| Matplotlib | Data visualization and charts |
| Jupyter Notebook | Development environment |

---

## 🚀 What Was Done

### 1. Data Collection & Merging
- Combined multiple CSV files into one unified dataset
- Checked dataset size, shape, column types, and structure

### 2. Data Cleaning
- Identified and handled missing values and duplicate rows
- Standardized column names for consistency
- Fixed inconsistent state name spellings and formatting issues
- Removed invalid or non-state entries from the dataset

### 3. Feature Engineering
- Created a **Region Type** column to classify entries as State or Union Territory
- Built an **India Region Mapping** to group states into:
  - 🗺️ North, South, East, West, Central, North-East, Islands
- Converted the `date` column to proper datetime format

### 4. Analytical Datasets Prepared
- State-wise dataset for geographic analysis
- Union Territory-wise dataset for separate UT analysis
- Time-based dataset for trend and pattern analysis

### 5. Exploratory Data Analysis (EDA)
- Grouped summaries and record counts by state and region
- Calculated total biometric usage for both age groups
- Analyzed regional differences in authentication frequency

### 6. Visualizations
- Bar chart — Age-group-wise Aadhaar biometric transaction comparison
- State-wise transaction distribution
- Region-wise usage patterns

---

## 📈 Key Findings

- **Most records** belonged to States, with a smaller portion from Union Territories
- **Biometric usage varied significantly** across Indian geographic regions
- The dataset required **heavy cleaning** before analysis — a large portion of the work was data preparation on real-world messy data
- Both age groups showed **different usage patterns**, visible through grouped analysis

---

## ▶️ How to Run This Project

1. Clone or download this repository
2. Install required libraries:
```bash
pip install pandas numpy matplotlib jupyter
```
3. Open the notebook:
```bash
jupyter notebook notebook.ipynb
```
4. Run all cells from top to bottom

> **Note:** The full dataset (1.86M+ records) is not included in this repository due to file size. The notebook shows the complete analysis workflow with outputs.

---

## 🙋 About Me

**Manoj Kumawat**
B.Tech Computer Science Engineering — PIET, Jaipur (2027)
Aspiring Data Analyst | Machine Learning Enthusiast | Salesforce Developer

📧 manojkumawat37505@gmail.com
🔗 [LinkedIn](https://www.linkedin.com/in/manoj-kumawat-a18a79290/)
🐙 [GitHub](https://github.com/ManojKumawat075)

---

*If you found this project useful, feel free to ⭐ star the repository!*
