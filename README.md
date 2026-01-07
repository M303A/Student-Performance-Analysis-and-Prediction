PROJECT TITLE : Student Performance Analysis & Score Prediction

📌 Project Overview

Educational institutions often struggle to identify students who may underperform until it is too late for meaningful intervention. This project analyzes student behavioral data to understand the key factors influencing academic performance and builds predictive models to estimate students’ final scores.

The project combines exploratory data analysis, business interpretation, and machine learning to deliver actionable insights and a reliable prediction framework.

📌 Objectives

- Analyze the impact of behavioral factors on student performance

- Identify which factors influence scores the most when analyzed independently

- Build and compare multiple machine learning models to predict student scores

- Select the best-performing model using appropriate regression metrics

The dataset contains student-level academic and behavioral information. 

| Feature                 | Description                            |
| ----------------------- | -------------------------------------- |
| weekly_self_study_hours | Hours spent on self-study per week     |
| attendance_percentage   | Percentage of classes attended         |
| class_participation     | Level of classroom engagement          |
| total_score             | Final academic score (target variable) |

Methodology


1️⃣ 
Exploratory Data Analysis (EDA)

Descriptive statistics and distributions

Correlation analysis

Independent (factor-wise) analysis of each behavioral variable

2️⃣ Factor-Wise Analysis

Each factor was analyzed separately using:

Visualizations

Group-based comparisons

Business interpretation

Key Insight Summary:

Attendance → Strongest impact

Class Participation → High impact

Study Hours → Moderate impact with diminishing returns

3️⃣ Data Preparation

Feature selection based on availability before final exams

Train–test split

Feature scaling where required

4️⃣ Baseline Prediction

A baseline model using mean score prediction was created to establish a benchmark and justify the use of machine learning models.

5️⃣ Machine Learning Models

The following regression models were trained and evaluated:

Linear Regression

Decision Tree Regressor

Random Forest Regressor

Gradient Boosting Regressor


6️⃣ Model Evaluation

Models were evaluated using:

MAE (Mean Absolute Error)

RMSE (Root Mean Squared Error)

These metrics were chosen for their interpretability and relevance to real-world decision-making.

7️⃣ Model Selection

Gradient Boosting achieved the lowest RMSE and was selected as the final model due to its ability to capture non-linear relationships while maintaining strong predictive accuracy.

8️⃣ Model Explainability

Feature importance analysis was performed

Results were interpreted alongside exploratory insights

The dominance of certain features was explained in the context of model optimization vs real-world interpretation

9️⃣ Error Analysis

Distribution of prediction errors

Error patterns across score ranges

Identification of cases where the model performs less accurately

📈 Sample Prediction

The final model can be used to predict a student’s expected score based on behavioral inputs such as attendance, study habits, and participation—supporting early intervention strategies.

🧾 Key Findings

Attendance is the strongest behavioral indicator of academic success

Engagement (participation) significantly improves performance consistency

Study hours matter, but excessive hours show diminishing returns

Ensemble models outperform simpler models for this dataset

⚠️ Limitations

Dataset does not include socioeconomic or prior academic history

Results are based on available behavioral factors only

Feature importance reflects model behavior, not causality

🔮 Future Improvements

Add time-based performance tracking

Include external factors (previous grades, demographics)

Deploy the model as an early warning system

Build an interactive dashboard (Power BI / Streamlit)

🛠 Tools & Technologies
- Python

- Pandas, NumPy

- Matplotlib

- Scikit-learn

- Google Colab



📌 Conclusion

This project demonstrates a complete analytics workflow—from understanding the problem to delivering interpretable predictions. It highlights how data-driven insights can support timely academic interventions and improve student outcomes.
