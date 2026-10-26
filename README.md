# 📊 R Programming Laboratory (BE CMPN) — 24102A2005

[![Language: R](https://img.shields.io/badge/Language-R-276DC3.svg?style=for-the-badge&logo=R&logoColor=white)](https://www.r-project.org/)
[![Notebook: Jupyter](https://img.shields.io/badge/Notebook-Jupyter-F37626.svg?style=for-the-badge&logo=Jupyter&logoColor=white)](https://jupyter.org/)
[![Repository: GitHub](https://img.shields.io/badge/GitHub-24102A2005__R--PROGRAMMING-181717.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Shaziya-1/24102A2005_R-PROGRAMMING)
[![Department: Computer Engineering](https://img.shields.io/badge/Department-Computer%20Engineering%20(CMPN)-00599C.svg?style=for-the-badge)](https://en.wikipedia.org/wiki/Computer_engineering)

This repository contains the complete collection of laboratory experiments and assignments for the **R Programming Laboratory Course** in Bachelor of Computer Engineering (BE CMPN - A).

The curriculum spans from foundational vector and matrix computation, robust data preprocessing, and inferential statistical testing to high-performance big data analytics (`data.table`, multicore parallelization) and end-to-end machine learning pipelines (RFM customer segmentation, K-Means, Hierarchical Clustering, PCA, Random Forest, SVM).
---

## 👩‍💻 Student Profile

| Attribute | Details |
| :--- | :--- |
| **Student Name** | Sajiya Shaikh |
| **Roll Number** | `24102A2005` |
| **Program / Division** | BE Computer Engineering (CMPN - A) |
| **Course** | R Programming Laboratory |
| **Repository URL** | [https://github.com/Shaziya-1/24102A2005_R-PROGRAMMING](https://github.com/Shaziya-1/24102A2005_R-PROGRAMMING) |

---

## 📑 Repository Structure & Laboratory Index

| Lab # | Notebook File | Topic & Domain | Key Packages / Methods |
| :---: | :--- | :--- | :--- |
| **Lab 01** | [`24102A2005_R_LAB_01.ipynb`](./24102A2005_R_LAB_01.ipynb) | **Data Cleaning & Preprocessing in R** | `NA`, `NULL`, `NaN`, Imputation loops, `tryCatch`, Summary functions, Exporting cleaned data |
| **Lab 02** | [`24102A2005_R_LAB_02.ipynb`](./24102A2005_R_LAB_02.ipynb) | **Basics of Calculations & Vector Operations** | Vector arithmetic (`+`, `-`, `*`, `/`), Scalar operations, Type casting, BODMAS, `c()` |
| **Lab 03** | [`24102A2005_R_LAB_03.ipynb`](./24102A2005_R_LAB_03.ipynb) | **Course Assessment & Rubrics Mapping** | Course Outcome Mapping (CO1–CO6), Rubric evaluation framework, Laboratory metadata |
| **Lab 04** | [`24102A2005_R_LAB_04.ipynb`](./24102A2005_R_LAB_04.ipynb) | **Matrix Operations & Logical Expressions** | Matrix algebra, `%*%`, `crossprod()`, `eigen()`, `solve()`, `rbind()` / `cbind()`, Row/Col sums & means, Logical operators |
| **Lab 05** | [`24102A2005_R_LAB_05.ipynb`](./24102A2005_R_LAB_05.ipynb) | **Missing Data Handling & Exploration** | `is.na()`, `which(is.na())`, `complete.cases()`, `na.omit()`, NULL vs NA differences |
| **Lab 06** | [`24102A2005_R_LAB_06.ipynb`](./24102A2005_R_LAB_06.ipynb) | **Statistical Analysis on Palmer Penguins** | Descriptive statistics, Two-sample t-test, Cohen's *d*, One-Way ANOVA, Tukey's HSD, Mann-Whitney U, Kruskal-Wallis, `ggplot2` |
| **Lab 07** | [`24102A2005_R_LAB_07.ipynb`](./24102A2005_R_LAB_07.ipynb) | **Customer Segmentation & Predictive Analytics** | UCI Online Retail, RFM Engineering, Elbow Method, Silhouette Score, K-Means, Dendrograms, PCA 2D/3D, Random Forest, SVM, ROC-AUC |
| **Lab 08** | [`24102A2005_R_LAB_08.ipynb`](./24102A2005_R_LAB_08.ipynb) | **High-Performance Big Data Analytics Using R** | NYC TLC Yellow Taxi records, `data.table` aggregations, `lapply()`, `purrr::map()`, `foreach`, `doParallel`, Benchmarking & Speedup |
| **Lab 09** | [`24102A2005_R_LAB_09.ipynb`](./24102A2005_R_LAB_09.ipynb) | **String Manipulation & Text Processing (NPTEL)** | `cat()`, `format()`, `paste()` / `paste0()`, `strsplit()`, Case transformations, Substrings, Alphabets manipulation |

---

## 🔬 Detailed Experiment Summaries

### [Lab 01: Data Cleaning & Preprocessing in R](./24102A2005_R_LAB_01.ipynb)
- **Objective:** Master essential data preparation techniques in Base R and specialized utilities.
- **Key Highlights:**
  - Import raw datasets with inspection of dimensions, data types, and head/tail records.
  - Distinguish between missing (`NA`), undefined numerical operations (`NaN`), and non-existent values (`NULL`).
  - Implemented an automated missing value summary function reporting missing counts and percentages per column.
  - Applied numeric imputation (mean/median replacement using conditional iterative loops) and categorical mode imputation.
  - Robust error handling using `tryCatch()` to safeguard file reading and computational procedures.
  - Comparative diagnostic visualization before and after data cleaning, concluding with exporting the curated data to CSV.

### [Lab 02: Basics of Calculations & Vectors in R](./24102A2005_R_LAB_02.ipynb)
- **Objective:** Understand elementary R programming constructs, vectorization, and data typing.
- **Key Highlights:**
  - Element-wise arithmetic operations on numerical vectors (addition, subtraction, multiplication, division).
  - Variable assignment semantics (`<-`, `=`, `<<-`) for numeric and character literals.
  - Dynamic type checking (`mode()`, `typeof()`) and explicit coercion (`as.numeric()`, `as.character()`).
  - Handling special values including `Inf`, `-Inf`, and evaluating operator precedence using standard BODMAS conventions.
  - Vector creation using `c()`, scalar broadcasting, and behavior of whitespace and case sensitivity in R syntax.

### [Lab 03: R Programming Laboratory Assignment & Evaluation Rubrics](./24102A2005_R_LAB_03.ipynb)
- **Objective:** Structure laboratory assessment goals and align experiments with formal Course Outcomes.
- **Key Highlights:**
  - Outlines the key syllabus modules: Control Flow, Functions, Vectorized Programming, Exception Handling, Missing Data Management, and Quality Assessment.
  - Rubric scoring matrix across real-life applications, problem-solving ability, critical reasoning, and creativity.
  - Explicit mapping to Course Outcomes CO1 through CO6.

### [Lab 04: Matrix Operations & Logical Expressions](./24102A2005_R_LAB_04.ipynb)
- **Objective:** Deep-dive into 2-dimensional array transformations and linear algebra operations in R.
- **Key Highlights:**
  - Matrix generation using `matrix()`, diagonal matrices `diag()`, and custom row/column naming (`dimnames()`, `rownames()`, `colnames()`).
  - Matrix slicing, indexing, sub-setting, transposition (`t()`), and scalar arithmetic.
  - Fast dimensional aggregations with `rowSums()`, `colSums()`, `rowMeans()`, and `colMeans()`.
  - Advanced linear algebra: matrix multiplication with `%*%`, inner/cross product using `crossprod()`, matrix inversion using `solve()`, and spectral decomposition via `eigen()`.
  - Matrix concatenation using `rbind()` and `cbind()`.
  - Truth-value evaluation and short-circuit evaluation: vector-level vs single-element logical operators (`|` vs `||`, `&` vs `&&`).

### [Lab 05: Missing Data Handling & Exploration](./24102A2005_R_LAB_05.ipynb)
- **Objective:** In-depth diagnosis, detection, and filtering of incomplete observations.
- **Key Highlights:**
  - Conceptual and computational differentiation between `NA` and `NULL`.
  - Coordinate detection of missing values using `which(is.na(x))` and global missing counts via `sum(is.na(x))`.
  - Identification of complete records using `complete.cases()` and dataset filtering via `na.omit()`.
  - Subsetting techniques to isolate rows with clean observations.

### [Lab 06: Statistical Analysis on Palmer Penguins](./24102A2005_R_LAB_06.ipynb)
- **Objective:** Perform rigorous inferential statistical analysis on morphological traits of penguin species (*Adelie*, *Chinstrap*, *Gentoo*).
- **Key Highlights:**
  - Exploratory data analysis (mean, median, standard deviation, interquartile ranges, distribution skewness).
  - Parametric hypothesis testing: Two-sample independent *t*-tests and effect size estimation using Cohen's *d*.
  - Analysis of Variance (One-Way ANOVA) to test morphological variation across species.
  - Post-hoc pairwise comparisons using Tukey's Honest Significant Difference (Tukey's HSD).
  - Non-parametric statistical tests: Mann-Whitney U test (Wilcoxon rank-sum test) and Kruskal-Wallis test for non-normal distributions.
  - Informative visualizations built with `ggplot2` (box plots, density curves, violin plots, and correlation charts).

### [Lab 07: Customer Segmentation & Predictive Analytics](./24102A2005_R_LAB_07.ipynb)
- **Objective:** Build an end-to-end unsupervised clustering and supervised machine learning workflow for e-commerce customer profiling.
- **Key Highlights:**
  - Ingested and cleaned the UCI Online Retail transaction dataset.
  - Outlier detection and treatment using Interquartile Range (IQR) filtering.
  - Feature engineering of RFM metrics: **Recency** (days since last purchase), **Frequency** (total orders), and **Monetary Value** (total spend).
  - Feature scaling with Z-score standardization.
  - Optimal cluster estimation using the **Elbow Method (Within-Cluster Sum of Squares)** and **Silhouette Analysis**.
  - Unsupervised clustering: **K-Means Clustering** and **Agglomerative Hierarchical Clustering** with dendrogram generation.
  - Dimensionality reduction and cluster visualization using Principal Component Analysis (PCA 2D projection).
  - Supervised classification: Partitioned data into Train/Test sets to predict high-value customer tiers using **Random Forest** and **Support Vector Machines (SVM)**.
  - Comprehensive model evaluation: Accuracy, Precision, Recall, F1-Score, Confusion Matrices, and ROC-AUC curve analysis.
  - Feature importance ranking from Random Forest and interactive 3D visualizations with `plotly`.
  - Actionable business strategies and segment-specific retention recommendations.

### [Lab 08: High-Performance Big Data Analytics Using R](./24102A2005_R_LAB_08.ipynb)
- **Objective:** Process and analyze millions of NYC TLC Yellow Taxi trip records using high-performance and parallel computing paradigms.
- **Key Highlights:**
  - Big data ingestion and memory optimization by pruning unnecessary column types.
  - Spatial lookup integration: joined trip records with official NYC Taxi Zone boundary tables.
  - Feature extraction: temporal dimensions (pickup hour, day of week, monthly trends, duration).
  - Domain analytics: highest revenue routes, most frequented pickup/drop-off zones, fare vs distance distributions, tip and payment methods.
  - Programming paradigm benchmarking: Functional programming (`lapply()`, `purrr::map()`) vs Vectorized Base R vs `data.table` syntax (`microbenchmark`).
  - Multicore parallel computing: Sequential execution versus parallelized execution using `foreach` and `doParallel`.
  - Calculation of speedup ratios, multi-thread CPU utilization, and visual dashboards of taxi demand trends.

### [Lab 09: String Manipulation & Text Processing (NPTEL Foundations of R)](./24102A2005_R_LAB_09.ipynb)
- **Objective:** Master string formatting, pattern processing, and string manipulation techniques based on NPTEL Foundations of R.
- **Key Highlights:**
  - Formatted text output using `cat()`, `print()`, and format specifiers (`format()`).
  - String concatenation using `paste()`, `paste0()`, and custom separators (`sep`, `collapse`).
  - Text splitting into tokens with `strsplit()` and list handling.
  - Character casing transformations (`toupper()`, `tolower()`), substring extraction (`substr()`), and operations on built-in alphabet vectors (`letters`, `LETTERS`).

---

## 🎯 Course Outcomes (CO) Mapping

| Course Outcome | Description | Demonstrated in |
| :---: | :--- | :--- |
| **CO1** | Understand fundamentals of R syntax, control structures, and vector operations. | Labs 01, 02, 09 |
| **CO2** | Implement user-defined functions, matrix algebra, and logical expressions. | Labs 02, 04 |
| **CO3** | Design robust data cleaning pipelines, handle missing data (`NA`/`NULL`), and exception handling (`tryCatch`). | Labs 01, 05 |
| **CO4** | Conduct descriptive, parametric, and non-parametric statistical hypothesis tests on empirical datasets. | Lab 06 |
| **CO5** | Apply high-performance computing, `data.table`, benchmarking, and parallel processing (`doParallel`). | Lab 08 |
| **CO6** | Develop machine learning solutions (clustering, PCA, classification) with interactive visualizations. | Labs 07, 08 |

---

## 🛠️ Required Packages & Dependencies

To execute all notebooks seamlessly, ensure R (>= 4.0.0) is installed alongside the following packages:

```r
# Core & Data Manipulation
install.packages(c("tidyverse", "data.table", "dplyr", "purrr", "readr", "tibble"))

# Statistical Analysis & Hypothesis Testing
install.packages(c("palmerpenguins", "effsize", "car", "rstatix"))

# Machine Learning & Clustering
install.packages(c("cluster", "factoextra", "randomForest", "e1071", "pROC", "caret"))

# High-Performance & Parallel Computing
install.packages(c("foreach", "doParallel", "microbenchmark", "parallel"))

# Visualization
install.packages(c("ggplot2", "plotly", "corrplot", "gridExtra", "RColorBrewer"))
```

---

## 🚀 How to Run the Notebooks Locally

### 1. Clone the Repository
```bash
git clone https://github.com/Shaziya-1/24102A2005_R-PROGRAMMING.git
cd 24102A2005_R-PROGRAMMING
```

### 2. Launch Jupyter Notebook or JupyterLab
Ensure the R kernel (`IRkernel`) is registered:
```r
# In R terminal (run once):
install.packages("IRkernel")
IRkernel::installspec(user = FALSE)
```

Then start Jupyter:
```bash
jupyter notebook
# or
jupyter lab
```

Alternatively, open and run the `.ipynb` files directly in **VS Code** with the *Jupyter* and *R* extensions installed.

---

## 📂 File Directory

```text
24102A2005_R-PROGRAMMING/
│
├── 24102A2005_R_LAB_01.ipynb    # Lab 1: Data Cleaning & Preprocessing
├── 24102A2005_R_LAB_02.ipynb    # Lab 2: Vector Operations & Calculations
├── 24102A2005_R_LAB_03.ipynb    # Lab 3: Assessment & Course Outcome Rubrics
├── 24102A2005_R_LAB_04.ipynb    # Lab 4: Matrix Algebra & Logical Expressions
├── 24102A2005_R_LAB_05.ipynb    # Lab 5: Missing Data Handling
├── 24102A2005_R_LAB_06.ipynb    # Lab 6: Statistical Analysis (Palmer Penguins)
├── 24102A2005_R_LAB_07.ipynb    # Lab 7: Customer Segmentation & Machine Learning
├── 24102A2005_R_LAB_08.ipynb    # Lab 8: Big Data Analytics & Parallel Processing
├── 24102A2005_R_LAB_09.ipynb    # Lab 9: String Manipulation (NPTEL Series)
├── .gitignore                   # Standard R/Jupyter ignore rules
└── README.md                    # Comprehensive repository documentation
```

---

## ✍️ Author & Contact

- **Student:** Sajiya Shaikh
- **Roll Number:** 24102A2005
- **Branch:** BE Computer Engineering (CMPN - A)
- **GitHub Profile:** [@Shaziya-1](https://github.com/Shaziya-1)

---
*Maintained as part of the academic coursework for the R Programming Laboratory.*
