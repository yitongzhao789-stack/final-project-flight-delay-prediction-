# final-project-flight-delay-prediction-
Overview
This project builds a logistic regression model to classify whether a flight is delayed or not based on weather and flight data.
Before formal modeling, we need to perform preprocessing operations such as data cleaning and numerical standardization.

Workflow Summary

Feature Engineering ：
One-hot encoding for categorical features
Combine encoded features into training set

Model Training ：
Split data (80% training, 20% testing)
Train a Logistic Regression model
Evaluate using accuracy, recall, and ROC-AUC

Model Evaluation ：
Confusion Matrix
ROC Curve visualization

Deployment ：
Push cleaned source code and requirements file to GitHub
<img width="1331" height="1146" alt="image" src="https://github.com/user-attachments/assets/26b9c716-358f-4123-b473-f93a890b325d" />
<img width="1339" height="1339" alt="image" src="https://github.com/user-attachments/assets/22387bcf-0e0d-4444-8b18-6903eb747995" />

Conclusion:
As can be seen from the figure, the model has high precision for non-delayed flights, but low recall for delayed flights, indicating a class imbalance.
Future improvements may include oversampling, balancing, or trying ensemble models.
Repository Link：
https://github.com/yitongzhao789-stack/final-project-flight-delay-prediction-/edit/main/README.md
