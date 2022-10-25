## COMP90089 Group Project: Group 10 

In this project, we explored predicting hyperglycemic patient's length-of-stay in the ICU using classification algorithms, with navigations to the repository as follow:

- `data/`: preprocessed data based on `MIMIC-IV` databases
- `models/`: Machine learning models used to preprocess/ predict label data, specifically
  - `kmean.ipynb`: used to convert continuous data to categorical data using `KMeans`.
  - `rf_model_imbalanced`: `RandomForest` model used to predict on `hyperglycemic_patients` data without resampling data (and with imabalanced laebls)
- `preprocessing/`: Preprocessing data used to fetch data via Google Cloud BigQuery. With jupyter notebook copy on what's used via colab.
- `visualizations/`: contains programming copies of statistical visualizations and graphics used in the project report.
