# 🚢 Titanic Data Analysis

This project contains my complete end-to-end analysis of the **Titanic dataset**, exploring survival patterns using **Pandas**, **NumPy**, **Matplotlib**, and **Seaborn**.  
It includes all stages - from learning/experimentation to a polished final notebook - along with saved figures, the dataset, and required dependencies.

---

## 📁 Folder Contents

### 🧠 `titanic_analysis_arjun.ipynb`
This file represents the **final presentation-ready version** of my analysis. 
It includes all insights and key findings. 

---

### 🧪 `titanic_practice.ipynb`
My **exploratory and testing notebook**, where I experimented with data cleaning, transformations, and visualisation techniques.  
This notebook documents my step-by-step learning process, trial code, and initial attempts before creating the polished version.
It also serves as a revision source, full of inline comments explaining functions and logic.

---

### 📊 `figures/`
This folder contains all the **saved visual outputs** from my final notebook.  
Each figure represents a key part of the analysis:

- `age_distribution_of_survivors_vs_deaths.png` -> Comparison of age between survivors and non-survivors 
- `age_distribution.png` -> Overall passenger age distribution   
- `age_vs_fare_with_survival.png` -> Age vs fare scatterplot with survival colouring  
- `correlation_heatmap.png` -> Correlation matrix between key numerical features  
- `fare_distribution_by_class.png` -> Fare variation across passenger classes  
- `log_binned_fares.png` -> Log-binned histogram  
- `survival_rate_by_gender.png` -> Survival comparison between males and females  

All figures were saved using `plt.savefig()` for clarity and reproducibility.

---

### 📂 `titanic.csv`
The original dataset used throughout this project.  
It includes passenger details such as:

- `Survived` (target variable)  
- `Name`, `Ticket`, `Pclass`, `Sex`, `Age`, `SibSp`, `Parch`, `Fare`, and `Embarked`  

This file is read directly in both notebooks using `pandas.read_csv()`.

---

### 📄 `requirements.txt`
Contains all Python libraries required to run the notebooks successfully:

---

## 🧭 Project Overview

This analysis focuses on uncovering relationships between passenger features and survival rates on the Titanic.  
It demonstrates:
- **Data cleaning and transformation** using Pandas  
- **Feature engineering** to create new insights (e.g., FamilySize, Age Buckets, Fare Bands)  
- **Data visualisation** with Matplotlib and Seaborn  
- **Statistical exploration** using grouping, aggregation, and correlation techniques  

---

## 🎯 Summary

- Conducted complete exploratory data analysis (EDA)  
- Designed clear visuals to highlight survival trends  
- Produced a final polished notebook for readability and presentation  
- Created reproducible visual assets and a well-documented structure  

---
👤 *Author: Arjun*      
🎓 *Mechanical Engineering Student | Data & AI Enthusiast*  
📘 *Project: Titanic Survival Analysis with Python*
