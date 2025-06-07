# Task-5
 Exploratory Data Analysis (EDA)
# Exploratory Data Analysis on Olympic Dataset

## Project Overview
This project performs Exploratory Data Analysis (EDA) on the **Olympics Dataset** sourced from Kaggle. The goal is to extract meaningful insights through visual and statistical exploration using Python libraries like `pandas`, `seaborn`, and `matplotlib`.

---

##  Tools & Libraries
- Python
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn

---

## EDA Workflow

### 1. Data Loading & Inspection
- Used `.head()`, `.info()`, `.describe()` to explore the dataset.
- Checked for missing values and duplicates.

### 2. Data Cleaning
- Dropped duplicate records.
- Handled missing values in key columns like `Medal` and `Height`.

### 3. Visual Exploration
- Countplots for gender and medal distribution.
- Histograms and KDE plots for age.
- Boxplots and violin plots for height/weight distributions.
- Heatmaps for correlation and medal count by year/country.
- Line charts for participation trends.

### 4. Grouped Analysis
- Grouped by `Year`, `NOC`, `Sport`, and `Sex` to analyze trends in age, height, and medal counts.

---

##  Key Findings

- Male athletes outnumbered females, especially in earlier years.
- Gold medals were most frequently won by athletes from the USA.
- Average athlete age has remained mostly between 20–30 years.
- Some sports, like **Basketball**, had taller athletes, while **Gymnastics** had shorter ones.
- Female participation has increased steadily over the years.

---

## Deliverables
- `olympic_eda.ipynb`: Complete Jupyter Notebook with code and markdowns.
- `summary_of_findings.pdf`: A PDF report summarizing key insights and visualizations.
- `README.md`: This documentation file.

