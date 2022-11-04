## COMP90089 Group Project: Group 10 

In this project, we explored predicting hyperglycemic patient's length-of-stay in the ICU using classification algorithms, with navigations to the repository as follow:

- `data/`: preprocessed data based on `MIMIC-IV` databases. The files maybe empty to adhere to privacy practices.
- `models/`: Machine learning models used to preprocess and predict label data, specifically
  - `kmean.ipynb`: used to convert continuous data to categorical data using `KMeans`.
  - `categorizer.ipynb`: used to convert continuous data to categorical data based on Medical studies.
  - Random Forest Model
    - `rf_model_imbalanced.ipynb`: `RandomForest` model used to predict on `hyperglycemic_patients_w_bin_categories` data without resampling data (and with imabalanced labels)
    - `rf_model_balanced.ipynb`: `RandomForest` model used to predict on `hyperglycemic_patients_w_bin_categories` data with SMOTE (Synthetic Minority Oversampling Technique) data labels.
  - Logistic Regression Model
    - `logistic_regression_imbalanced.ipynb`: `LogisticRegression` model used to predict on `hyperglycemic_patients_w_bin_categories` data without resampling data (and with imabalanced labels)
    - `logistic_regression_balanced.ipynb`: `LogisticRegression` model used to predict on `hyperglycemic_patients_w_bin_categories` data with SMOTE (Synthetic Minority Oversampling Technique) data labels.
  - Naive Bayes
    - `nb_model_imbalanced.ipynb`: `GaussianNB` model used to predict on `hyperglycemic_patients_w_bin_categories` data without resampling data (and with imabalanced labels)
    - `nb_model_balanced.ipynb`: `GaussianNB` model used to predict on `hyperglycemic_patients_w_bin_categories` data with SMOTE (Synthetic Minority Oversampling Technique) data labels.
- `preprocessing/`: Preprocessing data used to fetch data via Google Cloud BigQuery. This is a jupyter notebook copy on what's executed via colab.
- `visualizations/`: contains programming copies of statistical visualizations and graphics used in the project report.


Also note that all preprocess data under `/data` has removed to adhere standard data privacy practices.