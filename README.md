# Capstone Project: Sustainable Development Goals (SDGs)

## Project Title: Understanding Factors Influencing Life Expectancy and Implications in Southeast Asia

### Table of Contents
- [Introduction](#introduction)
- [Dataset Description](#dataset-description)
- [Problem Statement](#problem-statement)
- [Data Cleaning and Transformation](#data-cleaning-and-transformation)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Interpretation and Recommendations](#interpretation-and-recommendations)
- [Conclusion](#conclusion)

## Introduction
This project aims to address the disparity in life expectancy across different countries, particularly in Southeast Asia, and its association with health service coverage and disease prevalence. By understanding these factors, strategies can be proposed to improve overall life expectancy in the region.

## Dataset Description
This capstone project uses the "World Health Statistics" dataset from World Development Indicators (WDI). This dataset contains information about various health indicators from different countries, including life expectancy, mortality rates, disease prevalence, and health service coverage.

**Source:** The World Development Indicators (WDI)

**Key Features:**
- **Country:** Name of the country
- **Year:** Year of the data
- **Life Expectancy:** Average life expectancy at birth
- **Mortality Rate:** Mortality rate per 1000 live births
- **Prevalence:** Prevalence of certain factors (Malaria, Tobacco, Undernourishment)
- **Health Service Coverage:** Coverage of essential health services

## Problem Statement
The problem addressed is the disparity in life expectancy across different countries and its association with health service coverage and disease prevalence. The goal is to understand the factors contributing to lower life expectancy in certain regions and propose strategies to improve overall life expectancy.

**Importance:**
Addressing this problem is crucial for achieving SDG 3 (Good Health and Well-being) because improving life expectancy is a key indicator of overall health and well-being. By identifying and addressing the factors that negatively impact life expectancy, the project can contribute to better health outcomes globally.

## Data Cleaning and Transformation
**Initial State of Dataset:**
- **Missing Values:** Some countries may have missing data for certain years.
- **Data Types:** Ensuring all columns have appropriate data types (e.g., numerical for health indicators and year).

**Data Cleaning Steps:**
- Handling Missing Values: Impute missing values or remove rows/columns with excessive missing data.
- Correcting Data Types: Ensure all columns have the correct data type.

**Data Transformation Steps:**
- Creating New Variables: Calculate additional indicators, such as the ratio of health service coverage to prevalence.
- Aggregations: Aggregate data to get country-level averages over certain periods.

## Exploratory Data Analysis (EDA)

### Visualization and Insights:

1. **Life Expectancy: Average life expectancy at birth**
   - **Description:** Life expectancy at birth is a statistic that tells us the average number of years a newborn baby is expected to live if the current conditions affecting health and mortality (death rates) stay the same throughout their life.
   - **Example:**
     - High Life Expectancy: If the life expectancy is 80 years, it means that on average, a baby born today can expect to live until they are 80 years old.
     - Low Life Expectancy: If the life expectancy is 60 years, it suggests that there are more health challenges and lower living standards.

2. **Mortality Rate: Mortality rate per 1000 live births**
   - **Description:** The mortality rate per 1000 live births is a way to measure how many babies die before their first birthday out of every 1000 babies born alive in a year.
   - **Example:**
     - High Mortality Rate: If a country has a high mortality rate, such as 50 deaths per 1000 live births, it suggests significant challenges in healthcare and living conditions that need to be addressed.
     - Low Mortality Rate: A low mortality rate, such as 5 deaths per 1000 live births, indicates better healthcare services and healthier living conditions.

3. **Prevalence: Prevalence of Tobacco**
   - **Description:** The prevalence of current tobacco use is a measure that tells us the percentage of adults who currently use tobacco products, such as cigarettes, cigars, pipes, or smokeless tobacco.
   - **Example:**
     - High Prevalence: If the prevalence of current tobacco use is 30%, it means that 30 out of every 100 adults are currently using tobacco.
     - Low Prevalence: If the prevalence is 10%, only 10 out of every 100 adults are currently using tobacco.

4. **Prevalence: Prevalence of Undernourishment**
   - **Description:** The prevalence of undernourishment is a measure that tells us the percentage of people in a population who do not have enough food to meet their daily energy requirements.
   - **Example:**
     - High Prevalence: If the prevalence of undernourishment is 30%, it means that 30 out of every 100 people in the population do not have enough food.
     - Low Prevalence: If the prevalence is 5%, only 5 out of every 100 people are undernourished.

5. **Prevalence: Prevalence of Malaria**
   - **Description:** The incidence of malaria is a measure that tells us how many new cases of malaria occur in a population that is at risk of contracting the disease within a specific time period, usually a year. It is expressed per 1,000 people at risk.
   - **Example:**
     - High Incidence: If the incidence of malaria is 50 per 1,000 population at risk, it means that out of every 1,000 people living in an area where malaria is present, 50 people get malaria in a year.
     - Low Incidence: If the incidence is 5 per 1,000 population at risk, only 5 people out of every 1,000 at risk get malaria in a year.

6. **Health Service Coverage: Coverage of essential health services**
   - **Description:** The UHC (Universal Health Coverage) service coverage index is a measure that evaluates how well a country is providing essential health services to its population. It reflects the extent to which people have access to the healthcare they need without suffering financial hardship.
   - **Example:**
     - High UHC Service Coverage Index: If a country has an index score of 80, it means that a significant portion of its population has access to essential health services.
     - Low UHC Service Coverage Index: If the score is 40, it suggests that many people in the country struggle to get the healthcare they need.

## Interpretation and Recommendations
**Connecting Visualizations to Problem Statement:** The EDA will show how factors like health service coverage and disease prevalence impact life expectancy. For example, a strong positive correlation between health service coverage and life expectancy suggests that improving healthcare access is crucial.

**Implications for SDG:** Findings can inform policy decisions, such as increasing investment in healthcare infrastructure in regions with low life expectancy.

**Recommendations:**
- **Increase Healthcare Funding:** Allocate more resources to regions with poor health indicators.
- **Disease Prevention Programs:** Implement programs targeting high-prevalence diseases like malaria.
- **Improve Data Collection:** Enhance data collection efforts to better track health indicators such as Prevalence of Undernourishment and Prevalence of Tobacco.
- **Nutritional Education Programs:** Develop and implement educational initiatives focused on improving nutrition and reducing undernourishment rates.
- **Tobacco Control Initiatives:** Introduce comprehensive tobacco control measures including awareness campaigns, smoking cessation programs, and policies aimed at reducing tobacco use prevalence.

## Conclusion
By analyzing the factors influencing life expectancy, this project provides valuable insights into how health service coverage, disease prevalence, undernourishment, and tobacco use impact life expectancy. These findings can guide policymakers in making informed decisions to improve health outcomes and achieve the Sustainable Development Goals.

---



