# Bankruptcy Prediction
 Data Science Institute - Cohort 4 - Team 25 Project

## Members
[Erfan Nazari](https://github.com/Erfan-Nazari), [Parisa Ghotbi](https://github.com/Parisaghotbi), [Marjan Rajabi](https://github.com/marjanrajabi437), [Fatemeh Safaei](https://github.com/Safaei-Fatemeh)


## Project Overview: Bankruptcy Prediction
This repository contains the implementation of a machine learning project to classify companies as "Bankrupt" or "Not Bankrupt" based on financial indicators. The dataset used for this project is sourced from [Kaggle](https://www.kaggle.com/datasets/fedesoriano/company-bankruptcy-prediction).
The goal of this project is to predict the likelihood of a company's bankruptcy using various financial ratios and indicators. The dataset spans data from 1999 to 2009 and includes 95 features, offering rich insights into financial health and corporate governance.
The data were collected from the Taiwan Economic Journal for the years 1999 to 2009. Company bankruptcy was defined based on the business regulations of the Taiwan Stock Exchange. The data was obtained from UCI Machine Learning Repository: https://archive.ics.uci.edu/ml/datasets/Taiwanese+Bankruptcy+Prediction






## Team Videos



## Outline

- [data/](https://github.com/Erfan-Nazari/DSI_Team_Project-Bankruptcy_Prediction/tree/main/data)
  - [processed/](https://github.com/Erfan-Nazari/DSI_Team_Project-Bankruptcy_Prediction/tree/main/data/processed)
  - [raw/](https://github.com/Erfan-Nazari/DSI_Team_Project-Bankruptcy_Prediction/tree/main/data/raw)
  - [best_model/](https://github.com/Erfan-Nazari/DSI_Team_Project-Bankruptcy_Prediction/tree/main/data/best_model)
- [experiments/](https://github.com/Erfan-Nazari/DSI_Team_Project-Bankruptcy_Prediction/tree/main/experiments)
- [models/](models)
- [reports/](reports)
- [src/](src)
- README.md
- .gitignore



## :moneybag: Business Case and Value

Corporate bankruptcy prediction is a critical aspect of financial risk management for businesses, investors, and financial institutions. This project provides a robust and interpretable framework for identifying early warning signs of financial distress in companies, enabling stakeholders to make informed decisions.





#### Business Case:

- Early Risk Detection:

  - Helps businesses and investors identify potential financial risks early, allowing for timely interventions and strategic adjustments.
  - Enables creditors and lenders to assess the creditworthiness of companies before extending loans or investing capital.

- Efficient Resource Allocation:

  - Financial institutions can prioritize resources for companies showing signs of distress and develop customized support strategies to mitigate potential losses.

- Regulatory Compliance:

  - Governments and regulators can use such models to monitor and enforce corporate governance standards, reducing systemic risks in the economy.

- Improved Decision-Making:

  - Companies can leverage insights from the model to improve financial health and mitigate operational inefficiencies.

#### Value Delivered: 

- Stakeholder Protection:

  - Protects investors and creditors from unexpected financial losses through reliable bankruptcy risk assessments.

- Economic Stability:

  - Reduces the risk of large-scale corporate failures, contributing to overall economic stability.

- Cost Reduction:

  - Automates the bankruptcy prediction process, minimizing reliance on manual evaluations and reducing operational costs.

- Strategic Planning:

  - Supports businesses in aligning long-term strategies with financial sustainability, ensuring robust growth.

- Customizable and Scalable:

  - Adaptable for various industries, geographies, and economic conditions, making it a versatile tool.

## Analyses Conducted :mag:

To achieve the project goals, the following analyses were conducted:

### 1. Exploratory Data Analysis (EDA):

Visualized distributions of features and the target variable.
Identified class imbalance in the dataset.
Explored correlations between features to uncover potential multicollinearity issues.

### 2. Feature Selection:

Applied statistical and machine learning-based techniques to identify the most relevant features.
Reduced dimensionality to improve model performance and interoperability.

### 3. Model Training/Testing Without SMOTE:

Trained several classification models (e.g., Logistic Regression, Random Forest, Gradient Boosting) on the original dataset.
Evaluated models using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.

### 4. Model Training/Testing With SMOTE (Addressing Class Imbalance):

Applied Synthetic Minority Over-sampling Technique (SMOTE) to balance the dataset.
Retrained the models and compared performance with those trained on the imbalanced dataset.

### 5. Model Evaluation and Selection:

Selected the best-performing model based on evaluation metrics.
Stored the trained model in the best_model/ directory for future use.

### 6. Report Generation:

Summarized findings and insights in structured reports available in the reports/ directory.

