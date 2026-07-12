# 📂 Exploratory Data Analysis - Bivariate & Multivariate Analysis

This section focuses on **Bivariate** and **Multivariate Analysis**, two essential stages of Exploratory Data Analysis (EDA). The notebook demonstrates how to analyze relationships between two or more variables using statistical visualizations, helping uncover patterns, trends, correlations, and interactions within the data.

---

## 📖 Learning Notebook

| Notebook | Description |
| :-------- | :---------- |
| [`day21.ipynb`](documents/day21.ipynb) | Learn how to perform bivariate and multivariate analysis using Seaborn and Pandas through various visualization techniques. |

---

## 📊 Dataset

| Dataset | Purpose |
| :------ | :------ |
| [`train.csv`](documents/train.csv) | Titanic dataset used for analyzing relationships between categorical and numerical features. |
| **Tips** *(Seaborn Dataset)* | Restaurant tipping dataset used for scatter plot demonstrations. |
| **Flights** *(Seaborn Dataset)* | Airline passenger dataset used for line plots and heatmap visualizations. |
| **Iris** *(Seaborn Dataset)* | Classic flower dataset used for pairwise feature analysis. |

---

## 🔍 Topics Covered

### 📌 Bivariate Analysis

| Visualization | Relationship | Description |
| :------------ | :----------- | :---------- |
| **Scatter Plot** | Numerical ↔ Numerical | Analyze relationships between two numerical variables using `sns.scatterplot()`. |
| **Bar Plot** | Numerical ↔ Categorical | Compare numerical values across different categories using `sns.barplot()`. |
| **Box Plot** | Numerical ↔ Categorical | Visualize distributions and detect outliers across categories using `sns.boxplot()`. |
| **Distribution Plot** | Numerical ↔ Categorical | Compare distributions of numerical variables across different categories. |
| **Heatmap** | Categorical ↔ Categorical | Display relationships between categorical variables using `pd.crosstab()` and `sns.heatmap()`. |
| **Cluster Map** | Categorical ↔ Categorical | Group similar categories using hierarchical clustering with `sns.clustermap()`. |

---

### 📌 Multivariate Analysis

| Visualization | Description |
| :------------ | :---------- |
| **Pair Plot** | Explore pairwise relationships among multiple numerical features with class-wise coloring using `sns.pairplot()`. |
| **Line Plot** | Visualize trends over time using grouped numerical data with `sns.lineplot()`. |
| **Clustered Heatmap** | Analyze patterns in pivot tables using hierarchical clustering with `sns.clustermap()`. |

---

## 📝 Notes & Diagrams

| Topic | Preview |
| :---- | :------ |
| EDA - Bivariate & Multivariate Analysis | ![EDA Bivariate & Multivariate Analysis](images/eda-bivariate-and-multivariate-analysis-01.png) |

---

## 📁 Repository Structure

```text
Repository
│
├── README.md
├── documents
│   ├── day21.ipynb
│   └── train.csv
│
└── images
    └── eda-bivariate-and-multivariate-analysis-01.png
```

---

## 🎯 Learning Objectives

- Understand the concepts of Bivariate and Multivariate Analysis
- Analyze relationships between numerical variables using Scatter Plots
- Compare numerical values across categories using Bar Plots and Box Plots
- Compare feature distributions using Distribution Plots
- Explore relationships between categorical variables using Heatmaps and Cluster Maps
- Visualize pairwise feature relationships using Pair Plots
- Analyze time-series trends using Line Plots
- Discover hidden patterns and clusters using hierarchical clustering techniques
- Gain deeper insights into datasets before feature engineering and model building

---

> **Note:** The notebook uses both **local datasets** (`train.csv`) and **built-in Seaborn datasets** (`tips`, `flights`, and `iris`) to demonstrate different visualization techniques. All notebooks and local datasets are stored inside the **`documents/`** directory, while images used in this README are stored inside the **`images/`** directory.