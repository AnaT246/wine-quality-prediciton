# wine-quality-prediciton
# Wine Quality Prediction using Machine Learning

## Project Overview

This project aims to predict the quality of red wine based on its physicochemical properties. I developed and evaluated two tree-based machine learning models, Decision Tree and Random Forest, to perform the classification task. This was my Bachelor Thesis project, which was awarded the highest grade (10/10).

## Dataset

The dataset used is the "Red Wine Quality" dataset from the UCI Machine Learning Repository. It contains 11 chemical features and a quality score ranging from 3 to 8.

[Link to the dataset](https://archive.ics.uci.edu/ml/datasets/wine+quality)

## Key Steps

- **Data Cleaning and Preprocessing:** Handled missing values and prepared the data for modeling.
- **Exploratory Data Analysis (EDA):** Used Matplotlib and Seaborn to visualize feature distributions and correlations to gain insights.
- **Model Training:** Implemented Decision Tree and Random Forest classifiers using the scikit-learn library.
- **Model Evaluation:** Assessed model performance using metrics like accuracy, precision, recall, and the confusion matrix.

## Technologies Used

- **Language:** Python
- **Libraries:** Pandas, NumPy, scikit-learn, Matplotlib, Seaborn
- **Tools:** Jupyter Notebook

## Results

The Random Forest model achieved a higher accuracy of [upisi svoju točnost, npr. 85%] compared to the Decision Tree model, proving to be more robust for this prediction task. The most important features for predicting wine quality were found to be alcohol, sulphates, and volatile acidity.
