# Student Dropout Prediction (Machine Learning Project)

This project aims to predict whether a student will drop out or successfully complete their studies based on academic, demographic, and behavioral factors.

## 🎯 Goal

- Use machine learning to identify students at risk of dropping out
- Enable early interventions by universities or advisors

## 🧰 Tools & Techniques

- Python (Pandas, NumPy, Scikit-Learn, Matplotlib)
- Decision Tree, Naive Bayes, k-NN, Random Forest
- Cross-Validation
- ONNX model export

## 📊 Key Results & Model Comparison

After training and cross-validating several models, the following insights were gained:

- **Random Forest** achieved the highest mean accuracy (76.55%) and F1 score (66.14%), making it the best overall performer.
- **Consistency**: Random Forest also showed the lowest standard deviations across folds, indicating robust performance.
- **Naive Bayes** performed reasonably, but had the highest variability (least consistent).
- **k-Nearest Neighbors (k-NN)** ranked mid-level in both accuracy and consistency.
- **Decision Tree** had decent performance, more consistent than Naive Bayes, but less than Random Forest.

### 🔍 Conclusion:
> Random Forest is the most promising model due to its balance of performance and stability. However, model selection should always align with the specific goals of deployment. Further tuning and domain-specific evaluation are recommended.

Confusion matrices and classification reports are included in the notebook to explore error types in more detail.


## 📁 Project Files

- `Project_2_student_drop_out_classifier.ipynb`: Full notebook incl. preprocessing, training & evaluation
- `student_data.csv`: Cleaned dataset
- `best_model.onnx`: Final exportable model


## 🔎 Learnings

- Data preprocessing and class balancing are crucial in imbalanced datasets
- Random Forest performed best due to feature diversity
- ONNX allows easy integration into production environments

## 📌 Use Case

This model could help universities monitor dropout risk and take proactive steps to support students.

## 👤 Author

Andrika Kapoor – M.Sc. Medical Informatics  
Focus: Data Science, Business Analytics
