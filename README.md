# Student Performance Analysis and Machine Learning

## Project Overview

This project analyzes student performance data and applies machine learning techniques to understand the factors associated with students' academic outcomes.

The project uses the **Student Performance Dataset**, which contains information about students' demographic characteristics, family background, study habits, school support, social activities, and academic performance.

The project demonstrates an end-to-end data science workflow, starting from data exploration and preprocessing and progressing to visualization, feature preparation, machine learning, and model evaluation.

---

## Project Objectives

The main objectives of this project are to:

* Explore and understand the Student Performance dataset.
* Identify patterns and relationships between student characteristics and academic performance.
* Perform data cleaning and preprocessing.
* Visualize important patterns within the dataset.
* Prepare data for machine learning.
* Train a machine learning classification model.
* Evaluate the performance of the model.
* Identify factors that may be associated with student performance.

---

## Dataset

The dataset contains information about students from secondary schools.

Some of the important variables include:

| Feature      | Description                                 |
| ------------ | ------------------------------------------- |
| `school`     | Student's school                            |
| `sex`        | Student's gender                            |
| `age`        | Student's age                               |
| `address`    | Type of residential area                    |
| `famsize`    | Family size                                 |
| `Pstatus`    | Parents' cohabitation status                |
| `Medu`       | Mother's education level                    |
| `Fedu`       | Father's education level                    |
| `Mjob`       | Mother's occupation                         |
| `Fjob`       | Father's occupation                         |
| `studytime`  | Weekly study time                           |
| `failures`   | Number of previous class failures           |
| `schoolsup`  | Extra educational support                   |
| `famsup`     | Family educational support                  |
| `activities` | Participation in extracurricular activities |
| `higher`     | Desire to pursue higher education           |
| `internet`   | Internet access at home                     |
| `absences`   | Number of school absences                   |
| `G1`         | First-period grade                          |
| `G2`         | Second-period grade                         |
| `G3`         | Final grade                                 |

The dataset contains both categorical and numerical variables, making it suitable for practicing data preprocessing and machine learning techniques.

---

## Technologies and Libraries

The project was developed using Python and Jupyter Notebook.

Main technologies and libraries used include:

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## Project Workflow

The project follows a typical machine learning workflow:

```text
Data Collection
      ↓
Data Loading
      ↓
Data Exploration
      ↓
Data Cleaning
      ↓
Exploratory Data Analysis
      ↓
Feature Preparation
      ↓
Train/Test Split
      ↓
Model Training
      ↓
Prediction
      ↓
Model Evaluation
      ↓
Conclusion
```

---

## 1. Data Exploration

The dataset was first loaded into Python using Pandas.

Initial exploration was performed to understand:

* Number of rows and columns
* Data types
* Missing values
* Duplicate records
* Statistical summaries
* Distribution of variables

Examples of Pandas functions used include:

```python
df.head()
df.info()
df.describe()
df.isnull().sum()
df.duplicated().sum()
```

This stage helped establish a clear understanding of the dataset before applying machine learning techniques.

---

## 2. Data Cleaning and Preprocessing

Before training the machine learning model, the data was prepared for analysis.

The preprocessing stage included:

* Checking for missing values
* Checking for duplicate records
* Examining categorical and numerical variables
* Converting categorical variables into a machine-readable format
* Selecting appropriate features
* Preparing the target variable
* Splitting the data into training and testing sets

Categorical variables were encoded so that they could be used by the machine learning algorithm.

---

## 3. Exploratory Data Analysis

Exploratory Data Analysis was performed to identify patterns and relationships within the dataset.

Visualizations were created to investigate areas such as:

* Student performance
* Study time
* Previous failures
* Absences
* Gender
* Parental education
* School support
* Family support
* Internet access
* Students' intention to pursue higher education

The visualizations helped provide a better understanding of the factors associated with academic performance.

---

## 4. Machine Learning

After preprocessing the data, the dataset was divided into training and testing sets.

The training data was used to teach the machine learning model, while the testing data was used to evaluate how well the model performed on unseen data.

The general process was:

```python
X_train, X_test, y_train, y_test = train_test_split(
    X, y,
    test_size=0.2,
    random_state=42
)
```

A classification model was then trained using the prepared features.

---

## 5. Model Evaluation

After training, the model generated predictions for the test dataset.

The model was evaluated using appropriate classification metrics, including:

* Accuracy
* Confusion Matrix
* Classification Report
* Precision
* Recall
* F1-score

These metrics provide different perspectives on how well the model classified student outcomes.

---

## Key Findings

The analysis showed that student performance is influenced by a combination of academic, demographic, family, and behavioral factors.

Variables such as:

* Study time
* Previous failures
* Absences
* Previous grades
* Parental education
* Educational support

can provide useful information when analyzing student academic outcomes.

The project also demonstrates that machine learning can be used to identify patterns in educational data and potentially support data-driven decision making.

---



---



## Skills Demonstrated

This project demonstrates practical experience with:

* Python programming
* Data manipulation using Pandas
* Numerical analysis using NumPy
* Data visualization
* Exploratory Data Analysis
* Data cleaning
* Categorical encoding
* Feature preparation
* Train/test splitting
* Supervised machine learning
* Classification
* Model evaluation
* Jupyter Notebook
* Git and GitHub

---



---

## Conclusion

This project provided practical experience in taking a real-world dataset through the complete data science and machine learning workflow.

It demonstrates how Python can be used to explore educational data, identify meaningful patterns, prepare data for machine learning, build predictive models, and evaluate their performance.

The project also serves as a foundation for more advanced work in **Data Science, Machine Learning, and Artificial Intelligence**.

---

## Author

BONELLY KAMONYE

Student | Business Information Technology
Interested in Data Analytics, Data Science, Machine Learning, and Artificial Intelligence. from Dedan Kimathi univerisity of Technology 

