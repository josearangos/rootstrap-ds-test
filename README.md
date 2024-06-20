# Rootstrap-ds-test

# Github solution => https://github.com/josearangos/rootstrap-ds-test/tree/main

[github](https://github.com/josearangos/rootstrap-ds-test/tree/main)
# Data Scientist Challenge

## Description of the problem

### About dataset

**Name**: Wine Quality, https://archive.ics.uci.edu/dataset/186/wine+quality 


Two datasets are included, related to red and white vinho verde wine samples, from the north of Portugal. 

#### Goal: 
Modeling wine quality based on physicochemical tests (see [Cortez et al., 2009], http://www3.dsi.uminho.pt/pcortez/wine/).


1. **Subject Area**: Business

2. **Dataset Characteristics**: Multivariate

3. **Associated Task**: Classification(chosen), Regression

4. **Feature Type**: Real

5. **number of instances**:red wine - 1599; white wine - 4898 = 6497 Instances

6. **number of features**: 11

7. **Has Missing Values?**: No

8. **Features**:

| Number | Variable Name          | Role    | Type        | Description              | Units | Missing Values |
|--------|------------------------|---------|-------------|--------------------------|-------|----------------|
| 1      | fixed_acidity          | Feature | Continuous  | Most acids in wine are fixed or non-volatile, meaning they do not evaporate readily.                          |       | no             |
| 2      | volatile_acidity       | Feature | Continuous  | The amount of acetic acid in wine; at high levels, it can impart an unpleasant vinegar taste.                         |       | no             |
| 3      | citric_acid            | Feature | Continuous  | Found in small quantities, citric acid can add freshness and flavor to wines.                        |       | no             |
| 4      | residual_sugar         | Feature | Continuous  | The amount of sugar remaining after fermentation stops; wines with less than 1 gram/liter are rare, while those with more than 45 grams/liter are considered sweet.                       |       | no             |
| 5      | chlorides              | Feature | Continuous  | The amount of salt in the wine.                         |       | no             |
| 6      | free_sulfur_dioxide    | Feature | Continuous  | The free form of SO₂ exists in equilibrium between molecular SO₂ (as a dissolved gas) and bisulfite ion; it prevents microbial growth and oxidation of wine.                        |       | no             |
| 7      | total_sulfur_dioxide   | Feature | Continuous  | The total amount of free and bound forms of SO₂; at low concentrations, SO₂ is mostly undetectable, but at free SO₂ concentrations over 50 ppm, it becomes noticeable in the nose and taste of wine.                         |       | no             |
| 8      | density                | Feature | Continuous  | The density of wine, which is close to that of water, depending on the alcohol and sugar content.                       |       | no             |
| 9      | pH                     | Feature | Continuous  | Describes how acidic or basic a wine is on a scale from 0 (very acidic) to 14 (very basic); most wines range between 3 and 4 on the pH scale.                          |       | no             |
| 10     | sulphates              | Feature | Continuous  | A wine additive that can contribute to sulfur dioxide (SO₂) levels, acting as an antimicrobial and antioxidant.                         |       | no             |
| 11     | alcohol                | Feature | Continuous  | The percentage of alcohol content in the wine.                        |       | no             |
| 12     | quality                | Target  | Integer     | Score between 0(very bad) and 10(excellent), output variable (based on sensory data  |       | no             |
| 13     | color                  | Other   | Categorical | red or white             |       | no             |



### About problem to solve

1. **Machine Learning problem**: Supervised Learning
2. **Type**: Classification
3. **Metric to optimize**: F1-Score
4. **Target**: quality  
    - bad < 5 (0)
    - good >=5 (1)

### References
#### Introductory Paper
Cortez, P., Cerdeira, A., Almeida, F., Matos, T., & Reis, J. (2009). Modeling wine preferences by data mining from physicochemical properties. Decision support systems, 47(4), 547-553.



# Setup project

1. conda create --name rootstrap-ds-test python=3.11 
2. conda activate rootstrap-ds-test
3. pip install -r requirements. txt


# About this project

1. data/ : All the datasets and the versions they have had, before and after the EDA, as some decisions made during the EDA altered the initial dataset. 
2. experiments/ : All artifacts generated during the experimentation phase (53 trainings) 
3. notebooks/: 
    - 1.Preprocess_dataset.ipynb: It includes all the code executed to generate the train and test sets.
    - 2.EDA.ipynb : It includes all the code used for the exploratory data analysis and the decisions made during the process.
    - 3.Experiments.ipynb: Includes all the code related to the experimentation phase.
4. notebooks/mlruns: All information about the best model from the experiments is saved in MLflow.

To view the MLflow UI, follow these steps:
- Navigate to the notebooks directory:

- cd notebooks/

- Start the MLflow server: mlflow server --host 127.0.0.1 --port 8080

- Open your browser and go to: http://127.0.0.1:8080

Note: Ensure MLflow is installed beforehand (pip install mlflow).




