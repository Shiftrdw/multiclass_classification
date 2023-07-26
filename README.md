### Overview
This repository contains a Python implementation of a fetal health multiclass classification task. The project leverages machine learning tools such as Scikit-learn (sklearn) and XGBoost to analyze and predict fetal health outcomes based on a series of biomedical predictors.

The objective of this project is to develop a predictive model that can accurately classify fetal health into three categories: Normal, Suspect, and Pathological.

#### Data
The dataset used in this project consists of biomedical features of several fetal heart rate (FHR) metrics. The original dataset can be found at UCI Machine Learning Repository.

Each row in the dataset corresponds to a single examination, with a series of measurements related to the fetal heart rate (FHR) and uterine contraction (UC) features. The 'fetal_health' column contains the outcome, which is a multiclass target variable representing three categories of fetal health:

We implemented a custom multiclass classification model and boosting done using the XGBoost library. The model's hyperparameters are tuned using sklearn's GridSearchCV. Model performance is evaluated using multiclass classification metrics such as the confusion matrix, precision, recall, and F1 score.

#### Usage
`pip install -r requirements.txt`

#### Contributing
Contributions to this project are welcome. Please feel free to fork the repository and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

#### License
This project is licensed under the MIT License. See the LICENSE file for details.