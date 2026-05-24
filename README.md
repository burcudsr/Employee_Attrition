# 🏢 Employee Attrition Prediction

This project focuses on predicting employee attrition using machine learning techniques, developed during the **Kaggle Playground Series - Season 3, Episode 3**. The goal is to identify factors that influence employees' decisions to leave the company, allowing for proactive retention strategies.

### 🚀 Live Demo
Explore the interactive prediction model here: https://huggingface.co/spaces/bdaser/Employee_Attrition

### 📊 Dataset & Preprocessing
The model was trained on a comprehensive dataset capturing various employee attributes. Key preprocessing steps include:
* **Data Transformation**: Categorical variables were encoded to convert them into a machine-readable format.
* **Feature Scaling**: To ensure all numerical features contribute equally to the model's predictive power, `MinMaxScaler` was applied to normalize the data within the [0, 1] range.
* **Feature Engineering**: Relevant features were selected to enhance model focus on key indicators of attrition.

### 🤖 Model Performance
After evaluating multiple classification models, the selected model demonstrates strong performance in distinguishing between employees who stay and those who may leave.

| Accuracy | Precision | Recall | F1-Score |
| :--- | :--- | :--- | :--- |
| 0.884 | 0.892 | 0.875 | 0.883 |
