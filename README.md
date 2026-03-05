# Income Inequality Econometrics Model

## Project Overview

This project investigates the economic factors that influence income inequality using econometric modeling techniques. The primary objective is to analyze how variables such as education levels, economic development, and unemployment affect income inequality across an economy.

Income inequality is a central topic in economics and public policy. Economists frequently use statistical and econometric tools to understand the determinants of inequality and evaluate potential policy interventions. This project demonstrates how econometric methods can be applied to analyze these relationships.

The analysis combines theoretical reasoning from economics with empirical modeling using regression techniques.

---

## Research Objective

The objective of this project is to explore the determinants of income inequality and demonstrate how econometric models can be used to estimate relationships between economic variables.

Specifically, the project examines the relationship between:

* Education levels
* Economic development (GDP)
* Unemployment rates
* Income inequality (measured using the Gini coefficient)

By estimating econometric models, the project illustrates how these factors may influence inequality outcomes.

---

## Economic Background

Income inequality refers to the unequal distribution of income across individuals or households in an economy. One of the most widely used measures of inequality is the **Gini coefficient**, which ranges from 0 (perfect equality) to 100 (maximum inequality).

Economic theory suggests several key determinants of inequality:

### Education

Higher levels of education tend to improve labor productivity and income opportunities. Increased educational attainment may reduce inequality by allowing more individuals to access higher-paying jobs.

### Economic Development

Economic growth and development can influence income distribution in complex ways. In some cases, growth may initially increase inequality before eventually reducing it.

### Unemployment

High unemployment levels often increase income inequality by reducing income opportunities for certain segments of the population.

This project explores these relationships using an econometric regression framework.

---

## Econometric Model

The relationship between inequality and the explanatory variables is estimated using a multiple linear regression model.

The general econometric specification is:

Gini = β₀ + β₁(Education) + β₂(GDP) + β₃(Unemployment) + ε

Where:

* **Gini** represents the income inequality index.
* **Education** represents average years of schooling or education levels.
* **GDP** represents economic development.
* **Unemployment** represents the unemployment rate.
* **ε** represents the error term.

The model is estimated using **Ordinary Least Squares (OLS)** to determine the magnitude and direction of these relationships.

---

## Methodology

The project follows the following analytical steps:

1. **Data Preparation**

   A dataset is constructed containing observations for the key variables:

   * Gini coefficient
   * Education levels
   * GDP
   * Unemployment rate

2. **Exploratory Data Analysis**

   The data is visualized to understand relationships between variables, particularly the relationship between education and income inequality.

3. **Econometric Estimation**

   A multiple regression model is estimated to quantify how education, GDP, and unemployment influence income inequality.

4. **Interpretation of Results**

   The estimated coefficients are interpreted in the context of economic theory to determine whether the results align with expected economic relationships.

---

## Tools and Technologies

This project was implemented using the following tools:

* Python
* Google Colab
* Pandas (data manipulation)
* Statsmodels (econometric modeling)
* Matplotlib (data visualization)

These tools allow the implementation of statistical models and graphical analysis within a reproducible computational environment.

---

## Key Variables Used

| Variable     | Description               |
| ------------ | ------------------------- |
| Gini         | Income inequality index   |
| Education    | Average education level   |
| GDP          | Economic output indicator |
| Unemployment | Unemployment rate         |

---

## Results and Interpretation

The regression model estimates the relationship between the explanatory variables and income inequality.

The estimated coefficients provide insights into:

* Whether higher education levels are associated with lower inequality.
* How economic development relates to inequality levels.
* Whether higher unemployment contributes to greater income disparities.

These results illustrate how econometric tools can be used to test economic hypotheses and interpret relationships between macroeconomic variables.

---

## Project Structure

income-inequality-econometrics-model

├── income-inequality-econometrics-model.ipynb
└── README.md

The notebook file contains the full analysis including:

* Data creation and preparation
* Visualization
* Econometric estimation
* Interpretation of results

---

## Learning Outcomes

This project demonstrates the application of several important concepts in economics and econometrics:

* Multiple regression modeling
* Empirical testing of economic relationships
* Interpretation of econometric results
* Use of computational tools for economic analysis

It also illustrates how theoretical economic ideas can be translated into empirical models using data.

---

## Note

This project was developed as part of an academic learning exercise to demonstrate econometric modeling techniques and analytical workflows. The dataset used in the analysis is a simplified illustrative dataset designed to demonstrate the methodology.
