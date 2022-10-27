## COMP90089 Group Project: Group 10 

In this project, we explored predicting hyperglycemic patient's length-of-stay in the ICU using classification algorithms, with navigations to the repository as follow:

- `data/`: preprocessed data based on `MIMIC-IV` databases. The files maybe empty to adhere to privacy practices.
- `models/`: Machine learning models used to preprocess/ predict label data, specifically
  - `kmean.ipynb`: used to convert continuous data to categorical data using `KMeans`.
  - `categorizer.ipynb`: used to convert continuous data to categorical data based on Medical studies.
  - `rf_model_imbalanced.ipynb`: `RandomForest` model used to predict on `hyperglycemic_patients` data without resampling data (and with imabalanced labels)
  - `rf_model_balanced.ipynb`: `RandomForest` model used to predict on `hyperglycemic_patients` data with SMOTE (Synthetic Minority Oversampling Technique) data labels.
- `preprocessing/`: Preprocessing data used to fetch data via Google Cloud BigQuery. With jupyter notebook copy on what's used via colab.
- `visualizations/`: contains programming copies of statistical visualizations and graphics used in the project report.
