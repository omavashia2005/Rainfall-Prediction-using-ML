# Rainfall Prediction Using Machine Learning

## Overview
This mini-project is a simple machine learning model to predict rainfall. Using a Kaggle dataset, I performed:
- **Data Cleaning**: Addressed missing values and ensured data consistency.
- **Feature Engineering**: Created and selected meaningful features to improve model performance.
- **Model Training and Evaluation**: Leveraged scikit-learn to train and test multiple machine learning models.

This mini-project highlights my ability to independently process raw datasets, apply machine learning concepts, and derive actionable insights from the data.

---


## Tech Stack
<p float="left">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" height="60" alt="Python" />
  <img src="https://upload.wikimedia.org/wikipedia/commons/2/22/Pandas_mark.svg" height="60" alt="pandas" />
  <img src="https://upload.wikimedia.org/wikipedia/commons/3/31/NumPy_logo_2020.svg" height="60" alt="NumPy" />
  <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" height="60" alt="scikit-learn" />
</p>


---

## Dataset
**Source**: [Kaggle Dataset](https://www.kaggle.com/datasets/waqi786/usa-rainfall-prediction-dataset-2024-2025?select=usa_rain_prediction_dataset_2024_2025.csv)  

### Key Features
- Dataset contains Date, Location, Temperature, Humidity, Cloud Cover, Rain Tomorrow, Precipitation, Wind Speed
- Target variable: `Rainfall Tomorrow` 

---

## Workflow
1. **Load Dataset**:
   - Imported data using `pandas` and performed an exploratory data analysis (EDA)

2. **Data Preprocessing**:
   - Handled missing values
   - Encoded categorical variables
   - Standardized numerical features

3. **Feature Engineering**:
   - Created new features to capture patterns in the data

4. **Model Training**:
   - Split data into training and testing sets
   - Trained Logistic Regression (normal and SGD-based) and Decision Classification models using ``Scikit-learn``
   - Utilized class balancing to improve F1-scores

5. **Evaluation**:
   - Evaluated models using F1-score

---

## Results
- Current Model: Logistic Regression
- Key Metric: F1 of 0.91

---

## Learnings
- Gained hands-on experience in feature engineering, data preprocessing, and understood logistic regression and decision tree classification.
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

