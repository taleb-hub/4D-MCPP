# 4D-MCPP

ML model for Macrocycle permeability prediction, involving molecular descriptor analysis, feature selection, model development, and performance evaluation.

<!-- Optional: Add project badges here -->

## 1. Project Overview

Describe the project, the problem being addressed, and the general approach used to solve it.

## 2. Problem Statement

- What problem are you trying to solve?
- Why is this problem important?
- What is the expected outcome?

## 3. Project Objectives

- Explore and understand the dataset.
- Perform data preprocessing and feature analysis.
- Experiment with different model architectures.
- Identify the best-performing approach.
- Evaluate the final selected model.

## 4. Dataset Description

Describe the dataset, its source, size, features, and target variable.

### Dataset Splits

| Dataset | Description |
|---|---|
| Training | Used for model training |
| Validation | Used for model selection and tuning |
| Testing | Used for final evaluation |


## 5. Repository Structure


## Repository Structure

```text
Macrocycle-Permeability-Prediction/
│
├── data/
│   ├── raw/                         # Original dataset
│   └── processed/                   # Processed and split datasets
│       ├── train.csv
│       ├── validation.csv
│       └── test.csv
│
├── notebooks/
│   ├── 01_exploratory_data_analysis.ipynb
│   ├── 02_data_preprocessing.ipynb
│   ├── 03_feature_selection.ipynb
│   ├── 04_model_experiments.ipynb
│   ├── 05_final_model_training.ipynb
│   └── 06_model_evaluation.ipynb
│
├── src/
│   ├── data_processing.py
│   ├── feature_selection.py
│   ├── model_training.py
│   ├── evaluation.py
│   └── utils.py
│
├── models/
│   ├── best_model.pkl
│   └── model_config.json
│
├── reports/
│   ├── figures/
│   │   ├── feature_importance.png
│   │   ├── model_comparison.png
│   │   └── confusion_matrix.png
│   │
│   └── results/
│       ├── model_comparison.csv
│       └── evaluation_metrics.json
│
├── README.md
├── requirements.txt
├── .gitignore
├── LICENSE
└── DATA_LICENSE.md
```

### Directory and File Descriptions

| Directory / File | Description |
|---|---|
| `data/raw/` | Original dataset |
| `data/processed/` | Cleaned and split datasets |
| `notebooks/` | Jupyter notebooks documenting the complete workflow |
| `src/` | Reusable Python functions and modules |
| `models/` | Best-performing trained model and configuration |
| `reports/figures/` | Visualizations and evaluation plots |
| `reports/results/` | Experiment comparisons and evaluation metrics |
| `requirements.txt` | Python dependencies |
| `.gitignore` | Files and directories excluded from Git |
| `LICENSE` | MIT License for original project code |
| `DATA_LICENSE.md` | Original dataset licensing and attribution information |

## 6. Methodology

Describe the overall workflow:

1. Exploratory Data Analysis
2. Data Preprocessing
3. Feature Selection
4. Model Experimentation
5. Final Model Training
6. Model Evaluation

## 7. Model Experiments

Describe the different models and architectures investigated.

Explain the evaluation criteria and model selection strategy.

## 8. Results and Evaluation

Present the comparison of candidate models.

| Model | Accuracy | Precision | Recall | F1-score |
|---|---|---|---|---|
| Model 1 | - | - | - | - |
| Model 2 | - | - | - | - |
| Best Model | - | - | - | - |

### Performance Visualizations

Add important figures from reports/figures/.

### Final Evaluation

Discuss the final model's performance on the test set.

## 9. Installation and Requirements

Clone the repository:

    git clone YOUR_REPOSITORY_URL

Install dependencies:

    pip install -r requirements.txt

## 10. How to Run

The project notebooks are designed to run in Google Colab.

1. Open the desired notebook.
2. Open it in Google Colab.
3. Set up the dataset paths.
4. Install the required dependencies.
5. Execute the notebook cells in order.

## 11. Best Model

Describe the selected model architecture, configuration, and saved artifacts.

## 12. Conclusion and Future Work

Summarize the findings and discuss potential improvements.

## 13. License

This project is licensed under the LICENSE specified in this repository.

### Dataset License and Attribution

This project uses an external dataset for macrocycle
permeability prediction.

The original dataset is subject to its own licensing
terms and conditions.

- Dataset name: CycPeptMPDB-4D
- Original source: [Dataset](https://doi.org/10.5281/zenodo.18754430) Version v3, Jul 9, 2026

The dataset and its associated materials are not
covered by this project's MIT License. Users must refer to the original dataset source
and comply with its licensing and attribution
requirements before using or redistributing the data.









