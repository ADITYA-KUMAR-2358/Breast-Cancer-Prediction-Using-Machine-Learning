# Breast Cancer Prediction Using Machine Learning

## Overview
This project is part of a machine learning learning journey (Coursera) focusing on predicting whether a breast cancer tumor is benign or malignant. It uses a Breast Cancer dataset containing various features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass.

## Dataset
The dataset `data.csv` contains 569 instances with 33 columns. Key columns include:
- `id`: Unique ID for each patient
- `diagnosis`: The target variable (`M` = Malignant, `B` = Benign)
- 30 numerical features computing mean, standard error, and "worst" (mean of the three largest values) for 10 real-valued features (e.g., radius, texture, perimeter, area, smoothness, compactness, concavity, concave points, symmetry, fractal dimension).

## Project Structure
- `data.csv`: The dataset used for training and testing.
- `project.ipynb`: Jupyter Notebook containing the data exploration, preprocessing, and model building steps.
- Screenshots: Visual results and code execution captures of the data analysis.

## Machine Learning Pipeline
1. **Data Preprocessing**:
   - Handled null values (dropped empty columns like `Unnamed: 32`).
   - Encoded the categorical target variable (`diagnosis`) into numerical format (1 for Malignant, 0 for Benign) using `LabelEncoder`.
   - Split the dataset into training (75%) and testing (25%) sets using `train_test_split`.
   - Scaled the features using `StandardScaler` to standardize the data distributions.

2. **Model Training**:
   - Built a **Logistic Regression** model using `scikit-learn` to classify the tumors based on the input features.
   
3. **Results & Evaluation**:
   - Predicted the diagnosis on the testing set and evaluated model performance.

## Requirements
To run this project, you need the following Python libraries installed:
- `pandas`
- `seaborn`
- `scikit-learn`
- `jupyter` (to run the notebook)

## How to Run
1. Clone this repository to your local machine.
2. Ensure you have the required libraries installed. You can install them using `pip install pandas seaborn scikit-learn jupyter`.
3. Open `project.ipynb` in Jupyter Notebook or JupyterLab.
4. Run the cells sequentially to observe data processing, model training, and results.


## Batch B2
1. Aditya Kumar B-53
2. Ankit Singh B-54
3. Anuj Kathal B-61