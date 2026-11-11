# elevate-labs-task-05
AI &amp; ML Internship – Task 5: Decision Trees and Random Forests

# Task 5: Decision Trees and Random Forests

**AI & ML Internship – Elevate Labs**

## Objective
To understand and implement Decision Tree and Random Forest algorithms for classification, analyze overfitting, and evaluate model performance.

## Dataset
Heart Disease Dataset (Kaggle).

## Tools & Technologies
- Python
- Pandas
- Scikit-learn
- Graphviz
- Google Colab

## Tasks Performed
1. Loaded and explored the Heart Disease dataset.
2. Handled duplicate records.
3. Performed One-Hot Encoding.
4. Split the dataset into training and testing sets.
5. Trained a Decision Tree Classifier.
6. Analyzed overfitting using different tree depths.
7. Visualized the Decision Tree using Graphviz.
8. Trained a Random Forest Classifier.
9. Analyzed feature importance.
10. Evaluated models using 5-fold cross-validation.
11. Compared model performance.
12. Evaluated the Random Forest using a confusion matrix and classification report.

## Model Performance

| Metric | Decision Tree | Random Forest |
|---|---:|---:|
| Training Accuracy | 77.59% | 100.00% |
| Testing Accuracy | 72.13% | 81.97% |
| Cross-Validation Accuracy | 68.00% | 77.16% |

## Key Findings
- Random Forest achieved higher testing accuracy than the Decision Tree.
- Random Forest achieved 77.16% mean cross-validation accuracy.
- `thalach` was the most important feature in the Random Forest model.
- The Random Forest showed a gap between training and testing accuracy, indicating possible overfitting.
