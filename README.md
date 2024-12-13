# Global Health Statistics Analysis and Modeling

## Project Overview
This project explores global health statistics through an analysis of 1 million rows of data to understand the socioeconomic factors influencing disease prevalence and recovery rates. By cleaning the data, performing exploratory and clustering analyses, and building predictive models, the study uncovers insights into how factors such as urbanization, healthcare access, and economic conditions affect disease dynamics.

The notebook could not be uploaded to GitHub. However, you can access it on Kaggle through the following link: [https://www.kaggle.com/code/azhardaho/global-health-statistics-data-analysis-and-ml/edit].

---

## Problem Statement
The prevalence and recovery rates of diseases are influenced by a variety of factors, including economic, social, and environmental conditions. This project addresses the following key questions:

- What factors most significantly affect the prevalence and recovery rates of diseases?
- How can countries be grouped based on health statistics and socioeconomic factors?
- Can machine learning models accurately predict disease prevalence and recovery rates?

---

## Methodology

1. **Data Cleaning:**
   - Addressed mislabeling in disease categories (e.g., reclassifying COVID-19 as viral or respiratory instead of genetic) using domain knowledge.

2. **Exploratory Data Analysis (EDA):**
   - Visualized data with scatter plots, box plots, and heat maps.
   - Identified patterns through geographic visualizations that were not evident in raw correlations.

3. **Clustering Analysis:**
   - Applied clustering techniques to group countries based on health statistics and socioeconomic indicators.
   - Identified optimal clusters that reveal shared patterns among nations.

4. **Predictive Modeling:**
   - Built a Random Forest model to predict disease prevalence and recovery rates.
   - Extracted feature importance, identifying urbanization rate, mortality rate, affected population, average treatment cost, and healthcare access as key predictors.

---

## Key Findings

- **Urbanization and Disease Spread:**
  - Countries with higher urbanization rates (e.g., the United States, China) showed increased disease prevalence, suggesting a link between population density and disease spread.
  
- **Economic and Health Disparities:**
  - Nations with lower socioeconomic factors experienced higher disease prevalence and lower recovery rates, highlighting disparities in healthcare access.

- **Clustering Insights:**
  - Countries were grouped into clusters based on shared health and socioeconomic profiles, providing actionable insights for targeted interventions.

- **Model Insights:**
  - The Random Forest model revealed that urbanization rate, mortality rate, population affected, average treatment cost, and healthcare access are the most critical factors affecting disease dynamics.

---

## Challenges and Future Directions

### Challenges:
- The dataset's size (1 million rows) necessitated sampling, reducing the amount of data used for training models.
- Low initial correlations required advanced visualization techniques to uncover patterns.

### Future Improvements:
- **Feature Engineering:** Incorporate additional derived metrics to improve model accuracy.
- **Scalability:** Use advanced technology or distributed computing to process the full dataset.
- **Model Refinement:** Explore other machine learning techniques (e.g., gradient boosting, neural networks) for improved predictions.
