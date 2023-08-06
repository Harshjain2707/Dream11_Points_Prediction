# Dream11 Points Prediction

Welcome to the repository that documents the creation of a predictive model for estimating Dream-11 fantasy cricket points through the application of Data Science and Analytics. This README provides an overview of the project, its objectives, and the structure of the included notebooks.

## Abstract
In the dynamic landscape of digital technology and the escalating allure of sports, Fantasy Sports Platforms (FSPs) have redefined user engagement. Leveraging the omnipresence of Data Science and Analytics, this project endeavors to elevate the fantasy sports experience by introducing a predictive model that anticipates player performance in upcoming games. The ultimate aspiration is to empower users with precise insights for informed decision-making. The project centers on the widely-acclaimed FSP, Dream-11, and aims to bolster the probability of achieving substantial wins.
## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install requirements.txt.

```bash
pip install -r requirements.txt
```

## Notebooks

### [YAML_TO_CSV.ipynb](Notebooks/YAML_TO_CSV.ipynb):
* Objective: This notebook initiates the journey by converting match data from cricsheet.org's YAML format into practical CSV files.
* Data Preparation: YAML files are transmuted into usable CSV tables, unlocking crucial batting and bowling statistics.
* Acknowledgment: The esteemed contribution of Tinniam V Ganesh's 'yorkpy' package is recognized for aiding in the transformation of YAML data.
### [Model_based_on_Research_Paper.ipynb](Notebooks/Model_based_on_Research_Paper.ipynb):
* Objective: This notebook meticulously outlines the construction of the predictive model as inspired by a relevant research paper.
* Libraries and Exploration: Essential libraries are imported, and the merged batting and bowling CSV files are loaded for analysis.
* Data Preprocessing: Thorough data preprocessing is executed, encompassing data type conversion, handling missing values, and feature engineering.
* Model Selection and Evaluation: The notebook delves into model selection using the PyCaret library. Regression models are scrutinized based on R2 scores, with an emphasis on avoiding overfitting.
### [Model_with_5_features.ipynb](Notebooks/Model_with_5_features.ipynb):
* Objective: This notebook experiments with a streamlined approach, utilizing a concise set of input features to achieve predictions.
* Input Selection: The rationale behind the choice of ['Player', 'MF', 'team1', 'team2', 'venue'] as input features is elucidated.
* Model Training: The PyCaret library is harnessed again to train regression models, accompanied by a detailed examination of R2 scores.
### [Model_with_2_features.ipynb](Notebooks/Model_with_2_features.ipynb):
* Objective: This notebook presents an innovative strategy, focusing on player performance at specific venues.
* Data Analysis: Grouping data by venue and calculating average Dream-11 points provide unique insights into player dynamics.
* Modeling Approach: Leveraging the PyCaret library, regression models are constructed with a specialized input set, complemented by comprehensive R2 score discussions.

## Abstracting Insights
This repository encapsulates a comprehensive journey through the realm of fantasy cricket points prediction. From the inception of data conversion to the intricate process of model development and evaluation, each notebook demystifies a crucial facet. This documentation not only equips enthusiasts with the tools to delve into predictive analytics but also serves as a testament to the transformative power of Data Science and Analytics in the domain of sports and user engagement.

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.
