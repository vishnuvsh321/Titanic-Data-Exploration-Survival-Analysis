# Titanic Data Exploration & Survival Analysis

![Titanic](https://upload.wikimedia.org/wikipedia/commons/thumb/f/fd/RMS_Titanic_3.jpg/1200px-RMS_Titanic_3.jpg)

## 📊 Project Overview
This repository contains a comprehensive analysis of the Titanic dataset, focusing on preprocessing, visualization, and uncovering patterns in passenger survival. The project is implemented in Python using libraries like Pandas, NumPy, Matplotlib, and Seaborn.

## 📖 Dataset
The dataset used is the famous Titanic passenger list, which includes details such as:
- Passenger demographics (age, gender)
- Ticket class (Pclass)
- Survival status (Survived)
- Fare, Embarkation point, and more.

## 🛠️ Key Features
1. **Data Preprocessing**:
   - Handling missing values (e.g., filling missing ages with the mean).
   - Dropping irrelevant columns (e.g., `Cabin` due to high missing values).
   - Encoding categorical variables.

2. **Exploratory Data Analysis (EDA)**:
   - Statistical summaries of numerical features.
   - Count plots for categorical features (e.g., `Survived`, `Sex`, `Pclass`).
   - Visualizations to explore relationships between survival and other variables.

3. **Visualizations**:
   - Histograms and box plots for age distribution.
   - Bar plots for survival rates by gender and class.
   - Correlation heatmaps.

## 📁 Files Included

- `Titanic_data_exploration.ipynb`: Main analysis notebook
- `titanic.csv`: Dataset (post-cleaning)
- `Summary of Findings.pdf`: Summary report of observations and visualizations

## 📈 Results
- **Survival Rate**: ~38% of passengers survived.
- **Key Findings**:
  - Women and children had higher survival rates.
  - Higher-class passengers (Pclass 1) were more likely to survive.
  - Age and fare also showed correlations with survival.

## How to Use
1. Clone the repository:
   ```bash
   [git clone https://github.com/your-username/titanic-data-exploration.git](https://github.com/vishnuvsh321/Titanic-Data-Exploration-Survival-Analysis)
