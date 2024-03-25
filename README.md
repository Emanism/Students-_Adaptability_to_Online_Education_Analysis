# Students-_Adaptability_to_Online_Education_Analysis

# Overview
This project explores the adaptability levels of students to online education. Utilizing various data preprocessing techniques and machine learning models, we aim to identify significant factors influencing students' ability to adapt to online learning environments.

# Data Preprocessing
The initial steps involve data cleansing and encoding:

* One-Hot Encoding: Applied to non-ordinal categorical data such as 'Education Level', 'Financial Condition', and 'Internet Type'.
* Label Encoding: Utilized for binary categorical data like 'Gender', 'IT Student', and 'Self Lms'.
* Custom Encoding: Specific mappings for 'Age' and 'Class Duration' to convert these ordinal features into numerical values.
* Standardization: All features were standardized to have a mean of 0 and a standard deviation of 1 for scale-invariant machine learning algorithms.
  
# Dataset Split
The dataset was split into training (70%) and testing (30%) sets to evaluate the performance of the models accurately.

# Model Selection and Evaluation

We tested various machine learning models, including:

* Logistic Regression
* Decision Trees
* Random Forest
* Support Vector Machine (SVM)
* Gradient Boosting Machines (GBM)
  
The Random Forest classifier was identified as the most effective model, based on metrics such as accuracy, precision, recall, and F1 score.

### Hyperparameter Tuning
Following initial model evaluation, we performed hyperparameter tuning on the Random Forest model to enhance its performance. This involved optimizing parameters such as 'n_estimators', 'max_depth', 'min_samples_split', and 'min_samples_leaf' using a grid search approach.

### Results and Insights
The optimized Random Forest model showed an improvement over the baseline model, achieving an accuracy of approximately 88.67%. This indicates the model's strong predictive capability and its potential to aid educational strategies and interventions for improving student adaptability in online learning contexts.

### Repository Contents
Data Preprocessing Notebook: Step-by-step data cleaning, encoding, and standardization.
Model Training and Evaluation Notebook: Detailed model evaluation and hyperparameter tuning.
Datasets: The raw and processed datasets used in the analysis.
Readme: Instructions for replicating the study and additional project details
