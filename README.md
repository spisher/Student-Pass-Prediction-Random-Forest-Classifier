
# Student Pass Prediction — Random Forest Classifier

This project predicts whether a student will pass or fail based on their academic performance using a Random Forest Classifier.

##  Project Overview
The goal of this project is to build a classification model that determines whether a student will pass based on their **math**, **reading**, and **writing** scores.

We use the `StudentsPerformance.csv` dataset and define a new column `passed` where:

passed = 1  if average score >= 70
passed = 0  otherwise


##  Steps Performed

### 1. Import and Prepare Data
- Loaded the dataset using **Pandas**  
- Calculated the `average score` for each student  
- Created a binary target column `passed`  

### 2. Split Data
Used `train_test_split` to divide the data:
python
test_size=0.25, random_state=42

3. Train Model
Trained a Random Forest Classifier with:
n_estimators = 200
max_features = 'sqrt'
random_state = 42

4. Evaluate Model
Calculated the following metrics:


Accuracy


Precision


Recall


F1 Score


ROC-AUC Score


Also displayed:


Classification Report


Confusion Matrix


ROC Curve


5. Visualizations


Confusion Matrix heatmap using matplotlib


ROC Curve visualization with RocCurveDisplay



 Results
MetricScore (example)Accuracy0.96Precision0.95Recall0.97F1 Score0.96ROC-AUC0.97
(Scores may vary slightly depending on train/test split)

## Technologies Used


Python 


Pandas


Scikit-learn


Matplotlib


# Author
Ali Shahab Pour
alishahabpour19@gmail.com

