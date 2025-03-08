#  DBMAP - Database Management & Processing in R

## Project Overview  
DBMAP (**Database Management and Processing**) is a project implemented in **R** to demonstrate key concepts in **data manipulation, visualization, multi-table joins, missing value handling, and graph-based database schema representation**.

The project is structured into **three levels** of complexity:  
 **EASY:** Basic data processing and visualization  
 **MEDIUM:** Advanced data handling with multiple datasets  
 **HARD:** Graph-based database schema representation  

Each section contains R Markdown (`.Rmd`) files that generate insights and structured reports (`.pdf`).  

---

##  Tasks Completed  

###  EASY Task: Basic Data Processing  
** Objective:**  
- Perform **basic data handling** using `data.table`  
- Merge student-related datasets and visualize the results  

**📂 Files Added:**  
- `EASY/EASY_SOL.Rmd` – R Markdown script  
- `EASY/EASY_SOL.pdf` – PDF output  

** What We Did:**  
- Used `merge()` to **join multiple tables** (students & exam scores)  
- Handled missing values by replacing them with `0`  
- Created a **bar chart** to visualize student scores using `ggplot2`  

** Run it using:**  
```r
rmarkdown::render("EASY/EASY_SOL.Rmd")
```

---

###  MEDIUM Task: Advanced Data Processing & Visualization  

** Objective:**  
- Handle multiple datasets, process missing values, and generate advanced visualizations  

** Files Added:**  
- `MEDIUM/MEDIUM_SOL.Rmd` – R Markdown script  
- `MEDIUM/MEDIUM_SOL.pdf` – PDF output  

** What We Did:**  
- Merged multiple tables (students, exam_scores, and attendance)  
- Applied Mean Imputation for missing values  
- Created a grouped bar chart visualizing trends in student performance  

** Run it using:**  
```r
rmarkdown::render("MEDIUM/MEDIUM_SOL.Rmd")
```

---

### 3️⃣ HARD Task: Graph-Based Database Schema Representation  

** Objective:**  
- Represent a database schema using graph structures and analyze relationships  

** Files Added:**  
- `HARD/HARD_SOL.Rmd` – R Markdown script  
- `HARD/HARD_SOL.pdf` – PDF output  

** What We Did:**  
- Used the `igraph` library to visualize database relationships  
- Computed network metrics (degree, betweenness centrality)  
- Applied Kamada-Kawai layout for structured visualization  

** Run it using:**  
```r
rmarkdown::render("HARD/HARD_SOL.Rmd")
```

---

##  Project Structure  
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

---

##  How to Use This Repository  

### 1️⃣ Clone the Repository  
```sh
git clone https://github.com/Dishdavey21/DBMAP.git
cd DBMAP
```

### 2️⃣ Install Required Packages in R  
```r
install.packages(c("data.table", "ggplot2", "igraph", "rmarkdown"))
```

### 3️⃣ Run the R Markdown Files  
```r
rmarkdown::render("EASY/EASY_SOL.Rmd")  # For EASY task
rmarkdown::render("MEDIUM/MEDIUM_SOL.Rmd")  # For MEDIUM task
rmarkdown::render("HARD/HARD_SOL.Rmd")  # For HARD task
```

### 4️⃣ View Output PDFs  
- Navigate to the `EASY/`, `MEDIUM/`, or `HARD/` folder  
- Open the corresponding PDF file  


## **Contributors**
- **Disha H. Davey**



