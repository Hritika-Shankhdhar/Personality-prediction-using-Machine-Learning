# Personality-prediction-using-Machine-Learning

📋 Project Overview

This project predicts whether a person is an Introvert or Extrovert based on behavioral and social activity data.
Using supervised learning models such as Logistic Regression and Random Forest, the project identifies personality traits based on measurable factors like social event attendance, time spent alone, and stage fear.

🎯 Objective

To build and compare machine learning models that classify individuals into two personality types — Introvert or Extrovert — and identify which social and psychological factors most strongly influence these traits.

📂 Dataset

Size: 2,900 rows × 8 columns

Features include:

Time_spent_Alone

Stage_fear

Social_event_attendance

Going_outside

Drained_after_socializing

Friends_circle_size

Post_frequency

Personality (Target: Introvert = 0, Extrovert = 1)

⚙️ Tech Stack

Language: Python

Libraries:
NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn

Environment: Jupyter Notebook / VS Code

🔍 Methodology

Data Cleaning & Preprocessing

Handled categorical variables using mapping (Yes/No → 1/0)

Scaled numerical features using StandardScaler

Split dataset (80% training, 20% testing)

Exploratory Data Analysis (EDA)

Boxplots, Countplots, Heatmaps to visualize trends

Observed strong correlations between:

Time spent alone ↔ Personality

Friend circle size & Post frequency ↔ Extroversion

Model Building

Logistic Regression

Random Forest Classifier

Voting & Stacking Ensemble Classifiers

Evaluation Metrics

Accuracy, Precision, Recall, F1-score, ROC-AUC

📊 Results

| Model               | Accuracy | AUC Score |
| ------------------- | -------- | --------- |
| Logistic Regression | 0.92     | 0.929     |
| Random Forest       | 0.92     | 0.945     |
| Voting Classifier   | 0.93     | 0.943     |
| Stacking Classifier | 0.93     | 0.944     |

✅ Random Forest and Ensemble models performed the best, achieving an accuracy of ~93% and AUC around 0.94.

💡 Key Insights

People who spend more time alone and feel drained after socializing tend to be Introverts.

Those who attend more events and have a larger friend circle are Extroverts.

Stage fear, time spent alone, and social activity were the most important predictors.

📘 Conclusion

Machine learning can effectively identify personality traits based on behavioral data.
Among all models, Random Forest and Stacking Classifier achieved the highest accuracy and interpretability.
