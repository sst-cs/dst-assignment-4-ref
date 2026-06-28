# DST Assignment 04: ML Pipeline

In this assignment, you will build a complete machine learning pipeline for student performance classification.

## Core Objective
Implement the K-Nearest Neighbors (KNN) algorithm entirely from scratch using only `numpy`. You will then compare your implementation against standard models from `scikit-learn`.

## Dataset
You are provided with `students_performance.csv`, which contains 10,000 records of students with features like study hours, attendance, previous GPA, and sleep hours. The target variable is `grade` (A, B, C, or F).

Be careful! The dataset contains missing values and variables that need encoding before they can be used in your model.

## Rules
1. Work directly in `assignment.ipynb`.
2. Do **not** modify the specific variable names requested in the `# TODO:` comments. The autograder relies on these exact names.
3. For Task 4, you may NOT use `sklearn.neighbors` or any other library. You must implement the logic using `numpy`.
4. When asked for a `random_state`, always use `random_state=42`.

## To Run Locally
```bash
pip install -r requirements.txt
jupyter notebook assignment.ipynb
```

## Submission
Push your completed notebook to GitHub Classroom. The autograder will test your variable values and evaluate your KNN function on hidden test cases.
