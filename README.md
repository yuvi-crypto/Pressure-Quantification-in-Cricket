# Pressure Quantification in Cricket

*A Machine Learning and Survival Analysis Approach*

## 🔍 Project Overview

This project explores how pressure affects player performance in T20 cricket, using machine learning models and survival analysis. We quantify and model "pressure" situations, aiming to predict how players behave under stress during a match.

The study combines:

* Ball-by-ball match data
* Player-specific contextual features
* Survival curves and hazard modeling
* Classification algorithms

## 📁 Dataset

The dataset used in this project is available on Google Drive:

👉 [Download Dataset](https://drive.google.com/drive/folders/110i9cNwY7DG2_rnF0KQ7SaYpjXvGRmRD?usp=drive_link)


## 📓 Notebook

The main code and analysis are contained in:

* `smaiprojectmodel.ipynb`: Includes preprocessing, survival model training, classification experiments, and visualizations.

Key methods used:

* Kaplan-Meier estimator
* Cox Proportional Hazards Model
* Random Forest and XGBoost classifiers

## 🧠 Features Considered

* **Match Context**: Overs, wickets fallen, runs required
* **Player Form**: Average, strike rate, historical performance
* **Pressure Indicators**: Required Run Rate (RRR), Wickets in hand, Match Phase
* **Survival Variables**: Time to dismissal, censoring status

## 🎯 Objectives

* Model "survival" of a batter under pressure
* Predict dismissal likelihood
* Detect patterns in player performance under match stress
* Create data-driven pressure metrics

## 📊 Tools & Libraries

* Python (Pandas, NumPy)
* Scikit-learn
* Lifelines (Survival Analysis)
* Matplotlib / Seaborn
* Jupyter Notebook

## 📝 Results Summary

* Developed survival curves for various match contexts
* Identified key pressure indicators affecting survival time
* Achieved strong classification performance on pressure prediction

## 🧪 How to Run

1. Clone this repository
2. Download the dataset using the Drive link
3. Run the `smaiprojectmodel.ipynb` notebook in Jupyter
4. Ensure required libraries are installed:

   ```bash
   pip install pandas numpy lifelines scikit-learn matplotlib seaborn
   ```
