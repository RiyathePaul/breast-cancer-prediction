# Breast Cancer Prediction using Machine Learning

This is a beginner-level machine learning project where I worked on predicting whether a breast tumor is **benign or malignant** using Python and Logistic Regression.

I made this project to get more comfortable with the basic machine learning workflow, especially data preprocessing, visualization, model training, and evaluating the results.

> **Note:** This project is only for educational purposes and should not be used as a medical diagnostic tool.

---

## About the Project

The main idea of this project is to use the information provided in the dataset to predict the diagnosis of a tumor.

I followed these steps while building the project:

1. Loaded the dataset
2. Cleaned the unnecessary columns
3. Explored and visualized the data
4. Separated the features and target variable
5. Split the data into training and testing sets
6. Scaled the numerical features
7. Trained a Logistic Regression model
8. Made predictions on the test data
9. Evaluated the model

---

## Dataset

The dataset used in this project is `Cancer_Data.csv`.

The `diagnosis` column contains two types of values:

- `B` – Benign
- `M` – Malignant

For training the machine learning model, I converted these into numerical values:

- `0` – Benign
- `1` – Malignant

The dataset contains several numerical features related to characteristics of the cell nuclei.

---

## Machine Learning Model

### Logistic Regression

I used **Logistic Regression** for this project because the problem involves two possible classes: benign and malignant.

Before training the model, I used `StandardScaler` to standardize the numerical features.

---

## Tools and Libraries

I used the following tools and Python libraries:

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Project Workflow

```text
Cancer Dataset
      ↓
Load Data
      ↓
Clean Data
      ↓
Visualize Data
      ↓
Prepare Features and Target
      ↓
Train-Test Split
      ↓
Feature Scaling
      ↓
Logistic Regression
      ↓
Prediction
      ↓
Evaluation


## Data Preprocessing

Some of the preprocessing steps I performed were:
Removed unnecessary columns such as id and Unnamed: 32
Converted B and M into 0 and 1
Separated the input features from the target variable
Split the data into training and testing data
Standardized the features using StandardScaler


## Model Evaluation

After training the model, I evaluated its performance using:

Accuracy

Accuracy shows the percentage of predictions that were classified correctly.

Classification Report

The classification report gives information about:

Precision
Recall
F1-score
Support
Confusion Matrix

I also used a confusion matrix to see how many predictions were:

Correctly classified as benign
Correctly classified as malignant
Incorrectly classified as benign
Incorrectly classified as malignant

The actual results can be seen in the notebook.


## Results

### Diagnosis Distribution

![Diagnosis Distribution](diagnosis_distribution.png)

### Confusion Matrix

![Confusion Matrix](Conffusion_matrix_heatmap.png)

### Classification Report

![Classification Report](Classification_Report.png)




## Project Files
breast-cancer-prediction/
│
├── Breast_Cancer_Prediction_test.ipynb
├── Cancer_Data.csv
├── requirements.txt
├── .gitignore
└── README.md


## How to Run

If you want to try the project yourself:

1. Clone the repository
git clone https://github.com/RiyathePaul/breast-cancer-prediction.git
2. Open the project folder
cd breast-cancer-prediction
3. Install the required libraries
pip install -r requirements.txt
4. Open the notebook

Open:

Breast_Cancer_Prediction_test.ipynb

in Jupyter Notebook or VS Code.

5. Run the cells

Run the cells from top to bottom to load the dataset, train the model, and see the results.


## What I Learned

While working on this project, I got hands-on practice with:

Loading and working with datasets
Cleaning data
Visualizing data
Preparing data for machine learning
Splitting data into training and testing sets
Feature scaling
Logistic Regression
Making predictions
Understanding classification reports
Reading a confusion matrix

This project also helped me understand how the different steps of a basic machine learning project fit together.

## Future Improvements

There are several things I could add to this project in the future, such as:

Trying other classification algorithms
Comparing the performance of different models
Hyperparameter tuning
Cross-validation
ROC-AUC analysis
Adding more visualizations
Creating a simple web interface for making predictions


## Author
Riya Paul

This project was created as part of my learning journey in Python and Machine Learning.

This version sounds much more like **a student explaining their own project** rather than a generated project template. It also avoids pretending the project is more advanced than it actually is.
