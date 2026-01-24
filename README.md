# Raisin Classification - Machine Learning Project

## 📌 Project Overview
This project demonstrates a supervised machine learning approach to classify raisins based on their features. Using a dataset containing measurements of different types of raisins, a classification model was built to accurately predict the raisin type.

## 🛠 Tools & Techniques
- Python
- Pandas & NumPy for data manipulation
- Scikit-learn for machine learning
- Logistic Regression / Decision Tree / Random Forest (whichever you used)
- Train-test split
- K-Fold Cross Validation
- Pipelines for preprocessing and modeling
- Matplotlib / Seaborn for data visualization

## 📂 Dataset
The dataset includes features such as:
- Area, Perimeter, Major Axis, Minor Axis
- Eccentricity, Convex Area, Extent, etc.
- Target label: Raisin type (e.g., `Kecimen` or `Besni`)

## 📊 Model Approach
- Exploratory Data Analysis (EDA) to understand the dataset
- Preprocessing pipeline (scaling, encoding if necessary)
- Training classification model
- Model evaluation using accuracy, confusion matrix, and K-Fold cross-validation

## 🧠 Key Insights
- Feature importance analysis revealed which measurements best differentiate raisin types
- The model achieved high accuracy (insert % if known)
- Cross-validation ensures robust performance across different splits of the data

## 🚀 How to Use
1. Open the notebook `notebooks/raisin_classification.ipynb`
2. Ensure all dependencies in `requirements.txt` are installed
3. Run the notebook to reproduce preprocessing, model training, and evaluation

## 📁 Files in This Repository
- `notebooks/raisin_classification.ipynb` – Jupyter notebook with full workflow
- `data/` – Sample or full dataset (depending on size)
- `requirements.txt` – Libraries required for the project
