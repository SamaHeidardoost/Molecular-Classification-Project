# Molecular Classification using Machine Learning

## Project Overview

This project focuses on the classification of molecular compounds using supervised Machine Learning algorithms. The dataset contains molecular descriptors representing the structural and chemical properties of compounds, which are used to predict their corresponding classes.

The project demonstrates a complete machine learning workflow including data preprocessing, feature scaling, model development, evaluation, visualization, hyperparameter tuning, and model comparison.

---

## Dataset

The dataset contains:

- **837 molecular compounds**
- **41 numerical molecular descriptors**
- **Binary target variable (Class)**

Target classes:

- **0** → Inactive compound
- **1** → Active compound

---

## Project Workflow

1. Data Loading
2. Exploratory Data Analysis (EDA)
3. Data Preprocessing
4. Feature Scaling
5. Train-Test Split
6. Model Training
7. Model Evaluation
8. ROC Curve Analysis
9. Feature Importance Analysis
10. Hyperparameter Tuning
11. Model Comparison

---

## Machine Learning Models

The following supervised learning algorithms were implemented and evaluated:

- Logistic Regression
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest
- Gradient Boosting
- AdaBoost
- Gaussian Naive Bayes
- Multi-Layer Perceptron (MLP)

---

## Model Performance

| Model | Accuracy | ROC-AUC |
|--------|---------:|---------:|
| Logistic Regression | 86.2% | 0.912 |
| SVM | 78.4% | 0.852 |
| KNN | 76.0% | 0.853 |
| Decision Tree | 85.0% | 0.840 |
| Random Forest | 86.8% | 0.922 |
| Gradient Boosting | **87.4%** | **0.926** |
| AdaBoost | 83.8% | 0.901 |
| Gaussian Naive Bayes | 69.5% | 0.875 |
| MLP Neural Network | 81.4% | 0.892 |

---

## Best Model

🏆 **Gradient Boosting**

| Metric | Value |
|---------|------:|
| Accuracy | **87.43%** |
| ROC-AUC | **0.926** |

---

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Installation

```bash
pip install -r requirements.txt
```

---

## Run the Project

```bash
jupyter notebook Molecular-Classification-Project.ipynb
```

---

## Repository Structure

```
Molecular-Classification-Project
│
├── Molecular-Classification-Project.ipynb
├── Molecular_Dataset.csv
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

---

## Author

**Sama Heidardoost**

Python Developer | Machine Learning & Artificial Intelligence Enthusiast

---

## License

This project is released under the MIT License.
