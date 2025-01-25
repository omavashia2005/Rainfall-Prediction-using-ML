# Rainfall Prediction Using Machine Learning

## Overview
This project is a machine learning pipeline built from scratch to predict rainfall. Using a Kaggle dataset, I performed:
- **Data Cleaning**: Addressed missing values and ensured data consistency.
- **Feature Engineering**: Created and selected meaningful features to improve model performance.
- **Model Training and Evaluation**: Leveraged scikit-learn to train and test multiple machine learning models.

This mini-project highlights my ability to independently process raw datasets, apply machine learning concepts, and derive actionable insights from the data.

---

## Dataset
**Source**: [Kaggle Dataset](https://www.kaggle.com/datasets/waqi786/usa-rainfall-prediction-dataset-2024-2025?select=usa_rain_prediction_dataset_2024_2025.csv)  

### Key Features
- Dataset contains Date, Location, Temperature, Humidity, Cloud Cover, Rain Tomorrow, Precipitation, Wind Speed
- Target variable: `Rainfall Tomorrow` 

---

## Workflow
1. **Load Dataset**:
   - Imported data using `pandas` and performed an exploratory data analysis (EDA).

2. **Data Preprocessing**:
   - Handled missing values.
   - Encoded categorical variables.
   - Standardized numerical features.

3. **Feature Engineering**:
   - Created new features to capture patterns in the data.

4. **Model Training**:
   - Split data into training and testing sets.
   - Trained Linear Regression model using ``Scikit-learn``

5. **Evaluation**:
   - Evaluated model using MSE

---

## Results
- Current Model: Linear Regression
- Key Metric: MSE of 0.25

---

## Installation and Usage
### Requirements
- Python 3.x
- Libraries:
  - pandas
  - numpy
  - scikit-learn

---

## Learnings
- Gained hands-on experience in feature engineering, data preprocessing, and understood linear regression.
- Strengthened understanding of machine learning workflows.
- Explored practical challenges in handling real-world datasets.

---

## Future Improvements
- Experiment with advanced models like Random Forests or Gradient Boosting.
- Fine-tune hyperparameters for better accuracy.
- Deploy the model using Streamlit or Flask for user interaction.
---

## License
This project is open-source under the MIT License.

