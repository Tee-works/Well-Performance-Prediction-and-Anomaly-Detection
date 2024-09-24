# Well-Performance-Prediction-and-Anomaly-Detection

### **Project Overview**
This project focuses on predicting the performance of wells in terms of **gas, oil, and water production** and detecting anomalies that indicate unusual well behavior. By leveraging machine learning models, the goal is to provide accurate production forecasts and highlight wells that deviate significantly from normal operational patterns. This enables informed decision-making for optimizing well operations in the oil and gas industry.

### **Objectives**
- **Predict Well Production**: Develop a model that accurately predicts gas, oil, and water production based on historical data.
- **Anomaly Detection**: Identify wells that exhibit unusual production behavior using anomaly detection techniques.
- **Provide Actionable Insights**: The project aims to offer insights that can help with operational efficiency, resource management, and anomaly investigation.

### **What Was Done**
- **Data Preparation**: Collected and cleaned well production data, handling missing values and engineering new features, such as cumulative production and average monthly production for gas, oil, and water.
- **Predictive Modeling**: Built and trained a **Random Forest model** to predict well production, with strong performance metrics indicating reliable predictions across the dataset.
- **Anomaly Detection**: Implemented an **Isolation Forest model** to detect wells with unusually high or low production. These wells were flagged as anomalies for further investigation.
- **Model Evaluation**: The models were validated using cross-validation techniques to ensure that predictions were consistent and generalizable.
- **Insights & Visualizations**: The project includes visualizations of production trends and highlights the differences between normal and anomalous wells.

### **Key Results**
- **Accurate Predictions**: The Random Forest model produced reliable predictions for gas, oil, and water production, helping to forecast future well performance.
- **Anomalous Wells Identified**: The anomaly detection process flagged several wells with extreme production values, which may require operational review or data validation.
- **Operational Insights**: The project offers insights into which wells are performing exceptionally well and which may have issues that need to be addressed.

### **Future Steps**
- **Investigate Anomalous Wells**: Further exploration of flagged anomalies to determine whether they indicate operational inefficiencies, equipment failures, or data issues.
- **Model Deployment**: Deploy the predictive model for real-time use in forecasting well production and detecting anomalies as new data comes in.
- **Data Validation**: Ensure that any flagged anomalies are not due to data errors or inconsistencies.

### **Conclusion**
This project successfully demonstrates the use of machine learning in the oil and gas sector for **well performance prediction** and **anomaly detection**. The models developed can support real-time operational decisions and provide valuable insights into well efficiency, allowing for improved resource management and potential cost savings.
