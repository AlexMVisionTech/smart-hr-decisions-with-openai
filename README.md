## **Leveraging Generative AI and Predictive Analytics for Real-Time Human Resource Decision-Making**

### Overview

This project explores the integration of **Generative Artificial Intelligence (AI)** and **Predictive Analytics** to enhance real-time decision-making within Human Resource (HR) Management. The study demonstrates how structured data (e.g., payroll records, staff histories) and unstructured data (e.g., CVs, job descriptions) can be transformed into actionable insights using machine learning (ML) and natural language processing (NLP) techniques. The goal is to support more accurate, efficient, and equitable HR decisions.

---
### Problem Statement
Human Resource (HR) departments in many organisations, particularly in the public sector, often struggle with making timely, data-driven decisions related to recruitment, employee retention, payroll classification, and performance evaluation. Traditional HR processes are frequently manual, reactive, and subjective—leading to inefficiencies, delayed hiring, poor talent alignment, and increased attrition risk.

Despite the growing availability of HR data, most institutions have yet to fully leverage advanced analytics and artificial intelligence to support strategic human capital management. There is a pressing need to integrate predictive models and generative AI tools into HR workflows to enhance decision-making accuracy, speed, and fairness.

This project addresses this gap by developing and evaluating machine learning and generative AI solutions that can:

Predict critical HR outcomes such as attrition and payroll grouping,

Match CVs to job roles based on semantic relevance,

Support transparent, ethical, and scalable HR practices.

---

### Objectives

- Develop and evaluate predictive models for key HR functions, including attrition forecasting, performance classification, and payroll segmentation.
- Deploy a generative AI approach (Sentence-BERT) to automate and optimise CV-to-job-role semantic matching.
- Compare the performance of traditional and ensemble machine learning models in terms of accuracy, efficiency, and HR interpretability.
- Provide recommendations for the ethical and scalable integration of AI in HR operations.

---

### Data Sources

The project utilised anonymised HR datasets containing both structured and unstructured data, including:

- Employee demographic and employment histories  
- Performance appraisal outcomes and key performance indicators (KPIs)  
- Training participation and capacity-building logs  
- Payroll records and compensation bands  
- Recruitment documents, CVs, and job descriptions  

---

### Machine Learning Models Applied

| Model                | HR Application                                  | Strengths                                                 |
|---------------------|--------------------------------------------------|-----------------------------------------------------------|
| **Logistic Regression** | Attrition prediction                           | High interpretability, ideal for initial benchmarking      |
| **Random Forest**       | Performance classification and retention prediction | Captures non-linear patterns, offers feature importance    |
| **XGBoost**             | Payroll band classification                   | Superior accuracy, handles complex interactions, scalable |
| **Sentence-BERT**       | CV–job semantic matching                      | Captures deep context in unstructured text, reduces bias   |

---

### Evaluation Metrics

To assess model performance, the following standard classification metrics were applied, with additional consideration for interpretability in HR contexts:

- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**
- **ROC-AUC**
- **HR stakeholder interpretability**

---

### Model Performance Summary

| Model                 | Precision | Recall | F1-Score | Accuracy | ROC-AUC |
|----------------------|-----------|--------|----------|----------|---------|
| **Random Forest**    | 0.91      | 1.00   | 0.95     | 0.92     | 0.91    |
| **Logistic Regression** | 0.87   | 0.98   | 0.92     | 0.86     | 0.83    |
| **XGBoost**          | 0.96      | 0.99   | 0.97     | 0.96     | 0.93    |

**Interpretation**:
- **XGBoost** achieved the highest accuracy and overall balance, making it suitable for high-impact HR classification tasks such as payroll segmentation.
- **Random Forest** excelled in recall, reducing the risk of overlooking critical cases such as potential resignations.
- **Logistic Regression** performed well as a baseline model, offering strong results with high transparency—essential for HR communication and justification.

---

### Key Findings

- Predictive modelling enables proactive workforce management and reduces reliance on reactive or subjective decision-making.
- XGBoost outperformed other models in terms of predictive accuracy, particularly in complex tasks.
- Random Forest provided valuable interpretability for HR policy insight.
- Sentence-BERT significantly improved recruitment efficiency and fairness by semantically matching CVs to job descriptions.

---

