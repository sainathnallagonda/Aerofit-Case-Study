# Aerofit Case Study

## Problem Statement
The market research team at AeroFit wants to identify the characteristics of the target audience for each type of treadmill offered by the company, to provide better recommendations to new customers. The team aims to investigate whether there are differences across the products with respect to customer characteristics.

## Objectives
- Perform descriptive analytics to create a customer profile for each AeroFit treadmill product using tables and charts.
- Construct two-way contingency tables for each treadmill product and compute all conditional and marginal probabilities along with their business insights.

## Dataset
The dataset contains customer details related to treadmill purchases, including:
- **Product**
- **Age**
- **Gender**
- **Education**
- **Marital Status**
- **Usage (weekly)**
- **Fitness Score**
- **Income**
- **Miles (run per week)**

## Tools and Libraries Used
- **Python** (pandas, numpy, seaborn, matplotlib)
- **Data Cleaning** (Handling missing values, ensuring data integrity)
- **Exploratory Data Analysis** (Univariate and Bivariate analysis)
- **Statistical Analysis** (Probability calculations, contingency tables)

## Key Findings
- Customers prefer different treadmill models based on income levels and fitness scores.
- The **KP281 model** has the highest probability of purchase at **44%**, followed by KP481 at **33%**, and KP781 at **22%**.
- Male customers show a greater inclination towards high-end models like KP781.
- Conditional probabilities highlight gender-based differences in treadmill selection.

## Visualizations
Several plots and charts were generated to analyze data distribution:
- Product distribution, gender analysis, fitness trends.
- Box plots comparing age vs. usage, fitness vs. education.
- Contingency tables showcasing marginal and conditional probabilities.

## Conclusion
Understanding customer preferences allows AeroFit to better target their marketing strategies and product recommendations. This analysis offers valuable insights into purchasing patterns and demographic influences.

## Repository Contents
- `aerofit_treadmill.csv` – Dataset file.
- `aerofit_analysis.ipynb` – Jupyter notebook with full analysis.
- `README.md` – This file.

