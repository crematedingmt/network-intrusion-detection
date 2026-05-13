# Machine Learning Model
Built and optimized a machine learning model for network intrusion detection.

# What
This project builds and evaluates machine learning models to classify network connections from the NSL-KDD dataset into five categories: Normal, DoS, Probe, R2L, and U2R. The objective is to maximize macro F1-score on KDDTest+. Focus areas: handling class imbalance, feature preprocessing, model selection/tuning, and reproducible evaluation (cross-validation vs test).

# How to Run
Create environment:
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows

Install deps:
pip install -r requirements.txt

Run pipeline (example):
python src/train_and_evaluate.py

# Why
Because imbalanced, real-world security data is hard and interesting. This assignment teaches model training, imbalance strategies (SMOTE, class weights), evaluation (CV vs test), and critical thinking about trade-offs (precision vs recall).

# License
No license. Institution’s guidance is used.

# Notes & Constraints
Competition metrics: macro F1-score on KDDTest+.
Cross-validation on training set for model selection/tuning.
Code is reproducible. 
