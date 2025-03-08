# DBMAP - Data-Based Machine Learning Algorithm Project

This repository contains the implementation of various data-based machine learning techniques categorized into **Easy**, **Medium**, and **Hard** levels. The project follows a structured approach to problem-solving using different methodologies, ensuring a progressive learning curve.

## Project Overview
The **DBMAP** project is designed to demonstrate different levels of complexity in data handling, feature engineering, and machine learning model training. Each level contains an R Markdown (`.Rmd`) file that executes specific techniques and generates corresponding results in PDF format.

## Tasks Completed
### **Easy Task: Basic Data Processing & Visualization**
#### **Objective:**
- Perform fundamental data processing and generate simple visualizations using R.

#### **Files Added:**
- `EASY/EASY_SOL.Rmd` – Contains the implementation of basic data handling and visualization.
- `EASY/EASY_SOL.pdf` – Generated output showcasing results.

#### **What We Did:**
- Loaded a dataset and performed basic exploratory data analysis (EDA).
- Created simple visualizations (scatter plots, histograms, and line graphs).
- Used `ggplot2` for data visualization.

#### **Run it using:**
```r
rmarkdown::render("EASY/EASY_SOL.Rmd")
```

---
### **Medium Task: Feature Engineering & Model Training**
#### **Objective:**
- Implement feature extraction techniques and train a machine learning model.

#### **Files Added:**
- `MEDIUM/MEDIUM_SOL.Rmd` – Contains feature engineering and model implementation.
- `MEDIUM/MEDIUM_SOL.pdf` – Generated output showcasing results.

#### **What We Did:**
- Performed data preprocessing and feature selection.
- Applied **Principal Component Analysis (PCA)** for dimensionality reduction.
- Trained a classification model using **Naïve Bayes**.
- Evaluated model performance using accuracy and confusion matrices.

#### **Run it using:**
```r
rmarkdown::render("MEDIUM/MEDIUM_SOL.Rmd")
```

---
### **Hard Task: Clustering & Advanced Model Implementation**
#### **Objective:**
- Implement unsupervised learning techniques for data clustering.

#### **Files Added:**
- `HARD/HARD_SOL.Rmd` – Contains clustering techniques.
- `HARD/HARD_SOL.pdf` – Generated output showcasing results.

#### **What We Did:**
- Applied **K-Means Clustering** and **Hierarchical Clustering**.
- Implemented **DBSCAN** (Density-Based Spatial Clustering of Applications with Noise).
- Compared clustering results using different evaluation metrics.
- Visualized cluster formation and separation.

#### **Run it using:**
```r
rmarkdown::render("HARD/HARD_SOL.Rmd")
```

---
## **Project Structure**
```
DBMAP/
│── EASY/
│   ├── EASY_SOL.Rmd
│   ├── EASY_SOL.pdf
|   ├── README.md
│── MEDIUM/
│   ├── MEDIUM_SOL.Rmd
│   ├── MEDIUM_SOL.pdf
|   ├── README.md
│── HARD/
│   ├── HARD_SOL.Rmd
│   ├── HARD_SOL.pdf
|   ├── README.md
│── README.md
```

## **How to Use This Repository**
1. Clone the repository:
   ```sh
   git clone https://github.com/Dishdavey21/DBMAP.git
   ```
2. Navigate to the appropriate folder (`EASY`, `MEDIUM`, or `HARD`).
3. Open the `.Rmd` file in RStudio or run it using `rmarkdown::render()`.

## **Contributors**
- **Disha H. Davey**



