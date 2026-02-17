# Drug Classification using Machine Learning

This project applies supervised machine learning models to classify drugs based on patient medical attributes.

## 📂 Dataset

This project uses the IBM "Drug Classification" dataset.

The dataset contains 200 patient records with the following features:

- Age
- Sex
- Blood Pressure (BP)
- Cholesterol
- Na_to_K ratio

Target variable:
- Drug (Drug type prescribed)

The objective is to predict the correct drug type based on patient characteristics.

Dataset source:
IBM Data Science sample dataset (Drug200)

## 🧠 Models Implemented

- Decision Tree Classifier
- Random Forest Classifier

Both models were implemented using scikit-learn.

## ⚙️ Installation

Clone the repository:

git clone https://github.com/Raya1313/Drug_classification.git
cd Drug_classification

Install dependencies:

pip install -r requirements.txt

## ▶️ Usage

Launch Jupyter Notebook:


Open:
- notebooks/decisionTree.ipynb
- notebooks/randomForest_drug.ipynb

## 📊 Evaluation

Models were evaluated using classification accuracy.
Random Forest achieved higher accuracy due to ensemble learning properties.

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook


