# AI Tutor – Personalized Student Learning Recommendation System

## Overview

AI Tutor is an intelligent educational recommendation system designed to provide personalized learning guidance to students based on their academic performance, study habits, and learning behavior.

The system analyzes student data and predicts learning levels while generating customized study plans, topic recommendations, and performance insights.

This project is developed as part of the **Artificial Intelligence Lab Project** and is based on the **PEAS Framework and Task Environment Analysis** for an AI Tutor system.

---

## Objectives

* Analyze student learning performance.
* Predict student proficiency levels.
* Generate personalized study recommendations.
* Improve student engagement and learning outcomes.
* Visualize academic performance using interactive dashboards.

---

## Features

### Student Assessment

* Input academic scores.
* Record study hours and attendance.
* Track learning preferences.

### AI-Based Prediction

* Predict student level:

  * Beginner
  * Intermediate
  * Advanced

### Personalized Recommendations

* Weak topic identification.
* Customized study plans.
* Learning resource suggestions.

### Data Visualization

* Performance charts.
* Subject-wise analysis.
* Learning progress reports.

### Explainable AI

* Provides reasoning behind recommendations.
* Displays factors influencing predictions.

---

## PEAS Framework

### Performance Measures

* Recommendation Accuracy
* Student Improvement Rate
* User Satisfaction Score
* Response Time
* Learning Goal Achievement Rate

### Environment

Schools, colleges, universities, and online learning platforms with students of varying abilities and learning styles.

### Actuators

* Study Plan Generator
* Learning Resource Recommender
* Progress Notifications
* Performance Feedback System
* Quiz Recommendation Engine

### Sensors

* Quiz Scores
* Assignment Results
* Learning History
* Subject Preferences
* Study Time Records
* Student Feedback

---

## Environment Classification

| Dimension           | Classification       |
| ------------------- | -------------------- |
| Observability       | Partially Observable |
| Agents              | Single-Agent         |
| Determinism         | Stochastic           |
| Episodic/Sequential | Sequential           |
| Static/Dynamic      | Dynamic              |
| Discrete/Continuous | Continuous           |

---

## Technology Stack

### Frontend

* Streamlit

### Backend

* Python

### Machine Learning

* Scikit-Learn
* Decision Tree Classifier
* Random Forest Classifier

### Data Processing

* Pandas
* NumPy

### Visualization

* Plotly
* Matplotlib

---

## Project Structure

```text
AI-Tutor-Personalized-Learning-System/

├── app.py
├── data/
│   └── student_dataset.csv
├── models/
│   ├── train_model.py
│   └── model.pkl
├── utils/
│   ├── preprocessing.py
│   ├── recommendation.py
│   └── explainability.py
├── requirements.txt
└── README.md
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/huzaifali835/AI-Tutor-Personalized-Learning-System.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
streamlit run app.py
```

---

## Future Enhancements

* Real-time student analytics.
* AI-powered chatbot tutor.
* Adaptive learning paths.
* Learning resource integration.
* Multi-language support.
* Deep learning-based recommendations.
