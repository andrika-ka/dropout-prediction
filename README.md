# Student Dropout Prediction (Machine Learning Project)

This project aims to predict whether a student will drop out or successfully complete their studies based on academic, demographic, and behavioral factors.

## 🎯 Goal

- Use machine learning to identify students at risk of dropping out
- Enable early interventions by universities or advisors

## 🧰 Tools & Techniques

- Python, Scikit-Learn
- Decision Tree, Naive Bayes, k-NN, Random Forest
- Cross-Validation
- ONNX model export

## 📊 Key Results

- Best-performing model: Random Forest (F1-Score: 0.88)
- Cross-validated accuracy: 91%
- Model exported as ONNX (`best_model.onnx`) for deployment use

## 📁 Project Files

- `Project_2_student_drop_out_classifier.ipynb`: Full notebook incl. preprocessing, training & evaluation
- `student_data.csv`: Cleaned dataset
- `best_model.onnx`: Final exportable model
- `visuals/`: Optional plots (confusion matrix, accuracy, feature importance)

## 🔎 Learnings

- Data preprocessing and class balancing are crucial in imbalanced datasets
- Random Forest performed best due to feature diversity
- ONNX allows easy integration into production environments

## 📌 Use Case

This model could help universities monitor dropout risk and take proactive steps to support students.

## 👤 Author

Andrika Kapoor – M.Sc. Medical Informatics  
Focus: Data Science, Business Analytics
