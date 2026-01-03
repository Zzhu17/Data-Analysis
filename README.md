# Data-Analysis
# Breast Cancer Diagnosis using Data Mining Techniques
# Introduction
This project implements and applies various data mining techniques to a real-world imbalanced dataset. The primary goal is to perform classification on the Breast Cancer Wisconsin (Diagnostic) dataset to distinguish between malignant and benign tumors.

# Dataset
The project uses the Wisconsin Breast Cancer Diagnostic dataset from the UCI Machine Learning Repository.

Total Instances: 569

Features: 30 real-valued attributes computed from digitized images of fine needle aspirates (FNA) of breast masses.

Attributes: Radius, texture, perimeter, area, smoothness, compactness, concavity, concave points, symmetry, and fractal dimension.

Target Task: Binary classification (Malignant vs. Benign).

Features of the Project
Data Acquisition: Automatically fetches data using the ucimlrepo library.

Exploratory Data Analysis (EDA): Visualizes data distributions and correlations using matplotlib and seaborn.

Imbalanced Learning: Addresses the challenges of working with imbalanced real-world datasets.

Data Mining Pipeline: Covers data loading, preprocessing, and model implementation for classification.

Requirements
To run this notebook locally, you will need the following Python libraries:

pandas

numpy

matplotlib

seaborn

ucimlrepo

You can install the dependencies using pip:

Bash

pip install pandas numpy matplotlib seaborn ucimlrepo
Setup & Usage
Environment: It is recommended to create a new Python environment before running the project.

Execution: Open the [CS235F25]_Course_Project (1).ipynb file in Jupyter Notebook or Google Colab.

Data Loading: The notebook is configured to fetch the dataset directly from UCI, so no manual download of the CSV is required.

Project Structure
Setup: Environment initialization and package installation.

Imports: Loading necessary libraries for data processing and visualization.

Load Data: Fetching the Breast Cancer dataset.

Exploration/Modeling: Implementation of data mining techniques discussed in the course.
