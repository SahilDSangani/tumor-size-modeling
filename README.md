# Tumor Size Prediction and Lifestyle Impact Modeling in R

This project explores how lifestyle and demographic factors—such as physical activity, smoking, alcohol consumption, and living environment—affect tumor size. Using R, the analysis fits multiple linear models and two-way ANOVAs to evaluate both individual and interaction effects of these variables.  

The R Markdown file (`Midterm.Rmd`) is **templatized**, allowing you to easily swap in new datasets or variable names to generate fresh analyses and visualizations with minimal code changes.  

---

## 📊 Project Overview

- **Goal:** Identify which behavioral changes most strongly reduce tumor size risk.
- **Methods:**  
  - Two-way ANOVA to analyze main and interaction effects.  
  - Linear regression modeling to quantify variable importance.  
  - Scenario-based prediction to simulate how lifestyle changes impact expected tumor size.  
- **Visualization:**  
  - Interaction plots and boxplots to visualize categorical relationships.  
  - Scenario-based prediction charts for interpretability.

---

## 🧠 Scenario Example

A hypothetical case study is presented for **Joe**, a 40-year-old male, to demonstrate the model’s predictive power.  
By holding all other variables constant, the analysis simulates how individual lifestyle changes—such as quitting smoking or increasing physical activity—affect predicted tumor size.  
The model shows that quitting smoking yields the largest reduction in expected tumor size, highlighting the importance of behavioral interventions.

---

## 🧩 Features

- **Templatized analysis:** swap variable names and datasets easily.  
- **Statistical testing:** ANOVA, linear regression, and model comparison.  
- **Visualization-ready:** clean ggplot2-based plots for immediate reporting.  
- **Reproducible:** fully written in R Markdown with inline statistical explanations.

---

## ⚙️ Technologies Used

- **R**  
- **ggplot2** – visualization  
- **R Markdown** – reproducible reporting framework

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/SahilDSangani/tumor-size-modeling.git
