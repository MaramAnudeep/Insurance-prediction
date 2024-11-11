# Health Insurance Charges Prediction

## Overview

This project involves performing **Exploratory Data Analysis (EDA)** on a health insurance dataset to understand various factors influencing individual medical costs (charges) billed by health insurance companies. The objective is to uncover patterns and relationships between different features and the target variable, which is the "Charges" (individual medical costs).

As a Data Scientist working with one of the world's leading insurance providers, the goal is to analyze the dataset to make informed, data-driven business decisions for optimizing insurance premiums, underwriting processes, and other business operations.

## Dataset Description

The dataset includes the following columns:

- **age**: Age of the primary beneficiary
- **sex**: Gender of the beneficiary (male/female)
- **bmi**: Body Mass Index, an indicator of body fatness (kg/m²)
- **children**: Number of dependents
- **smoker**: Whether the individual smokes (yes/no)
- **region**: Residential area in the US (northeast, southeast, southwest, northwest)
- **charges**: Individual medical costs billed by the health insurance (target variable)

## Objective

The objective of this project is to perform an exploratory data analysis (EDA) to understand the following:

1. **Which variables are most significant with respect to the target variable (charges)?**
2. **Explore the data distribution of each column. Identify important patterns.**
3. **Provide data-driven insights and recommendations.**

## Tasks and Methodology

### 1. Data Preprocessing
- **Data Cleaning**: Handling missing values, duplicates, and correcting data types if needed.
- **Data Transformation**: Feature engineering, scaling, encoding categorical variables like 'sex', 'smoker', and 'region'.
- **Data Exploration**: Identifying relationships between variables using visualizations like histograms, boxplots, and scatter plots.

### 2. EDA Tasks
- **Univariate Analysis**: Explore the distribution of each variable (e.g., using histograms, boxplots) to understand their spread and central tendency.
- **Bivariate Analysis**: Analyze the relationships between the target variable (charges) and other features, using scatter plots and correlation matrices.
- **Multivariate Analysis**: Investigate complex relationships between multiple variables (e.g., using pair plots, heatmaps).

### 3. Insights and Recommendations
- Based on the findings from the exploratory analysis, conclusions will be drawn about which factors significantly influence medical charges.
- Provide actionable recommendations for the business, such as adjusting premiums based on BMI, smoking status, or age.

## Results and Insights

- **Key Features Influencing Charges**:
  - **Age**: Older individuals tend to have higher medical charges.
  - **BMI**: Higher BMI values are correlated with increased medical charges.
  - **Smoking Status**: Smokers generally have higher charges due to associated health risks.
  - **Region**: There are regional variations in medical costs, likely due to differing healthcare infrastructure and costs.
  
- **Data Distribution**:
  - **Age**: The distribution is right-skewed, with most beneficiaries being younger.
  - **BMI**: A wide range of BMI values, with a higher concentration in the normal to overweight categories.
  - **Charges**: Right-skewed distribution, with a few high medical cost outliers.

- **Important Patterns**:
  - **Smokers** have significantly higher medical charges compared to non-smokers.
  - **People with higher BMI** tend to incur higher healthcare costs.
  - **Older individuals** face increased charges compared to younger individuals.
  
## Recommendations

- **Premium Pricing**: Insurance companies should consider adjusting premium rates based on factors like **BMI**, **age**, and **smoking status**. Individuals with higher BMI or those who smoke should be charged higher premiums due to increased health risks.
  
- **Policy Underwriting**: BMI and smoking status should be key factors in underwriting decisions. High-risk individuals may require more comprehensive health assessments or even exclusions for obesity-related health conditions.

- **Regional Pricing Strategy**: Different regions exhibit varying healthcare costs, and premium pricing should reflect these regional disparities. More expensive regions may require higher premiums to cover costs.

- **Targeted Health Programs**: Implement wellness programs to help individuals manage BMI and quit smoking, thereby reducing health risks and, in turn, potentially lowering premiums.

## Files in the Repository

- `eda_health_insurance.py`: Python script for performing exploratory data analysis and generating visualizations.
- `health_insurance_data.csv`: The health insurance dataset used for analysis.
- `README.md`: Project overview, methodology, and recommendations.

## Requirements

- Python 3.8+
- Libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - sklearn

To install the required libraries, run:

```bash
pip install -r requirements.txt
```

## Conclusion

This EDA project provides insights into the significant factors influencing medical charges in the health insurance sector. By understanding these relationships, insurance companies can adjust their pricing strategies, improve underwriting processes, and offer tailored health programs to minimize risks and improve customer satisfaction.
