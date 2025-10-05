# PRODIGY_DS_02

## Task 2: Data Cleaning and Exploratory Data Analysis (EDA)

This task is part of my Prodigy Infotech internship.  
The objective was to perform **data cleaning** and **exploratory data analysis (EDA)** on the Titanic dataset to explore relationships between variables.

---

### Dataset
- `titanic_dataset.csv` → Titanic dataset from Kaggle (train.csv)

---

### Contents
- `Task2.ipynb` → Python notebook performing:
  - Data cleaning (handling missing values, rounding ages, removing outliers, converting categorical columns)
  - Exploratory data analysis (histograms, countplots, boxplots)
- Output plots → Visualizations of distributions and relationships

---

### Data Cleaning Steps
1. **Removed irrelevant columns** like `Cabin`. (too many missing data)
2. **Filled missing values**:
   - `Age` → replaced missing values with median age and rounded to integers  
   - `Embarked` → replaced missing values with the most frequent value (mode)  
3. **Converted categorical columns**: `Sex`, `Embarked` (for plotting/grouping)  
4. **Outlier handling**:
   - Removed age outliers using the IQR method for cleaner visualizations 
---

- **Relationships**:
  - Survival vs Sex (countplot)  
  - Age vs Survival (boxplot)   

**Insights Identified**:
- Women had higher survival rates than men  
- Children survived more than adults   
---

### Libraries Used
- Python 3  
- Pandas  
- Matplotlib  
- Seaborn  

---
