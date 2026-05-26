# K-Nearest Neighbors Classification Project

This is a course-based practice project completed as part of my Python for Data Science and Machine Learning learning journey.

The goal of this project is to build a K-Nearest Neighbors classification model using a dataset with anonymized numerical features and a binary target class.

## Project Overview

The notebook follows a standard classification workflow:

- Importing and inspecting the dataset
- Exploring the feature data with Seaborn and Matplotlib
- Scaling numerical features with `StandardScaler`
- Splitting the data into training and testing sets
- Training a KNN classification model
- Testing different values of `K` using error-rate analysis
- Evaluating predictions with a confusion matrix and classification report

## Model Evaluation

The final trained KNN model in this notebook uses:

- Algorithm: K-Nearest Neighbors
- Selected `K` value: 18
- Train-test split: 70% training and 30% testing
- Random state: 101

The model achieved the following results on the test set:

| Metric | Class 0 | Class 1 |
| --- | ---: | ---: |
| Precision | 0.82 | 0.83 |
| Recall | 0.84 | 0.82 |
| F1-score | 0.83 | 0.82 |

Overall accuracy: 0.83

Confusion matrix:

```text
[[127  25]
 [ 27 121]]
```

## Key Learnings

This project helped me understand how distance-based classification works and why feature scaling is important for KNN models. I also practiced tuning the `K` value and interpreting classification metrics such as precision, recall, F1-score, and accuracy.

## Files

- `02-K Nearest Neighbors Project - LinkedIn Ready.ipynb`: completed Jupyter notebook
- `KNN_Project_Data`: dataset used in the notebook
- `requirements.txt`: Python libraries used in the project

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

## Note

This is a learning project based on a course exercise. I am sharing it to document my progress and demonstrate my understanding of K-Nearest Neighbors, feature scaling, hyperparameter tuning, and classification model evaluation.
