# HealthcareProviderChoicesModel

## Analysis of Healthcare Provider Choices Using Multinomial Logistic Regression

### Overview
This project applies a Multinomial Logistic Regression Model to explore the determinants of healthcare provider choices among a sample of civilian non-institutionalized US population. The data analyzed in this project comes from the National Health Interview Survey (NHIS) responses collected from sample adults between 2019 and 2022. The focus is to understand how various factors such as demographics, insurance status, income, and general health status (including both mental and physical health) influence the choice of healthcare provider.

### Objectives
- **To identify the factors that significantly influence the choice of healthcare providers** such as doctors' offices/health centers, urgent care centers, hospital emergency rooms, and military health centers.
- **To quantify the impact of these factors** on the likelihood of choosing one type of healthcare provider over others.

### Data Source
The data used in this project is sourced from the **National Health Interview Survey (NHIS)** conducted between 2019 and 2022. The NHIS provides a comprehensive framework for compiling a wide range of health information in the U.S., making it a pivotal resource for assessing health trends across the nation.

### Model Description
A **Multinomial Logistic Regression Model** is employed in this analysis because the dependent variable—type of healthcare provider—is categorical with more than two levels. This type of model is particularly suited for scenarios where the outcome variables are nominal and categories are more than two. It helps in understanding how predictor variables (independent variables) affect the probability of each category of the outcome.

### Variables
The analysis includes a variety of predictor variables categorized as follows:

- **Demographic Factors**: Age, Sex, Race, and Marital Status.
- **Socioeconomic Status**: Employment status, Education level, and Income.
- **Health Status**: General health status, Presence of chronic ailments (like hypertension, diabetes), and Mental health status.
- **Insurance Status**: Type of health coverage (if any), which plays a critical role in healthcare provider choice.

### Data Query Tool
An interactive dropdown data query tool has been developed and can be viewed in the notebook `Dropdown_widget.ipynb`. This tool enables users to view trend lines in the usage of urgent care centers and emergency rooms based on the characteristics and variables mentioned above. It calculates the percentage of respondents from the total population interviewed in the National Health Interview Survey for individual years from 2019 to 2022 who reported at least one urgent care or emergency visit in the past 12 months. This functionality provides an insightful exploration into how different variables impact healthcare utilization trends over time.
