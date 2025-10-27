<h1 align="center"> Data Pipeline Development </h1>
<p align="center"> <em>TechNest Task : 1 for Titanic Dataset </em></p>

---

<img width="1200" height="630" alt="image" src="https://github.com/user-attachments/assets/303999c6-e504-4153-b88c-e9b4a10eaf07" />

---

## Overview
A well-documented Jupyter Notebook project demonstrating robust **data cleaning**, **exploratory data analysis (EDA)**, and **preprocessing** to build a machine learning-ready dataset using the classic Titanic data.

## Table of Contents
- [Project Overview](#overview)
- [Dataset](#dataset)
- [Features & Workflow](#features--workflow)
- [Installation & Usage](#installation--usage)
- [Project Structure](#project-structure)
- [Results & Insights](#results--insights)
- [Next Steps](#next-steps)
- [Contributing](#contributing)
- [Contact](#contact)
- [License](#license)

***

## Dataset

**Source:** [Kaggle – Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset/data)

*Download the `titanic.csv` and place it in your working directory.*

***

## Features & Workflow

- **Comprehensive EDA**  
  Visualizations/statistics to explore distributions, missing values, and relationships to the target.

- **Data Cleaning & Preprocessing:**  
  - Missing value imputation (median/mode).
  - Dropping irrelevant/excessive-missing columns (`Cabin`, `Ticket`, `PassengerId`, `Name`).
  - Encoding categorical features (mapping, one-hot).

- **Preprocessing Pipeline:**  
  Separate pipelines for numeric & categorical columns, integrated via `ColumnTransformer`.

- **Output:**  
  Processed CSV (`titanic_advanced_prepared.csv`), ready for ML models.

***

## Installation & Usage

**1. Clone this repository or download the notebook and dataset.**  
**2. Download Titanic CSV (`titanic.csv`) from Kaggle and place it in the repo folder.**  
**3. Run the Jupyter Notebook (`Data_Pipeline_Development.ipynb`) step-by-step.**  
**4. The processed dataset is saved as `titanic_advanced_prepared.csv`.**  
**5. Train ML models (e.g., Logistic Regression, Random Forest) on the output data.**

### Requirements

- Python 3.7+
- Jupyter Notebook
- pandas, numpy, matplotlib, seaborn, scikit-learn

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

***

## Project Structure

```
├── titanic.csv                 # Raw dataset (from Kaggle)
├── Data_Pipeline_Development.ipynb   # Preparation notebook
├── titanic_advanced_prepared.csv     # ML-ready output
└── README.md                   # This documentation
```

***

## Results & Insights

- Full data cleaning/preprocessing steps
- EDA with visual summaries (see notebook for matplotlib/seaborn plots)
- Well-prepared dataset with categorical encoding and imputation
- Useful for building ML models for Titanic survival prediction

***

## Next Steps

- Use this pipeline as a template for other tabular ML projects
- Extend analysis: Feature engineering, model training, hyperparameter tuning
- Integrate with cloud workflow (e.g., Google Colab, AWS S3) if needed

## Contributing

Issues, discussions, and pull requests are welcome!  
Open [issues](https://github.com/Kanakbaghel/Data_Pipeline_Development/issues) for suggestions or bugs.

***

## Contact

For questions or feedback, open an issue or contact [Kanakbaghel](https://github.com/Kanakbaghel).

***

## License

This project is available under the MIT License.


> <h3 style="color: #8B7D8B;">Built with persistence and curiosity</h3>

----------

<p align="center"><em>Crafted with ♥ by <strong>Kanak Baghel</strong> | <a href="https://www.linkedin.com/in/kanakbaghel">LinkedIn</a></em></p>

---
