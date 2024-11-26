# **Employee Attrition Analysis**

### **Project Summary**
This project aims to analyze and predict factors influencing employee attrition. It utilizes a dataset comprising 74,610 employee records, each identified by a unique Employee ID and containing features relevant to employee attrition. The dataset provides comprehensive information about employees' demographics, job-related attributes, and personal circumstances, offering a realistic view of the factors affecting employee retention.

Additionally, the project will explore employee sentiment by extracting reviews from [CareerBliss](https://www.careerbliss.com/). Using NLP models, we will analyze the sentiment of these reviews to determine if companies with higher turnover rates receive more negative feedback compared to those with lower turnover rates.

**Note:** GPU should be used for optimal runtime of the NLP models

**Dataset**: [Employee Attrition Dataset](https://www.kaggle.com/datasets/nikhilbhosle/employee-attrition-uncleaned-dataset)

### **Motivation**
Employee attrition poses significant challenges for organizations, including high replacement costs, loss of institutional knowledge, and disruptions in team dynamics. Understanding the key drivers behind attrition can help organizations identify at-risk employees and implement strategies to improve retention.

By exploring this dataset, we aim to uncover insights into the factors contributing to employee attrition and build predictive models to proactively address retention challenges.

### **Objectives**
1. **Understand Key Attrition Factors**:
   - Perform exploratory data analysis (EDA) to identify factors most strongly associated with employee attrition.
   - Investigate how attrition rates vary across demographics (e.g., age, gender, department) and job roles.
   
2. **Predictive Modeling**:
   - Build machine learning models to predict the likelihood of employee attrition.
   - Evaluate model performance and interpret the most significant predictors of attrition.

3. **Actionable Recommendations**:
   - Use insights from the analysis to recommend strategies for reducing attrition and improving employee retention.

### **Approach**
- **Data Wrangling and Cleaning**:
  - Clean and preprocess the dataset by handling missing and duplicate values for analysis and modeling.

- **Exploratory Data Analysis (EDA)**:
  - Encode categorical variables to generate summary statistics, visualizations, and correlation analyses to understand patterns and trends in attrition.
  - Explore demographic and job-related attributes to identify at-risk groups.

- **Feature Engineering and Selection**:
  - Create additional features if needed (e.g., tenure buckets or overtime categories).
  - Use statistical methods or model-based techniques to select the most relevant features for predictive modeling.

- **Model Development and Evaluation**:
  - Train machine learning models, such as Random Forest, Logistic Regression, and Gradient Boosted Trees to predict employee attrition.
  - Evaluate model accuracy, precision, recall, and other metrics to ensure reliable performance.
  - Analyze feature importance to interpret the drivers of attrition.

- **Conclusions and Recommendations**:
  - Summarize findings from the analysis and highlight actionable strategies for reducing attrition.
  - Provide tailored recommendations for organizational improvements based on key insights.

---

This project will provide valuable insights into employee attrition dynamics and offer data-driven strategies to enhance workforce stability and satisfaction.
