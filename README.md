# Machine-Learning---Credit-risk-management-

# Project Overview: Credit Risk Management with XGBoost and Neural Network

Welcome to my project dedicated to advancing credit risk management through the utilization of cutting-edge machine learning methodologies, specifically XGBoost and Neural Networks. This project aims to offer a comprehensive solution for financial institutions and risk analysts to effectively assess and mitigate credit risk.

### Objective:
The primary objective of this project is to develop robust models that accurately predict credit risk, thereby assisting in making informed lending decisions and reducing the likelihood of default.

### Methodology:

### Data Preparation:
I begin by randomly selecting 20% of observations from the "train_labels.csv" dataset and merging them with "train_data.csv".
The dataset is then thoroughly explored to understand its size, feature data types, and overall structure.
Missing values are handled through imputation, where numerical columns are replaced with mean values and categorical columns with mode values.
Categorical variables are encoded using One-Hot Encoding for compatibility with machine learning algorithms.
New features are defined to enhance the predictive capabilities of the models.
The dataset is split into training and testing subsets to facilitate model evaluation.

### XGBoost Setup:
I leverage the powerful XGBoost algorithm for credit risk prediction.
Feature Importance analysis is conducted using default parameters as well as customized parameters to identify significant predictors.
Features with importance scores above 0.5 are retained for further analysis and model training.
Grid Search optimization is performed to fine-tune the XGBoost model using the selected features.
Model interpretation is enhanced through SHAP (SHapley Additive exPlanations) Analysis, visualized using Bee Swarm and Waterfall graphs.

### Neural Network:
Data preprocessing focuses exclusively on features selected during the XGBoost phase to streamline model input.
A Neural Network approach is implemented to further enhance credit risk assessment.

### Strategy Evaluation:
I evaluate different risk management strategies by analyzing portfolio default rates across various time frames for each strategy.
