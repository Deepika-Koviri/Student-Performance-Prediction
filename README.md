🎓 Student Performance Prediction using Machine Learning
This project aims to predict a student's academic performance (Low, Medium, High) based on various socio-demographic and academic-related features using a classification model. It is built as part of a mini-project for a data science course.

📌 Project Title
Student Performance Prediction using Decision Tree Classifier

🧠 Objective
To develop a machine learning model that classifies students' performance based on features like gender, study time, health, and other factors. The model helps identify students who may need additional academic support.

📊 Dataset
The dataset is sourced from the UCI Machine Learning Repository (or any provided CSV).

It contains attributes like:

Gender, Age, Study Time, Failures, Absences

Grades: G1, G2, G3 (final grade used as target)

📁 Sample: student-mat.csv

🛠️ Technologies Used
Python

Jupyter Notebook

Libraries:

pandas, numpy, matplotlib, seaborn

scikit-learn

📈 Workflow
Step 1: Importing Libraries
Used standard libraries for data handling, visualization, and ML.

Step 2: Load and Understand Data
Loaded dataset using pandas.

Displayed basic info and data types.

Checked for null values.

Step 3: Data Preprocessing
Selected useful features.

Converted final grade G3 into categories: Low, Medium, High.

Used LabelEncoder to encode categorical values.

Performed train_test_split.

Step 4: Feature Scaling
Used StandardScaler for normalizing numerical data.

Step 5: Model Building
Used Decision Tree Classifier from sklearn.tree.

Step 6: Prediction & Evaluation
Evaluated the model using:

Accuracy Score

Classification Report

Confusion Matrix (with heatmap)

🤖 Algorithm Used
Decision Tree Classifier
A supervised learning algorithm used for classification tasks. It works by splitting the data based on feature values, forming a tree structure.

📊 Results
Accuracy: ~85% (may vary)

Model is able to successfully classify students into Low, Medium, or High performance levels.

