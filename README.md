  # Final Project - Data Analytics and Diagnostics

  This repository contains the final project for the Data Analytics and Diagnostics course.  
  The project focuses on **exploratory data analysis, normalization, PCA, and K-Means clustering** applied to global health statistics, specifically **COVID-19 cases in Germany (2024)**.

  ---

  ## 📌 Project Overview

  The objective of this project is to:
  - Analyze health-related indicators associated with COVID-19
  - Reduce data dimensionality using **Principal Component Analysis (PCA)**
  - Identify meaningful patterns using **K-Means Clustering**
  - Interpret cluster characteristics based on mortality, healthcare capacity, treatment types, and education level

  ---
  
  ## 📂 Dataset
  
  - **Source**: Kaggle – *Global Health Statistics*  
  - **Dataset link**:  
    👉 https://www.kaggle.com/datasets/malaiarasugraj/global-health-statistics/data  
  
  The dataset contains a wide range of **global health indicators**, including:
  - Mortality rates  
  - Communicable and non-communicable diseases  
  - Risk factors  
  - Public health and healthcare system statistics  
  
  For this project, the dataset was filtered to:
  - **Country**: Germany  
  - **Year**: 2024  
  - **Disease**: COVID-19  

  ---

  ## 🛠 Libraries Used

  This project is implemented in **R** using the following libraries:

  - `cluster`
  - `factoextra`
  - `reshape2`
  - `ggplot2`
  - `knitr`

  ---

  ## 🔄 Analysis Workflow

  1. Data Preparation  
  2. Exploratory Data Analysis (EDA)  
  3. Data Normalization  
  4. Principal Component Analysis (PCA)  
  5. K-Means Clustering  
  6. Cluster Profiling and Interpretation  

  ---

  ## 📊 Key Results

  - **Optimal number of clusters**: 2  
  - **Cluster interpretation**:
    - **Cluster 1**: Higher mortality, more dominant treatment profile, higher education index, but relatively lower hospital bed availability
    - **Cluster 2**: Lower mortality, better hospital bed availability, less dominant treatment profile, and lower education index

  ---

  ## 📁 Repository Structure

  ```
  ├── FP-ADD-KelompokC2_enhanced_english.Rmd
  ├── README.md
  ```

  *(Dataset downloaded separately via Google Drive link)*

  ---

  ## 👥 Team Members

  - Rafindra Nabiel Fawwaz (5026231024)  
  - Gusti Gratia Delpiera (5026231097)  
  - M. Naufal Erwin Effendi (5026231152)  
  - Gabriel Hadi Melvanto Sihaloho (5026231189)

  ---

  ## 🚀 How to Run

  1. Download the dataset from the link provided above
  2. Place `Global Health Statistics.csv` in the project directory
  3. Open the `.Rmd` file in **RStudio**
  4. Install required libraries if necessary
  5. Knit the document to **HTML**

  ---

  This project is created for academic purposes only.
