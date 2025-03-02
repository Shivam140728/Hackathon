# Hackathon
Aviation KPI Analysis

Overview

This project analyzes aviation key performance indicators (KPIs) and predicts profit using machine learning models. It utilizes Random Forest and XGBoost regression techniques to evaluate the dataset and generate insights.

Dataset

The dataset used is Aviation_KPIs_Dataset.csv.

It contains various aviation-related metrics, including profit in USD.

Unnecessary columns such as Flight Number, Scheduled Departure Time, and Actual Departure Time are removed.

Missing values are handled by replacing them with the median values of respective columns.

Features & Target Variable

Features: All columns except Profit (USD).

Target Variable: Profit (USD).

Steps Involved

Data Preprocessing

Load the dataset.

Drop irrelevant columns.

Handle missing values.

Model Training

Split data into training (70%) and testing (30%) sets.

Train a Random Forest Regressor.

Train an XGBoost Regressor with tuned hyperparameters.

Model Evaluation

Evaluate both models using:

Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)

R-squared (R²) Score

Identify potential overfitting or underfitting issues.

Prediction & Export

Generate profit predictions.

Store predictions in a CSV file for further analysis.

Dependencies

Ensure you have the following libraries installed before running the script:

pip install pandas numpy scikit-learn xgboost

Usage

Run the script in a Python environment (Google Colab, Jupyter Notebook, or local system) using:

python aviation_kpi_analysis.py

Author

Shivam Kumar

License

This project is open-source and free to use for educational and research purposes.

