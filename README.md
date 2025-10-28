# Tumor Size Prediction and Lifestyle Impact Modeling in R

This project analyzes how lifestyle and demographic factors—such as physical activity, alcohol consumption, smoking history, and living environment—affect tumor size.  
It uses two-way ANOVA and multiple linear regression to explore both individual and interaction effects of these variables.  

The report is written in a **templatized R Markdown framework**, allowing users to easily replace variable names or datasets to quickly produce new analyses and visualizations.

---

## 📂 Repository Contents

| File | Description |
|------|--------------|
| `Tumor_project.Rmd` | Main R Markdown file containing all analysis, code, and inline interpretations. |
| `Tumor_project.html` | Rendered HTML report version for easy viewing in a browser. |
| `colorectal_Midterm.RData` | Dataset used in the analysis (colorectal cancer data). |

---

## 🎯 Project Objectives

- Investigate how lifestyle factors influence tumor size (in mm).  
- Test for main and interaction effects using **two-way ANOVA**.  
- Fit and evaluate **linear regression models** for prediction.  
- Simulate lifestyle changes through **scenario-based modeling**.  
- Provide reusable, **templatized code** for quick reanalysis.

---

## 🧠 Scenario Example

A hypothetical case study (“Joe”) illustrates how changes in one behavior—such as quitting smoking or increasing physical activity—affect predicted tumor size while keeping other factors constant.  
The model shows that quitting smoking results in the **largest decrease** in expected tumor size, emphasizing the importance of behavioral factors in health outcomes.

---

## 🧩 Features

- **Templatized Analysis:** Swap datasets or variable names to generate new reports effortlessly.  
- **Statistical Modeling:** Two-way ANOVA, linear regression, and model comparison.  
- **Scenario-Based Predictions:** Predict outcomes under different behavioral conditions.  
- **Visualizations:** ggplot2 plots for boxplots, interactions, and prediction comparisons.  
- **Reproducibility:** Fully implemented in R Markdown with clean, dynamic text rendering.

---

## ⚙️ Technologies Used

- **R**
- **ggplot2** – Visualization  
- **broom**, **dplyr** – Model interpretation and data manipulation  
- **R Markdown** – Reproducible reporting  

---

## 🚀 How to Run the Project

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/tumor-size-modeling.git
