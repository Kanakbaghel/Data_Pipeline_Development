<h1 align="center"> Data Pipeline Development </h1>
<p align="center"> <em>TechNest Task : 1 for Titanic Dataset </em></p>

---

<img width="1200" height="630" alt="image" src="https://github.com/user-attachments/assets/303999c6-e504-4153-b88c-e9b4a10eaf07" />

---

This repository contains a Jupyter Notebook for preparing the Titanic dataset. The notebook demonstrates robust data cleaning, exploratory data analysis (EDA), and preprocessing to produce a clean, model-ready dataset.

---

## Dataset

The Titanic dataset used in this project is sourced from Kaggle:

[Titanic Dataset on Kaggle](https://www.kaggle.com/datasets/yasserh/titanic-dataset/data)

Make sure to download the `titanic.csv` file and place it in the working directory before running the notebook.

---

## Features of the Notebook

- **Comprehensive Exploratory Data Analysis (EDA):**  
  Visualizations and statistics to understand data distributions, missing values, and relationships with the target variable.

- **Data Cleaning and Preprocessing:**  
  - Handling missing values with median and mode imputation.  
  - Dropping columns with excessive missing data (`Cabin`) and irrelevant features (`Ticket`, `PassengerId`, `Name`).  
  - Encoding categorical variables using mapping and one-hot encoding.

- **Robust Preprocessing Pipeline:**  
  Separate pipelines for numeric and categorical features with imputation and encoding, integrated via `ColumnTransformer`.

- **Output:**  
  A fully processed, encoded dataset saved as `titanic_advanced_prepared.csv` ready for machine learning modeling.

---

## How to Use

1. **Clone the repository** or download the notebook and dataset.

2. **Download the Titanic dataset CSV** from Kaggle and place it in the same directory as the notebook, named `titanic.csv`.

3. **Open and run the Jupyter Notebook** (`titanic_data_preparation.ipynb`) step-by-step to perform data preparation.

4. **Processed data output:**  
   After running, the notebook saves the processed dataset as `titanic_advanced_prepared.csv`.

5. **Next steps:**  
   Use the prepared dataset for training machine learning models such as Logistic Regression, Random Forest, or XGBoost.

---

## Requirements

- Python 3.7+
- Jupyter Notebook
- Libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn

Install required packages via pip if needed:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## Project Structure

```
.
├── titanic.csv                      # Raw Titanic dataset CSV (download from Kaggle)
├── titanic_data_preparation.ipynb  # Jupyter Notebook with data preparation
├── titanic_advanced_prepared.csv   # Processed dataset output by the notebook
└── README.md                       # This file
```

---

## Contact

For questions or suggestions, feel free to open an issue or contact me.

---

## License

This project is open source and available under the MIT License.
