Heart Disease Prediction
Predicting heart disease presence using machine learning techniques

Overview
Heart disease is one of the leading causes of death worldwide. This project leverages machine learning models to predict the likelihood of heart disease using patient medical records. The solution is built with WEKA and uses classification algorithms to achieve accurate predictions.

By automating this predictive process, healthcare providers can make faster, data-driven decisions to save lives.

Features
- Predict presence or absence of heart disease
- Trained using Random Forest, Naive Bayes, and K-Nearest Neighbours (KNN)
- Dataset preprocessing and cleaning
- Achieved up to **85% accuracy**

Dataset
- Source: UCI Machine Learning Repository
- Records: 303 patients
- Attributes: 14 (Age, Sex, Chest Pain Type, Blood Pressure, Cholesterol, etc.)

> Dataset is converted from CSV to ARFF for compatibility with WEKA.

Algorithms Used
| Algorithm       | Accuracy |
| --------------- | -------- |
| Naive Bayes     | 85%      |
| Random Forest   | 84%      |
| K-Nearest Neighbors (KNN) | 82% |

All models were evaluated using 10-fold cross-validation.

 Tech Stack
- Machine Learning Tool:** WEKA
- Algorithms:
  - Random Forest
  - Naive Bayes 
  - K-Nearest Neighbors (KNN) 
- ataset Format:CSV, ARFF

How It Works

1. Data Preprocessing
   - Removed duplicates and irrelevant attributes
   - Discretized numeric attributes
   - Converted dataset to ARFF format

2. Model Training
   - Trained using Random Forest, Naive Bayes, and KNN
   - Used 10-fold cross-validation for evaluation

3. Prediction & Evaluation
   - Compared model accuracies
   - Selected the best performing model (Naive Bayes)

Results
- Naive Bayes achieved the highest accuracy at 85% 
- All models demonstrated strong predictive performance
This project proves that machine learning can effectively assist in early diagnosis of heart diseases, potentially saving lives through timely interventions.

Contributions
This project was developed as part of a data mining academic assignment. Special thanks to the UCI repository and WEKA developers.

Contact
Archie Chadha
Email: archiechadha12@gmail.com | Linkedin: https://www.linkedin.com/in/archie-chadha-1869ba281/

> ⭐ If you find this project useful, feel free to star this repo and connect with me!
