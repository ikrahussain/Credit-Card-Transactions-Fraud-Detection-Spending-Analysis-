# Credit-Card-Transactions-Fraud-Detection-Spending-Analysis-

This data analysis project used the Credit Card Fraud Detection dataset from Kaggle, which contains anonymised European credit card transaction data, including transaction amounts, timestamps, fraud classifications and behavioural features (V1–V28). The dataset was analysed as part of a real-world business scenario for the Global Bank Analytics Department, which wanted to improve fraud detection and gain better insight into customer spending behaviour. The main aim of the project was to identify fraud patterns, analyse spending trends over time, detect high-risk and unusual transactions and create interactive dashboards using SQL, Power BI and Tableau to support data-driven decision-making and improve fraud monitoring. 

 

---

## Table of Contents

- [Overview](#overview)  
- [Dataset](#dataset)  
- [Technologies Used](#technologies-used)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Analysis & Visualizations](#analysis--visualizations)  
- [Conclusion](#conclusion)  
- [Credits](#credits)  
- [License](#license)  

---

## Overview ## 

- **Motivation:**

I chose this dataset because credit card fraud detection is a real-world problem that has a significant financial impact on banks and customers. It provided an opportunity to work with a realistic financial dataset while applying SQL, Power BI and Tableau to solve a practical business problem. The project also allowed me to develop skills in analysing large datasets, identifying patterns and presenting insights through interactive dashboards.

- **Objective:**
The main objective of this project was to analyse historical credit card transaction data to improve fraud detection and understand customer spending behaviour. The analysis aimed to answer questions such as:

  - What percentage of transactions are fraudulent?
  - Are fraudulent transactions concentrated during specific time periods?
  - Which transaction amounts are most commonly associated with fraud?
  - What spending patterns and trends can be identified?
  - Which transactions should be considered high risk or suspicious?

- **Learning Outcomes:**

Through this project, I strengthened my skills in data cleaning, SQL querying, data visualisation and business intelligence reporting. I learned how to calculate key performance indicators, identify fraud patterns, analyse transaction trends, detect anomalies and outliers and design interactive dashboards in Power BI and Tableau. I also gained a better understanding of how data analysis can support fraud detection, risk management and business decision-making in the financial services industry.


---

## Dataset

Provide details about the dataset used:

- Source of the dataset:

The dataset used for this project is the Credit Card Fraud Detection dataset from Kaggle. It contains anonymised credit card transactions made by European cardholders and is widely used for fraud detection and machine learning research.

- Source: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

- Size of the Dataset:

The dataset contains:
  - Rows: 284,807 transactions
  - Columns: 31 variables


- Key Features/Columns Used:

The main columns used in the analysis include:
  - Time – The elapsed time (in seconds) between each transaction and the first transaction in the dataset.
  - Amount – The monetary value of each transaction.
  - Class – The fraud classification, where 0 = Non-Fraud and 1 = Fraud.
  - V1–V28 – Anonymised numerical features generated using Principal Component Analysis (PCA) to protect sensitive customer information while preserving patterns useful for fraud detection.

These features were used to analyse fraud rates, transaction amounts, spending behaviour, time-based trends, and high-risk transactions.

- Preprocessing and Cleaning

Before the analysis, the dataset was checked and prepared to ensure data quality. The preprocessing steps included:

Checking for missing (NULL) values.
  - Identifying and removing duplicate records where necessary.
  - Verifying the data types of each column.
  - Reviewing the distribution of fraud and non-fraud transactions.
  - Creating calculated fields for fraud rate, risk segmentation, and time-based analysis to support SQL queries and dashboard visualisations.

---

<h2>Technologies Used</h2>

<ul>
  <li><strong>Languages & Libraries:</strong> Python, Pandas, NumPy, SQL, Matplotlib, Seaborn</li>
  <li><strong>Tools:</strong> Jupyter Notebook, VS Code, Git, GitHub</li>
  <li><strong>Data Visualization:</strong> Power BI / Tableau (if applicable)</li>
</ul>

<p>
  <img src="https://img.shields.io/badge/Excel-3776AB?style=for-the-badge&logo=Excel&logoColor=white" alt="Excel">
  <img src="https://img.shields.io/badge/Power_BI-150458?style=for-the-badge&logo=Power_BI&logoColor=white" alt="Power BI">
  <img src="https://img.shields.io/badge/DAX-013243?style=for-the-badge&logo=DAX&logoColor=white" alt="DAX">
  <img src="https://img.shields.io/badge/Power_Query-11557C?style=for-the-badge&logo=Power_Query&logoColor=white" alt="Power Query">
  <img src="https://img.shields.io/badge/SQL-4C72B0?style=for-the-badge&logo=sql&logoColor=white" alt="SQL">

</p>

---

## Usage

Instructions for using the project:

1. Open the main notebook (`analysis.ipynb`)  
2. Run each cell sequentially to reproduce the analysis  
3. Visualizations and results will be generated automatically  

Visualition: 

<img width="848" height="491" alt="image" src="https://github.com/user-attachments/assets/db2c4866-28f7-4407-96b8-00131fe6d6fb" />


---

## Analysis & Visualizations 

 - Fraud Rate Analysis:

The analysis showed that fraudulent transactions account for only a very small percentage of the total 284,807 transactions. Although fraud is rare, the financial impact is significant because fraudulent transactions can involve high-value payments. This highlights the importance of accurate fraud detection systems that minimise financial losses while reducing false positives.

- Transaction Amount Analysis:

Transaction amounts were analysed to identify spending patterns and potential fraud indicators. Most transactions were for relatively small amounts, while a small number of very high-value transactions appeared as outliers. Higher transaction amounts were more likely to be associated with suspicious activity and should be monitored more closely.

- Time-Based Transaction Trends:
  
Transaction activity was analysed across different time periods to identify trends in customer spending and fraudulent behaviour. The results showed that fraud was not evenly distributed throughout the day, with certain hours experiencing a higher concentration of fraudulent transactions. These patterns suggest that time-based monitoring could improve fraud detection.

- Risk Segmentation and Anomaly Detection:
  
Transactions were grouped into low-, medium-, and high-risk categories based on transaction amounts and fraud status. Several unusually large transactions were identified as outliers, indicating potential fraudulent behaviour. Detecting these anomalies can help financial institutions prioritise investigations and improve fraud monitoring.

- Key Observations:

The analysis revealed several important patterns:

  - Fraudulent transactions represent a very small proportion of all transactions but pose a significant financial risk.
  - Fraud is concentrated during specific time periods rather than being evenly distributed.
  - Higher transaction amounts are more likely to be associated with suspicious activity.
  - Clear outliers exist within the transaction data and should be investigated further.
  - Customer spending patterns differ from fraudulent behaviour, making historical transaction data valuable for identifying potential fraud.
  - Interactive dashboards created in Power BI and Tableau provide clear insights into fraud trends, spending behaviour and high-risk transactions, helping support informed business decision-making.
---

## Conclusion 

 - Summary of the Analysis:

This project analysed historical credit card transaction data to identify fraud patterns and understand customer spending behaviour. SQL was used to clean and analyse the data, while Power BI and Tableau were used to create interactive dashboards that displayed fraud metrics, transaction trends, risk levels, and unusual spending patterns.

- Main Insights:
  
The analysis found that fraudulent transactions represent only a small percentage of all transactions but have a significant financial impact. Fraud was more common during certain time periods, suggesting time-based risk patterns. Higher-value transactions were more likely to be associated with suspicious activity, and several transaction outliers were identified that may require further investigation. Overall, fraudulent transactions showed different characteristics from normal spending behaviour, making them easier to identify through data analysis.

- Decision-Making Impact:
  
The findings from this project can help financial institutions improve fraud detection and risk management. The dashboards provide clear visibility into transaction activity, enabling analysts to monitor fraud trends, identify high-risk transactions, and make more informed decisions. These insights can support the development of more effective fraud detection strategies and improve the allocation of investigation resources.

- Recommendations and Future Work:
  
Future improvements could include developing machine learning models to increase fraud detection accuracy and reduce false positives. Additional customer information, such as demographic or account data, could be incorporated to provide deeper insights into spending behaviour. Implementing real-time data processing and automated fraud alerts would also enable faster identification and response to suspicious transactions.

---

## Credits

- **Collaborators:** Name – [GitHub Profile](https://github.com/USERNAME)  
- **Dataset Source:** ([Link](https://link-to-dataset.com)](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)  

---

## License

This project is licensed under the [MIT License](https://choosealicense.com/licenses/mit/) – feel free to use and modify it.  

---

<p align="center"><strong>Thanks for visiting! 🚀</strong></p>

