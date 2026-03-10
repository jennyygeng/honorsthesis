# Clinical Trial Outcomes Simulation Dashboard 🏥📊

An interactive dashboard and comprehensive report developed to simulate and analyze how patient dropout rates and missing data mechanisms impact the statistical power of clinical trials, utilizing the Treatment of Lead-Exposed Children (TLC) dataset.

## 📌 Project Overview
In clinical trials, patient non-adherence and dropout can severely compromise data integrity and statistical power. Using the longitudinal TLC dataset, this project provides a simulated environment to:
* Estimate treatment effects under various patient adherence assumptions.
* Visualize the impact of different missing data mechanisms (e.g., Missing Completely at Random, Missing at Random).
* Provide an interactive R Shiny dashboard for exploring how these variables affect overall clinical trial outcomes.

## ⚙️ Repository Contents
* **`TLC Dashboard.Rmd`**: The interactive Shiny-enabled R Markdown dashboard used to visualize the simulated data and power analyses.
* **`TLC Simulation Report.Rmd`**: A detailed statistical report outlining the methodology, simulation parameters, and findings.
* **`tlc_mock.csv`**: The dataset containing both the original TLC trial data and the simulated missingness columns.
* **`tlc-data.txt`**: Raw text format of the TLC dataset.
* **`tlc-dictionary.txt`**: The data dictionary defining all variables used in the analysis.

## 🛠️ Tech Stack
* **Language:** R
* **Framework:** R Markdown, Shiny (Flexdashboard)
* **Key Libraries:** `shiny`, `rmarkdown`, `dplyr`, `ggplot2`
* **Environment:** RStudio
