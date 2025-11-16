# Credit Classification

Supervised learning project for predicting credit default outcomes from customer and loan characteristics.

## Project overview

This project builds and evaluates classification models for credit risk:
- Exploratory data analysis of the input dataset
- Feature engineering and data preprocessing
- Training baseline and regularised models (for example logistic regression and tree-based methods)
- Evaluation using metrics such as ROC-AUC, precision, recall and confusion matrices

Originally developed as part of a university coursework, the repository is structured as a standalone, reproducible machine learning project.

## Repository structure

- `src/` – Python modules for data preparation, model training and evaluation
- `notebooks/` – Jupyter notebooks for exploration and experimentation
- `data/` – Raw and processed data (not stored in the repo)
- `report/` – Final written report for the project
- `docs/` – Coursework brief and additional documentation
- `requirements.txt` – Python dependencies
- `.gitignore` – Files and folders excluded from version control

## How to run

1. Clone the repository:

   git clone git@github.com:abailey81/Credit-Classification.git  
   cd Credit-Classification

2. (Optional) Create and activate a virtual environment.

3. Install dependencies:

   pip install -r requirements.txt

4. Run a training script (once scripts are added under `src/`):

   python -m src.train_model

   or open a notebook from `notebooks/` to reproduce the analysis.

## Results

The final model performance, analysis and discussion are documented in the report PDF under `report/` (to be added).
