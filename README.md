\# 🩺 Hypertension Prediction using Machine Learning



This project uses machine learning techniques to predict the likelihood of hypertension based on health indicators. 

The goal is to explore multiple classification models and evaluate their performance in terms of accuracy and interpretability.



---



\## 📊 Dataset



The dataset used for this project was sourced from a structured healthcare record containing features such as:



\- Age

\- BMI

\- Smoking status

\- Physical activity

\- Alcohol intake

\- Blood glucose

\- ...and several other lifestyle and clinical indicators.



---



\## 🔍 Exploratory Data Analysis (EDA)



EDA steps included:



\- Checking for missing values and imputation

\- Label encoding of categorical variables

\- Correlation heatmap to assess multicollinearity

\- Outlier visualization using boxplots

\- Class balance check



---



\## ⚙️ Models Trained



The following \*\*6 models\*\* were trained and evaluated:



| Model                          | Test Accuracy | Cross-Validation Accuracy |

|-------------------------------|---------------|---------------------------|

| Logistic Regression           | 0.96          | 0.96                      |

| K-Nearest Neighbors (KNN)     | 0.93          | 0.91                      |

| Decision Tree                 | 0.93          | 0.92                      |

| Support Vector Machine (SVM)  | 0.97          | 0.96                      |

| Naive Bayes                   | 0.94          | 0.93                      |

| \*\*Random Forest\*\*             | \*\*0.97\*\*      | \*\*0.97\*\*                  |



---



\## ✅ Final Model



🎯 The \*\*Random Forest Classifier\*\* achieved the best overall performance:

\- \*\*Test Accuracy:\*\* 96.7%

\- \*\*5-Fold Cross-Validation Accuracy:\*\* 97.2%

\- \*\*Precision/Recall/F1-score:\*\* ~0.97 across classes



---



\## 📈 Visualizations



\- Confusion matrices for each model

\- Feature importance from Random Forest

\- Accuracy comparison bar chart (Test vs CV)



---



\## 💡 Key Learnings



\- Feature scaling and encoding have a significant impact on model performance.

\- Random Forest is robust and performs well across imbalanced datasets.

\- Cross-validation helped ensure the model's generalizability.



---



\## 🛠️ Technologies Used



\- Python

\- Pandas, NumPy

\- Matplotlib, Seaborn

\- Scikit-learn

\- Jupyter Notebook



---

