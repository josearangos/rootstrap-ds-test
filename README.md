# Rootstrap-ds-test


[github](https://github.com/josearangos/rootstrap-ds-test/tree/main)

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
    - bad < 5
    - good >=5

### References
#### Introductory Paper
Cortez, P., Cerdeira, A., Almeida, F., Matos, T., & Reis, J. (2009). Modeling wine preferences by data mining from physicochemical properties. Decision support systems, 47(4), 547-553.





> **Note**: Code must be develop using **Python** and shared in **github**.

> **Note**: **jupyter** notebook should be used for exploratory data analysis (**EDA**).

---

In this challenge you will have to **run 2 machine learning** models that solve a problem you'll define from ONE of the provided data sets you will choose and then compare the results.

Keep in mind that the main goal of this challenge is not to get good performance on the models, but rather to validate the process you follow to solve the problem.

#### Tasks you'll need to perfom:
1. From ONE of the provided data sets below, you must define a problem to solve with supervised learning, specify the target variable and the metric to be used.
2. Perform an exploratory data analysis (EDA) on the data. During the analysis, make decisions about how the data will be processed, identifying transformations to be carried out during the preparation of the data.
3. Develop the code to execute the preparation of the data and then execute the models.
4. Evaluate the models and stablish a comparison between them.
5. Identify problems that the models have and mention how they could be solved to improve the result.

#### Output expected:
Github repo including:
1. Readme with decisions made
2. Code developed to resolve challenge
3. Include jupyter notebook inside the repo

#### Possible Datasets to be used for the challenge, you should choose ONLY 1:
- [Cars Dataset](https://data.world/dataman-udit/cars-data)
- [US International Air Traffic Dataset](https://www.kaggle.com/datasets/parulpandey/us-international-air-traffic-data)
- [World Happiness Dataset](https://www.kaggle.com/datasets/unsdsn/world-happiness)
- [The Boston Housing Dataset](https://www.cs.toronto.edu/~delve/data/boston/bostonDetail.html)
- [Wine Quality Dataset](https://archive.ics.uci.edu/ml/datasets/wine+quality)



Steps to show experiments on MLFLO


1. cd notebooks

2. mlflow server --host 127.0.0.1 --port 8080