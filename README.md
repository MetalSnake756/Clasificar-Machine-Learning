
# Classification of bank clients
This project analyzes data from a marketing campaign to predict whether bank clients will subscribe to investment products. The goal is to build a machine learning model to make these predictions. 🎯

## Project Description
This notebook outlines the steps for creating a classification model to predict client investment adherence using machine learning. The process covers reading 📖, exploratory analysis 📊, separation and transformation of data, and finally the fitting, evaluation, and comparison of different classification models.

## Methodology
The project begins with an Exploratory Analysis to understand the dataset. This involves:

1. Reading the Data: The dataset is read using the pandas library from a CSV file named marketing_inversiones.csv.

2. Data Quality Check: The info() method is used to check for null values and the data types of each column. The notebook states that for good models, the data should be high quality, without inconsistencies or missing values.

3. Data Exploration: The notebook uses the plotly library to create graphs for an in-depth exploration of the data, starting with categorical variables and then moving to numerical ones.

## Dataset
The notebook uses a CSV file named marketing_inversiones.csv. The data includes the following columns:

* edad: Age

* estado_civil: Marital status

* escolaridad: Education level

* default: Whether the client defaulted on a loan

* saldo: Balance

* prestatario: Borrower status

* ultimo_contacto: Last contact

* ct_contactos: Contact count

* adherencia_inversion: Investment adherence, which is the target variable (labeled si or no)

## 🛠️ Libraries Used

Pandas → Data manipulation & analysis

Seaborn & Matplotlib → Data visualization

Warnings → Suppress execution warnings

scikit-learn → Machine Learning

pandas

plotly.express
