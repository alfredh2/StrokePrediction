# Patient Stroke Prediction Project
**Alfred Hofmann**

## Introduction
Welcome to the Patient Stroke Prediction Project! Our main research goal is to build a predictive model that will effectively predict the probability a patient will have a stroke. Additionally, we aim to identify which variables in our dataset have the most predictive power when it comes to predicting if a person will have a stroke. This project is implemented in a Jupyter Notebook.

## Technologies
- **Programming Language:** Python 3
- **Libraries and Frameworks:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn, Statsmodels
- **Environment:** Jupyter Notebook

## Dataset
The dataset used in this project is from Kaggle's Stroke Prediction Dataset. It includes features such as age, hypertension, heart disease, average glucose level, BMI, and smoking status, with the response variable being whether a stroke has occurred or not.

**Dataset Source:** [Kaggle Stroke Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset)

## Model
We use various logistic regression models, like Lasso, for the stroke prediction. The use of the model and tuning are demonstrated in the notebook. Additionally, K-Means clustering is applied for further analysis.

## Installation
To run this project, follow these steps:

1. Ensure that Python 3 and Jupyter Notebook are installed on your machine.
2. Clone this repository:
   ```
   git clone https://github.com/alfredh2/PatientStrokePrediction.git
   ```
3. Navigate to the cloned repository.
4. Install required dependencies:
   ```
   pip install -r requirements.txt
   ```

## Running the Notebook
1. Open a terminal and navigate to the project directory.
2. Start Jupyter Notebook:
   ```
   jupyter notebook
   ```
3. Open the `PatientStrokePrediction.ipynb` notebook.
4. Run the cells in the notebook to see the analysis and model predictions.

## Results
The notebook includes a detailed analysis of model performance and accuracy metrics. We compare different models and discuss the best-performing model for this dataset. Additionally, the K-Means clustering analysis provides insights into the relationships between the explanatory variables.

**To read about my experience working on this project, go to my Medium article on it: https://medium.com/@alfredpmhofmann/project-5-patient-stoke-prediction-using-logistic-regression-9a35a24342dc
