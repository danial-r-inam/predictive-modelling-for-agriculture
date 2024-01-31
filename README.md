# Sowing Success: Machine Learning in Agriculture

## Overview

This project focuses on aiding farmers in selecting the most suitable crops for their fields using machine learning. By analyzing essential soil metrics, we aim to build a model that predicts the optimal crop choice, maximizing yield and efficiency in agricultural practices.

## Data Description

The provided dataset `soil_measures.csv` includes the following features:

- `"N"`: Nitrogen content ratio in the soil.
- `"P"`: Phosphorous content ratio in the soil.
- `"K"`: Potassium content ratio in the soil.
- `"pH"`: pH value of the soil.
- `"crop"`: Target variable indicating the optimal crop choice.

Each row represents soil measurements from different fields.

## Project Tasks

### Data Preprocessing
- Loaded and examined the `soil_measures.csv` file.
- Handled missing values and standardized the format of the data.
- Conducted feature engineering to enhance model inputs.

### Exploratory Data Analysis
- Analyzed soil metrics to understand their distribution and impact on crop choice.
- Visualized relationships between soil properties and crop types.

### Model Development
- Developed a multi-class classification model using scikit-learn to predict the type of `"crop"`.
- Addressed multicollinearity in features to ensure model reliability.

### Model Evaluation
- Assessed the model's performance using appropriate metrics for classification models.
- Conducted cross-validation to evaluate the model's effectiveness.

### Model Optimization
- Tuned hyperparameters and employed feature selection techniques to improve model accuracy.
- Implemented techniques to balance the dataset if needed.

### Results and Insights
- Summarized key findings and their implications for crop selection.
- Provided recommendations for farmers based on soil conditions and model predictions.

## Technologies Used
- Data analysis: `pandas`, `numpy`
- Machine learning: `scikit-learn`
- Data visualization: `matplotlib`, `seaborn`

## Contributors
- Danial Rashid Inam

---

*This project leverages machine learning to revolutionize agricultural practices, enabling farmers to make data-driven decisions for optimal crop selection and enhanced productivity.*
