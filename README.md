# hackbio-biocoding-stage-two
This repository contains a series of tasks involving data analysis across some scientific disciplines, including **Microbiology, Botany, and Public Health**. Each task involves data processing, visualization, statistical analysis, and interpretation of results.

## **Table of Contents**
- [Microbiology (Task Code 2.1)](#microbiology-task-code-21)
- [Botany & Plant Science (Task Code 2.3)](#botany--plant-science-task-code-23)
- [Public Health (Task Code 2.7)](#public-health-task-code-27)
- [Technologies & Tools Used](#technologies--tools-used)

---

## **Microbiology (Task Code 2.1)**

### **Objective**
Analyze bacterial growth curves and compare **knockout (-) and knock-in (+) strains**.

### **Tasks**
- Plot **growth curves (OD600 vs. Time)** for each strain.
- Overlay knockout (-) and knock-in (+) strain growth curves.
- Determine **time to reach carrying capacity** for each strain.
- Generate a **scatter plot** and **box plot** comparing knockout vs. knock-in strains.
- Perform **statistical analysis** to determine significant differences.
- Document observations as **comments** in the code.

---

## **Botany & Plant Science (Task Code 2.3)**

### **Objective**
Investigate **metabolic response** differences in pesticide-resistant mutant crops compared to wild-type plants.

### **Tasks**
- Compute **metabolic response difference (ΔM)** between **DMSO treatment** and **24-hour treatment** for wild-type and mutant crops.
- Generate a **scatter plot** for ΔM values.
- Fit a **regression line** (y-intercept = 0, slope = 1).
- Compute **residuals** and categorize metabolites:
  - Color within ±n residuals **grey**.
  - Color outside this range **salmon**.
- Identify and analyze **6 metabolites** that deviate significantly.
- Generate a **line plot** of their metabolic response over **0h, 8h, and 24h**.
- Interpret trends in the metabolic response.

---

## **Public Health (Task Code 2.7)**

### **Objective**
Analyze **NHANES** dataset to study health and nutrition patterns in the U.S.

### **Tasks**
- **Handle missing data** (delete or convert to zero).
- Visualize **histograms** for:
  - **BMI, Weight, Weight in pounds (Weight × 2.2), and Age**.
- Compute key statistics:
  - **Mean** 60-second pulse rate: **73.63**.
  - **Diastolic blood pressure range**: **0-116**.
  - **Variance and standard deviation** for **income**.
- **Scatter plot:** Relationship between **weight and height**, color-coded by:
  - **Gender**
  - **Diabetes** status
  - **Smoking status**
- Conduct **t-tests** for relationships between:
  - **Age and Gender**
  - **BMI and Diabetes**
  - **Alcohol Year and Relationship Status**

---

## **Technologies & Tools Used**
- **Python** (Pandas, NumPy, Matplotlib, Seaborn, SciPy)
- **Jupyter Notebook** for exploratory data analysis
- **Data visualization tools**

---

This README provides an organized and clear guide to the repository 🚀

