# Real Vs Fake Job Prediction Analysis

## Project Goal
The objective of this project is to detect fraudulent job postings to improve user trust and reduce the impact of scams on job platforms and recruitment agencies.

### Overview
This project analyzes fraudulent and non-fraudulent job postings from a dataset set obtained from kaggle. This dataset contains job descriptions consisting of both real and fake job postings on an international level. The data consists of both textual information and meta-information about the jobs. This analysis aims to create classification models which can learn the job descriptions which are fraudulent based on its features such as title, location, description, and other attributes provided in the dataset. This will help the company's platform avoid scams and improve the integrity of job listings.

### Business Problem
Recruit Holdings' company aims to improve Glassdoor, a jobseeking platform, to maintain the integrity of their listings ensuring a positive user experience. However, fraudulent job postings are a growing concern not only misleading job seekers leading to financial loss and wasted effort, but also tarnishing the platform’s reputation. This results in a decrease in user engagement due to a decrease in trustworthiness, lower customer retention, and potential legal ramifications. Therefore, the company critically needs an automated solution to detect and remove fraudulent job postings before they can cause harm.

This analysis, therefore, aims in coming up with a reliable classification model that can predictively identify and filter out fraudulent job postings, thereby improving the trustworthiness of the platform and safeguarding users from potential scams to enhance user experience.
### Data
This dataset is obtained from kaggle and contains about 18K job descriptions consisting of both real and fake job postings. The dataset contains a mix of textual information and meta-information, which are crucial for understanding and predicting fraudulent job postings.

The features in this dataset include title, location, department, salary_range, company_profile, description, requirements, benefits, telecommuting, has_company_logo, has_questions, employment_type, required_experience, required_education, industry and function. The target variable in this analysis is the fraudulent column that states the fraudulent and non-fraudulent jobs.

The analysis will aims to:
Evaluate the balance between real and fake job postings to understand the potential challenges of imbalanced classes incase which specialized techniques like SMOTE or class weighting may be necessary during model training.

Identify any missing values in the dataset, especially in key features like 'Description' or 'Company Profile'.

Analyze correlations between features and the target variable to identify the most predictive features. Features such as 'Has Company Logo' and 'Has Questions' could be significant indicators of job authenticity.


### Methods
This project applies descriptive analysis as well as classification models. The models are applied to show a predictive analysis on detecting fraudulent and non-fraudulent job postings. This analysis applies Logistics Regression, Decision Trees, Random Forest and Gradient Boosting. The models' accuracy is also tested to check the best applied model for the analysis.

### Results



### Conclusion



### Further Analysis


### For more Information
See the full analysis [Jupyter Notebook](Film_Performance_Analysis.ipynb)  or review the  [Presentation](Film_Data_Analaysis_Presentation.pdf)

## Dashboard

View the interactive [Tableau Dashboard](https://public.tableau.com/app/profile/maureen.wambugu/viz/Film_Analysis_Dashboard/FilmAnalysisDashboard?publish=yes) for detailed insights.

![Tableau Dashboard](Images/Film_Analysis_Dashboard.png)