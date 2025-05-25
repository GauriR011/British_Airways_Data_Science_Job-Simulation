# British Airways Job Simulation

This repository contains my work for the British Airways Job Simulation completed on Forage. The project focused on analyzing customer feedback data and building a predictive model to understand customer behavior. Below is a detailed description of each task and the tools and technologies used.

## Overview
This project involved two key tasks: analyzing customer feedback data to derive actionable insights and developing a predictive model to evaluate the likelihood of customers buying holidays. Each task incorporated data manipulation, analysis, and visualization techniques.

## Tasks
### Task 1: Customer Feedback Analysis
Objective: Scrape and collect customer feedback, analyze it for insights, and present findings visually.

#### Subtasks:

**Data Collection:**
-  Scraped customer feedback from a third-party source using Beautiful Soup library.
- Aggregated and cleaned the collected data for analysis.

**Data Analysis:**
- Performed text analysis and sentiment analysis to uncover customer sentiment trends.
- Identified key themes and pain points based on customer feedback.

**Presentation of Insights:**
- Created a PowerPoint presentation to summarize findings.
- Highlighted actionable insights to improve customer experience.

![alt text](https://github.com/GauriR011/British_Airways_Data_Science_Job-Simulation/blob/main/Screenshots/BA_Analysis.png)

### Task 2: Predictive Modeling on Customer Booking Data
Objective: Develop a predictive model to assess the likelihood of customers buying holidays.

#### Subtasks:

**Data Preparation:**
- Cleaned and preprocessed the provided dataset.
- Performed exploratory data analysis (EDA) to understand patterns and relationships within the data.
- Engineered features to enhance model performance.
- Used correlation matrix to determine the features that affected the target column

**Model Development:**
- Trained a RandomForest model to predict the target outcome (customer purchases).
- Conducted hyperparameter tuning to optimize model performance.

**Model Evaluation:**
- Evaluated the model's performance using cross-validation.
- Computed relevant evaluation metrics (e.g., accuracy, precision, recall, F1 score).
- Identified feature importance to understand variable contributions to model predictions.

**Presentation of Results:**
- Summarized findings in a single PowerPoint slide.
- Provided an interpretation of the model's predictive power and its feasibility for future use.

![alt text](https://github.com/GauriR011/British_Airways_Data_Science_Job-Simulation/blob/main/Screenshots/BA_Modelling.png)

## Environment and Tools
**Programming Languages:**
Python (for data analysis and predictive modeling)

**Libraries and Frameworks:**
- Pandas, NumPy (data manipulation and preprocessing)
- Matplotlib, Seaborn (data visualization)
- Scikit-learn (model training and evaluation)
- BeautifulSoup (web scraping for Task 1)

**Tools:**
- Jupyter Notebook (for code development)
- Microsoft PowerPoint (for presenting insights and findings)


