# Missing Data Mechanisms: Monte Carlo Simulation Dashboard 🏥📊

An interactive R Shiny web application and Honors Thesis analyzing how differential attrition and missing data mechanisms (MCAR, MAR) impact the statistical power of longitudinal clinical trials.

### 🔗 **[View the Live Interactive Dashboard Here](https://jennyygeng.shinyapps.io/TLC_Shiny_Dashboard/)**

## 📌 Project Overview
In clinical trials, patient non-adherence and dropout can severely compromise data integrity and statistical power. Using the longitudinal Treatment of Lead-Exposed Children (TLC) dataset as a framework, this project provides a simulated Monte Carlo environment to:
* Estimate treatment effects under various patient adherence assumptions.
* Visualize the impact of different missing data mechanisms.
* Evaluate how incomplete data impacts statistical significance and the validity of clinical conclusions.

## ⚙️ Repository Contents
* **`GengJ.pdf`**: The final approved Honors Thesis report detailing the clinical background, statistical methodology, and conclusions.
* **`TLC Dashboard.Rmd`**: The source code for the interactive Shiny (Flexdashboard) application.
* **`TLC Simulation Report.Rmd`**: The detailed statistical report generating the simulation parameters and findings.
* **`tlc_mock.csv`**: The dataset containing both the original TLC trial data and the simulated missingness columns.
* **`tlc-dictionary.txt` & `tlc-data.txt`**: Data dictionaries and abstracts defining the variables and origins of the TLC study.

## 🛠️ Tech Stack
* **Language:** R
* **Framework:** R Markdown, Shiny (Flexdashboard)
* **Key Libraries:** `shiny`, `rmarkdown`, `dplyr`, `ggplot2`
* **Deployment:** shinyapps.io
