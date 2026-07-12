# 📂 Automated EDA with Pandas Profiling

This section demonstrates how to perform **Automated Exploratory Data Analysis (EDA)** using **YData Profiling** (formerly **Pandas Profiling**). Instead of manually exploring a dataset, YData Profiling generates a comprehensive HTML report containing descriptive statistics, missing value analysis, correlations, distributions, duplicate detection, and data quality insights with a single command.

---

## 📖 Learning Notebook

| Notebook | Description |
| :-------- | :---------- |
| [`Day22.ipynb`](documents/Day22.ipynb) | Learn how to generate an automated EDA report using YData Profiling and analyze datasets with minimal code. |

---

## 📚 Official Resources

| Resource | Link |
| :------- | :--- |
| **YData Profiling Documentation** | https://docs.profiling.ydata.ai/latest/ |
| **YData Profiling GitHub Repository** | https://github.com/ydataai/ydata-profiling |

---

## 📊 Datasets

| Dataset | Purpose |
| :------ | :------ |
| [`train.csv`](documents/train.csv) | Titanic dataset used to generate an automated profiling report. |
| [`patients.csv`](documents/patients.csv) | Healthcare dataset for practicing automated data profiling. |
| [`staff.csv`](documents/staff.csv) | Employee dataset for data quality assessment and reporting. |
| [`staff_schedule.csv`](documents/staff_schedule.csv) | Staff scheduling dataset used for profiling structured data. |
| [`services_weekly.csv`](documents/services_weekly.csv) | Weekly service dataset used to explore automated EDA reports. |

---

## 🔍 Topics Covered

### 📌 Environment Setup

| Step | Description |
| :--- | :---------- |
| **Uninstall Existing Package** | Remove older versions of `pandas-profiling` or `ydata-profiling`. |
| **Install Latest Version** | Install the latest version of **YData Profiling** using `pip`. |

---

### 📌 Automated EDA Workflow

| Step | Description |
| :--- | :---------- |
| **Load Dataset** | Read the dataset using `pandas.read_csv()`. |
| **Create Profile Report** | Generate an interactive profiling report using `ProfileReport()`. |
| **Export Report** | Save the report as an HTML file using `profile.to_file()`. |

---

## 📋 Report Includes

The generated profiling report automatically provides:

- Dataset Overview
- Variable Summary
- Descriptive Statistics
- Missing Value Analysis
- Duplicate Record Detection
- Correlation Analysis
- Numerical Feature Distribution
- Categorical Feature Distribution
- Data Quality Warnings
- Sample Data Preview
- Interactive Visualizations

---

## 📁 Repository Structure

```text
Repository
│
├── README.md
├── documents
│   ├── Day22.ipynb
│   ├── train.csv
│   ├── patients.csv
│   ├── staff.csv
│   ├── staff_schedule.csv
│   └── services_weekly.csv
│
└── train.html (Generated after running the notebook)
```

---

## 🎯 Learning Objectives

- Understand the concept of Automated Exploratory Data Analysis (EDA)
- Install and configure **YData Profiling**
- Generate detailed profiling reports with minimal code
- Analyze missing values, duplicates, and correlations automatically
- Explore numerical and categorical feature distributions
- Export interactive HTML reports for sharing and documentation
- Reduce manual effort in the initial data exploration phase

---

> **Note:** The generated HTML profiling report (`train.html`) is created after executing the notebook and is not included in the repository by default. All notebooks and datasets are stored inside the **`documents/`** directory.