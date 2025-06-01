# Bank Customer Churn Prediction

This project predicts whether a bank customer will churn using demographic and transactional data. Built for the Applied Machine Learning course at UT Dallas, it compares multiple classification models and demonstrates preprocessing, feature selection, and performance evaluation.

## Dataset
- Source: [Kaggle – Churn_Modelling.csv]
- Features: CreditScore, Geography, Gender, Age, Tenure, Balance, etc.
- Target: `Exited` (1 = Churned, 0 = Stayed)

## Project Objectives
- Identify key drivers of customer churn.
- Compare performance across Logistic Regression, Decision Trees, and ANN.
- Recommend best-performing model for bank retention strategies.

## Tools & Technologies
- Python, Pandas, Scikit-learn, TensorFlow/Keras
- Jupyter Notebook
- Matplotlib, Seaborn for visualization

## Models Evaluated
- Logistic Regression (~81% accuracy)
- Decision Tree (~79% accuracy)
- Artificial Neural Network (~85% accuracy)

## Evaluation Metrics
- Accuracy, Precision, Recall, F1 Score
- ROC-AUC, Confusion Matrix, Precision-Recall curves

## Key Insights
- Tenure around year 10 shows both highest churn and highest loyalty.
- ANN provides best balance of precision/recall.
- Decision Tree offers high recall, suitable if false negatives are costlier.

## Files
- `Project_Code_Aml.ipynb`: Full modeling code
- `Churn_Modelling.csv`: Dataset
- `Project_Report_Nipun_Chauhan.pdf`: Full report
- `Presentation_AML_Project.pdf`: Presentation slides

## Future Work
- Hyperparameter tuning for ANN
- Ensemble models (e.g., Random Forest, XGBoost)
- Deeper feature engineering using customer interaction data

## License
MIT License
