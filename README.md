 **FinGuard**: \
 Credit Risk & Default ClassifierLive App: [(https://capstone-project-npoqfheykgqtnfpzn8hga4.streamlit.app/)]📌 
 
 
 
**Project Overview** \
 FinGuard is an end-to-end machine learning solution designed to identify high-risk loan applicants. 
 The project addresses the challenge of "messy" financial data by implementing a self-healing pipeline and an optimized Random Forest model prioritized for Recall.🛠️ 
 
**Key Features**
 
 Data Cleaning: \
 Automated handling of impossible outliers (e.g., $25M income) and missing values using Median Imputation.
 
 Feature Engineering: \
 Implementation of a Debt-to-Income (DTI) ratio to capture financial leverage.
 
 Risk Optimization: \
 Strategic threshold shifting to 0.3 and class weighting to prioritize capital preservation.
 
 📊 Performance SummaryMetric
 
**Recall (Default): Increased from 71% to 87%**

This is the most critical improvement in your project. By increasing the recall for the "Default" class (Class 1) by 16%, the model now identifies significantly more high-risk applicants, directly reducing the bank's exposure to bad debt.

**Precision (Safe): Increased from 86% to 92%**

The model has become much more reliable when it gives a "Safe" (Class 0) recommendation. With a 6% increase in precision for approvals, loan officers can have higher confidence that the applicants cleared by the system are truly creditworthy.

**Overall Accuracy: Decreased from 79.5% to 76.0%**

The 3.5% drop in accuracy was a deliberate trade-off. By lowering the threshold to 30%, the model became more "conservative," leading to more false alarms but fewer missed defaults.
