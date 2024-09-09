# AgroFood CO2 Emissions and Temperature Rise: Data Cleaning and Exploration

## Report
View report here -  
(https://nbviewer.org/github/rahilprime/Machine-Learning/blob/main/Project_Part1_AgroFood_Emissions_Temperature/MLProject_part1.ipynb)

## Overview
This project aims to perform data preparation and exploratory analysis on emissions from agri-food activities and their relationship with global temperature rise. The goal is to clean the dataset and analyze the impact of emissions from different sources on temperature escalation across countries.

## Objectives
- Prepare and clean the dataset for further analysis.
- Perform exploratory data analysis (EDA) to identify trends and correlations between emissions and temperature rise.
- Extract meaningful insights for future modeling efforts.

## Data Description
- **Data Source**: Kaggle (Alessandro, 2024) - AgroFood CO2 Emission Dataset.
- **Filtered Columns**:
  - **Area**: Country or region.
  - **Year**: Year of observation.
  - **CO2 Emissions**: Emissions from 19 different agri-food activities.
  - **Urban Population**: Number of people living in urban areas.
  - **Rural Population**: Number of people living in rural areas.
  - **Total Population**: Total population by gender.
  - **Average Temperature**: The target variable, representing annual temperature rise (in °C).
- **Filtered Observations**: 6,965 rows with data from 1990 to 2020.

## Methodology
- **Data Cleaning**: Handling missing data, formatting columns, and applying transformations where necessary.
- **Exploratory Data Analysis (EDA)**:
  - **Univariate**: Understanding individual feature distributions.
  - **Bivariate**: Analyzing relationships between CO2 emissions, population, and temperature rise.
  - **Trivariate**: Examining the combined effect of multiple features on temperature rise.
  
## Results
Key insights from the exploratory analysis include:
- Strong linear relationships between total CO2 emissions and temperature rise.
- Industrial processes and urban population are major contributors to temperature escalation.
- Europe has seen the highest temperature rise, while Southern Asia has experienced the least.

## How to Use
- **Setup**: Requires Python and relevant packages (`pandas`, `matplotlib`, `seaborn`, etc.).
- **Usage**: Run `DataPrep_Exploration.ipynb` to clean the dataset and generate exploratory visualizations. Ensure the dataset `agrofood_emissions.csv` is placed in the correct directory before running.

## Files
- `README.md`: This file.
- `DataPrep_Exploration.ipynb`: Jupyter Notebook containing code for data preparation and EDA.
- `agrofood_emissions.csv`: The dataset used for analysis.

## License
This project is licensed under the MIT License.

## Contact
For more information, please contact [Mohammad Rahil](mailto:smrahil98@gmail.com).
