# Literature Review

Approaches or solutions that have been tried before on similar projects.

**Summary of Each Work**:

- **Source 1**: Jin H, Lu Y, Harris ST, Black DM, Stone K, Hochberg MC, Genant HK (2004). Classification algorithms for hip fracture prediction based on recursive partitioning methods. *Med Decis Making 24*(4):386-98. doi: 10.1177/0272989X04267009. PMID: 15271277.

  - **[PubMed](https://pubmed.ncbi.nlm.nih.gov/15271277/)**
  - **Objective**: cost-saving classification approach using 43 predictive variables for 5-year hip fracture risk with equivalent diagnostic utility as the use of a robust optimum classification rule 
  - **Methods**: generation of a cost-saving classification rule and conduction of a validation study
  - **Outcomes**: cost-saving classification rule is statistically non-inferior to the robust optimum classification rule
  - **Relation to the Project**: hints for variable selection based on variable importance, theoretical background on variables and decision making

- **Source 2**: [Osteoporosis in Women and Men]

  - **[Kaggle](https://www.kaggle.com/code/aqsasadaf/osteoporosis-in-women-and-men)**
  - **Objective**: Research questions:
                  1. Examining the difference between men and women for osteoporosis risk. 
                  2. Examining the age at which fracture is most common for females and males.
                  3. Examining the effect of age, weight and height on BMD score.
  - **Methods**: EDA -> Data Preprocessing (Scaling, Encoding) -> Regression analysis: Ridge, Lasso, DecisionTree, RandomForest, XGBOOST
  - **Outcomes**: Linear regression had the best performance (R2, MSE) 
  - **Relation to the Project**: provides some framework for building regression models for osteoporosis data analysis

- **Source 3**: [Stroke Prediction Using Machine Learning]

  - **[Kaggle](https://www.kaggle.com/code/lcchennn/stroke-prediction-using-machine-learning/notebook)**
  - **Objective**: Analyze health data for feature selection and stroke prediction
  - **Methods**: Scikit-learn, Logistics Regression, SVM, RandomForestClassifier, XGBoost classifier, ROC/AUC score, confusion matrix
  - **Outcomes**: Random Forest performed the best in terms of accuracy
  - **Relation to the Project**: (National Health & Nutrition Examination Survey) dataset has a similar structure to SOF dataset
              - provides some method for balancing dataset which could be useful for our own imbalanced dataset
              - feature selection and prediction are also included in this analysis
              - structure is similar to our intended analysis structure
