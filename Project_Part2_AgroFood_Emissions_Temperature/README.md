# Predicting Temperature Rise: A Machine Learning Model Comparison

## Report  
View report here -  
(https://nbviewer.org/github/Rahil-An-Analyst/Machine-Learning/blob/main/Project_Part2_AgroFood_Emissions_Temperature/MLProject_part2.ipynb)

## Overview  
This project focuses on building and comparing binary classification models to predict whether the average temperature rise for a country in a given year is above or below the mean temperature rise. The analysis is based on the Agri-food CO2 emission dataset from Kaggle (Alessandro L B, n.d.), which includes various environmental factors and emission-related attributes. The goal is to classify the temperature rise using KNN, Naive Bayes, Decision Tree, and Neural Networks, with hyperparameter tuning for optimized performance.

## Objectives  
-- Transform the dataset into a binary classification problem.  
-- Build and evaluate three traditional binary classifiers (KNN, Naive Bayes, and Decision Tree) and a Neural Network.  
-- Compare model performance based on accuracy, precision, recall, and AUC.  
-- Conduct statistical tests to evaluate the significance of performance differences.  

## Data Description  
-- **Data Source**: Kaggle (Alessandro L B, n.d.) - AgroFood CO2 Emission Dataset.  
-- **Target Variable**: Average temperature rise with two classes:  
  -- `<= mean temp rise (0.9°C)`  
  -- `> mean temp rise (0.9°C)`  
-- **Descriptive Features**:  
  -- CO2 emissions from 19 Agri-food activities.  
  -- Total CO2 emissions.  
  -- Urban population.  
  -- Region and year.  

## Methodology  
-- **Data Preprocessing**: Cleaning the dataset, handling missing values, normalizing features, and transforming the target variable into two classes.  
-- **Model Building**:  
  -- **K-Nearest Neighbors (KNN)**: Hyperparameter tuning using grid search and cross-validation.  
  -- **Naive Bayes (NB)**: Model building with Gaussian assumptions.  
  -- **Decision Tree (DT)**: Hyperparameter tuning for depth and splits.  
  -- **Neural Network (NN)**: Setup, training, and optimization for classification tasks.  
-- **Model Evaluation**:  
  -- Use of 5-fold cross-validation to evaluate models.  
  -- Metrics: Accuracy, precision, recall, F1 score, and AUC.  
  -- Paired t-tests to assess the statistical significance of differences between models.  

## Results  
-- **KNN**: Achieved the highest AUC score of 0.731, making it the best performer for distinguishing between high and low temperature rise classes.  
-- **Decision Tree**: Competitive performance with an AUC score of 0.696, providing balanced precision and recall.  
-- **Naive Bayes**: Lowest AUC score (0.532), but good recall for predicting stable temperature periods.  
-- **Neural Network**: Achieved an AUC score of 0.65, offering balanced precision and recall for complex environmental patterns.  

## How to Use  
-- **Setup**: Requires Python and relevant packages (`pandas`, `scikit-learn`, `tensorflow`, etc.).  
-- **Usage**: Run `Binary_Classification_AgroFood.ipynb` to preprocess data, train models, and evaluate performance. Ensure the dataset `agrofood_emissions.csv` is placed in the correct directory before running.  

## Files  
-- `README.md`: This file.  
-- `MLProject_part2.ipynb`: Jupyter Notebook for binary classification and model evaluation.  
-- `MLProject_part2.csv`: The dataset used for analysis.  

## License  
This project is licensed under the MIT License.

## Contact  
For more information, please contact [Mohammad Rahil](mailto:smrahil98@gmail.com).
