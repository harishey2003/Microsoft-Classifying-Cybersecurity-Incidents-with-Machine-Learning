# Microsoft-Classifying-Cybersecurity-Incidents-with-Machine-Learning
# Introduction:
### Introduction  
**Classifying Cybersecurity Incidents with Machine Learning** leverages advanced algorithms to automatically identify and categorize cybersecurity threats. By analyzing patterns and anomalies in vast amounts of security data, machine learning enhances the speed, accuracy, and efficiency of incident classification. This approach empowers organizations to respond proactively to threats, reduce manual effort, and strengthen their overall security posture in an ever-evolving digital landscape.
# Objective:
  The objective of **Classifying Cybersecurity Incidents with Machine Learning** is to develop an automated system that can:  
1. **Identify and classify** cybersecurity incidents based on their type and severity.  
2. **Enhance response time** by quickly detecting patterns and anomalies in security data.  
3. **Reduce manual effort** in incident analysis through intelligent automation.  
4. **Improve accuracy** in threat detection and categorization.  
5. **Strengthen security posture** by enabling proactive threat mitigation.  

This approach aims to make cybersecurity systems more efficient, scalable, and resilient against evolving cyber threats.
# Dataset Overview:
  The dataset consists of labeled cybersecurity incident records with key attributes:  

- **Incident Type**: Malware, phishing, DDoS, etc.  
- **Timestamp**: Date and time of incidents.  
- **Source/Target IP**: Attack origin and target.  
- **Attack Vector**: Methods used for attacks.  
- **Severity Level**: Low, Medium, High.  
- **Log Details**: System logs and alerts.  

**Sources** include network logs, IDS reports, and public datasets like **CICIDS2017** or **NSL-KDD**. The target variable represents the type of cybersecurity incident.
# Business Use Cases:
1. **Incident Detection & Classification**: Automate identification of cyber threats like malware, phishing, or DDoS attacks.  
2. **Threat Prioritization**: Classify incidents by severity (Low, Medium, High) for faster response.  
3. **Anomaly Detection**: Detect unusual patterns in network traffic or user behavior.  
4. **Automated Response Systems**: Trigger real-time alerts or actions for critical threats.  
5. **Resource Optimization**: Reduce manual analysis and improve security team efficiency.  
6. **Compliance & Reporting**: Ensure regulatory compliance by accurately logging and categorizing incidents.  
# Model Comparison with Accuracy Score:
The table below provides an overview of the performance of various models, summarized through their Accuracy scores. The comparison highlights the ranking and effectiveness of each model in predicting sales.
Here is the data presented as a table:

| **Model**               | **Accuracy** |
|-------------------------|-------------:|
| Logistic Regression     | 0.6509       |
| Decision Tree           | 0.6743       |
| Random Forest           | 0.6756       |
| Gradient Boosting       | 0.6712       |
| SVM                     | **0.6952**   |
| KNN                     | 0.6694       |

**Best Model**: **SVM** with Accuracy **0.6952**.
# Result:
This project demonstrated the successful application of machine learning in classifying cybersecurity incidents using historical data. The SVM (Support Vector Machine) model provided the best performance, achieving a strong balance between accuracy, precision, and recall across all incident categories. By utilizing techniques such as hyperparameter tuning (via RandomizedSearchCV) and exploring feature engineering, the model achieved an improved Macro-F1 score, making it highly effective in handling the complexities of cybersecurity data.Further refinements, including additional hyperparameter optimization and feature engineering, have the potential to enhance the model’s performance even further. This approach provides a valuable tool for Security Operation Centers (SOCs) to prioritize and address cybersecurity threats more efficiently, ultimately improving response times and threat mitigation.
