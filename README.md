
Heart Failure Prediction
A machine learning project that predicts patient mortality caused by heart failure using clinical records. Built using Support Vector Machine (SVM) and Artificial Neural Network (ANN).

📌 Problem Statement
Heart failure is one of the leading causes of death globally. Early prediction of patient mortality using clinical data can help doctors make better treatment decisions. This project builds a binary classification model to predict whether a patient will survive based on medical features.

📂 Dataset

Source: Clinical heart failure records
Features: 12 clinical features including age, anaemia, creatinine phosphokinase, diabetes, ejection fraction, high blood pressure, platelets, serum creatinine, serum sodium, sex, smoking, time
Target: DEATH_EVENT (0 = Survived, 1 = Died)


🛠️ Technologies Used

Python
Pandas, NumPy
Scikit-learn (SVM, StandardScaler)
Keras / TensorFlow (ANN)
Matplotlib, Seaborn


⚙️ Methodology

Exploratory Data Analysis (EDA) — Distribution plots, correlation heatmap, feature analysis
Preprocessing — StandardScaler normalization, feature selection based on correlation
Model 1: SVM — Support Vector Machine with RBF kernel
Model 2: ANN — Artificial Neural Network built with Keras

Dropout regularization to prevent overfitting
EarlyStopping to optimize training


Evaluation — Precision, Recall, F1-Score, Confusion Matrix


📊 Results
ModelAccuracy
SVM~77%
ANN~75%
