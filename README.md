# **Employee Attrition Analysis**

**Group Members:** Michael DeMasi, Katherine Yang, Tolani Oshinusi, Jeremy Cho

### **Project Summary**
This project aims to analyze and predict factors influencing employee attrition. It utilizes a dataset comprising 74,610 employee records, each identified by a unique Employee ID and containing features relevant to employee attrition. The dataset provides comprehensive information about employees' demographics, job-related attributes, and personal circumstances, offering a realistic view of the factors affecting employee retention.

Additionally, the project will explore employee sentiment by extracting reviews from [CareerBliss](https://www.careerbliss.com/). Using NLP models, we will analyze the sentiment of these reviews to determine if companies with higher turnover rates receive more negative feedback compared to those with lower turnover rates. The code for extracting reviews is found in a supplemental notebook called "Web_Scraping".

**Note:** GPU should be used for optimal runtime of the Flair NLP model.

**Dataset**: [Employee Attrition Dataset](https://www.kaggle.com/datasets/nikhilbhosle/employee-attrition-uncleaned-dataset)

### **Motivation**
Employee attrition poses significant challenges for organizations, including high replacement costs, loss of institutional knowledge, and disruptions in team dynamics. Understanding the key drivers behind attrition can help organizations identify at-risk employees and implement strategies to improve retention.

By exploring this dataset, we aim to uncover insights into the factors contributing to employee attrition and build predictive models to proactively address retention challenges.

### **Approach**
- **Part 1: Data Wrangling and Cleaning**:
  - Clean and preprocess the dataset by handling missing and duplicate values for analysis and modeling.

- **Part 2: Exploratory Data Analysis (EDA)**:
  - Encode categorical variables to generate summary statistics, visualizations, and correlation analyses to understand patterns and trends in attrition.
  - Explore demographic and job-related attributes to identify at-risk groups.

- **Part 3: Employee Review Analysis**:
  - Scrape employee reviews from multiple high attrition companies and low attrition companies and perform a sentiment analysis using NLP
  - Perform EDA to identify any correlation between attrition and employee review sentiment

- **Part 4: Modeling with Machine Learning**:
  - Train machine learning models, such as Random Forest, Logistic Regression, and Gradient Boosted Trees to predict employee attrition.
  - Evaluate model accuracy, precision, recall, and other metrics to ensure reliable performance.
  - Analyze feature importance to interpret the drivers of attrition.
