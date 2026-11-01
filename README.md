## Global Birth Registration Analysis

## Project Overview
This project analyzes birth registration data from the World Bank ID4D Global Dataset. The goal is to explore birth registration rates across different countries, years, and genders.

## Objectives
- Analyze birth registration rates across countries.
- Compare birth registration rates between males and females.
- Explore yearly birth registration trends.
- Calculate the percentage of unregistered children.
- Create an interactive Power BI dashboard.

## Dataset
- World Bank: Identification for Development (ID4D) Global Dataset

## Indicator:
- Children under age 5 whose births are registered
- Period: 2022–2024
- Coverage: 69 economies
- Frequency: Annual

The analysis focuses on the 'BIRTH_REG' indicator.

## Key Columns:
- REF_AREA_LABEL: Country
- SEX_LABEL: Gender
- TIME_PERIOD: Year
- OBS_VALUE: Birth registration rate (%)
- Unregistered_Children: Percentage of unregistered children

## Calculation
Unregistered_Children = 100 - OBS_VALUE

## Tools Used
- Python
- Pandas
- Matplotlib
- Google Colab
- Microsoft Power BI

## Dashboard Features
- Average Birth Registration (%)
- Average Unregistered Children (%)
- Birth Registration Rate by Country
- Birth Registration by Gender
- Yearly Birth Registration Trend
- Interactive Country and Year slicers


## Conclusion

Through this project, I gained practical experience in data cleaning, exploratory data analysis, data visualization, and dashboard development using Python and Power BI.
