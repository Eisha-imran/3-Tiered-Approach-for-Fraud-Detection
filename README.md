# 3-Tiered-Approach-for-Fraud-Detection
### This project addresses this challenge by developing a fraud detection system that uses machine learning and data analytics to uncover fraud


## Fraud Detection Project Summary 
### Introduction
Many transactions happen digitally these days. Fraud, ranging from credit card scams to identity theft, results in substantial financial losses annually. For example, the Federal Trade Commission reported that U.S. consumers lost over $10 billion to fraudsters in 2023.
This emphasizes the need for robust fraud detection systems to identify and mitigate suspicious activities. Legacy fraud detection methods sometimes fall short due to their reactive rather than proactive nature or the ability of fraudsters to figure out and circumvent measures put in place. Rule-based systems, for example, may not be all-encompassing. It is also difficult to scale as rules can differ for different scenarios and business use cases requiring frequent updates. 

This project addresses this challenge by developing a fraud detection system that uses machine learning and data analytics to uncover fraud. Machine learning methods such as anomaly detection (to identify customers' baselines and flag significant deviations from their usual patterns) and classification models (trained from large-scale historical data to recognize fraud patterns beyond the human 3D/4D view), can improve the ability to identify fraudulent transactions. Integrating them with real-time systems can prevent fraud as they happen.

Rather than completely replace legacy systems or use only one machine learning method to detect fraud, our project provides a hybrid architecture to fraud detection systems, utilizing results from a rule-based system, a classification model, and an anomaly detection model.

### Project objectives

1.	Data Ingestion and Processing: Develop a system to ingest and process high volumes of transaction data, capturing essential information like user information, transaction amounts, geolocation etc. Engineer relevant features that can effectively distinguish legitimate from fraudulent transactions
2.	Model development: Build models from a set of rules, and different ML algorithms to detect patterns and anomalies
3.	Fraud reporting: Report the results from the rule-based, anomaly detection, and classification models. Make decisions from all three models for suspicious transactions that should be blocked outright, sent for manual authorization, or flagged for further investigation. 

### Methodology

1.	Data Collection: Aggregate historical transaction data from financial institutions ensuring compliance with data privacy regulations
2.	Preprocessing: Clean & normalize the data to prepare it for analysis
3.	Feature engineering: Develop features to enhance model accuracy
4.	Model Training: Build three models: a rules-based model, an anomaly detection model, and a classification model. Evaluate the results of the ML models to select the best training parameters. 
5.	Deployment: Deploy the results from all models for decision making

### Expected outcomes

By implementing this system, we anticipate a significant improvement in detecting fraudulent transactions enabling businesses to reduce fraud risk and minimize financial losses.

### Conclusion
As financial transactions grow digitally, the sophistication of fraudulent schemes evolves. Our project aims to stay ahead by leveraging multiple methods to detect fraud in one hybrid system. This improves the safeguarding of financial assets and fosters a secure environment for businesses and customers.

### Next steps
Integrate the fraud detection framework into a real-time transaction monitoring system to analyze incoming transactions in real-time, provide alerts and enable immediate action on suspicious transactions

