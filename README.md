# Mental Health Prediction at MMU

This repository contains the final project report for **Bachelor of Computer Science (Hons) Data Science** at Multimedia University. The project investigates mental health dynamics, including depression, anxiety, and stress, among university students over an academic semester. It applies machine learning techniques to predict mental health statuses based on sociodemographic and academic factors.

## Project Overview
The study aims to understand temporal changes in mental health conditions among students at MMU, focusing on stress, anxiety, and depression. The study also compares different machine learning models in predicting these conditions.

## Objectives
1. **Temporal Changes Analysis**: Examine changes in depression, anxiety, and stress over a 4-month academic semester.
2. **Associations with Sociodemographic Factors**: Investigate correlations with sociodemographic and academic characteristics.
3. **Model Comparison**: Evaluate the performance of LightGBM, SVM, Random Forest, Logistic Regression, and Naive Bayes in predicting mental health statuses.

## Dataset
Data was collected from MMU students over three phases of the semester using mental health assessment tools:
- **DASS-21** (Depression, Anxiety, Stress Scale - 21 Items)
- **PSS** (Perceived Stress Scale)
- Sociodemographic and academic characteristics

### Data Collection Phases
1. **Early Semester** (Week 3-7)
2. **Mid Semester** (Week 6-10)
3. **End of Semester** (Examination week)

### Note
*The dataset is not included in this repository due to privacy concerns.*

## Key Steps and Findings
### 1. Data Preprocessing
- Handled missing values, duplicates, and integrated data across phases.
- Applied label encoding, SMOTE, and polynomial feature engineering.

### 2. Exploratory Data Analysis (EDA)
- Analyzed distributions of demographic and mental health scores.
- Identified correlations between financial difficulties, sleep, smoking, and mental health scores.

### 3. Model Training and Evaluation
Five machine learning models were evaluated:
- **Support Vector Machine (SVM)**
- **Random Forest (RF)**
- **Logistic Regression (LR)**
- **Naive Bayes (NB)**
- **Light Gradient Boosting Machine (LightGBM)**

### 4. Performance Metrics
Models were evaluated using:
- Accuracy
- Precision
- Recall
- F1 Score

### Results
- While traditional models like **Random Forest** and **SVM** performed well, **LightGBM** showed unique strengths in predicting anxiety across phases, particularly between end and early semester.

## Conclusion and Future Work
The study demonstrates the potential of machine learning models in tracking mental health trends over time. Future work could involve larger datasets, advanced feature engineering, and real-time data collection for more granular analysis.

## License
This project is for educational purposes as part of the final year project at MMU.

