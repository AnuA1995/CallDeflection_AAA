# CallDeflection_AAA

This is my capstone project focused on **call deflection optimization**, sponsored by **Auto Club Group (AAA)**.

## Project Title
**Call Deflection Optimization Using Data Insights**

##  Overview
This project aims to improve call deflection strategies for customer service operations at Auto Club Group (ACG).  
By analyzing service request data and applying machine learning models, the project predicts:
- Service cancellation risks
- Contact center assignments  
...ultimately reducing unnecessary live calls and improving efficiency.

---

##  Problem Statement
ACG handles a high volume of live customer calls, especially during delays or cancellations. These calls are resource-intensive.

**Goals:**
- Identify factors leading to cancellations and live calls.
- Predict which contact center will be assigned.
- Support better operational decisions with dashboards and model-driven insights.

---

## Approach

### Objective 1: Cancellation Risk Classification
- Built multi-class classification models: **Logistic Regression**, **Random Forest**
- Applied **SMOTE** to handle class imbalance
- Categorized service outcomes into:
  - Successful Service  
  - Explicitly Canceled  
  - At-Risk Service  
  - Potential Impact  

### Objective 2: Contact Center Assignment Prediction
- Built models to predict the assigned contact center:
  - ERS ONLINE  
  - AAA MOBILE APP  
  - SMART ACTION  
- Key features:
  - Service request type
  - Request source
  - Provider ID
  - Regional and delay metrics

---

##  Power BI Dashboards
Developed interactive dashboards to visualize:
- Cancellation trends by region, service type, and request source
- Contact center assignment distributions
- Delay metrics and cost insights

---

## Tools & Technologies
- **Python (scikit-learn, pandas, imbalanced-learn)**
- **Power BI**
- **SMOTE (for class balancing)**
- **Random Forest & Logistic Regression**

---

## Results Summary

| Objective | Model              | Accuracy |
|----------|-------------------|----------|
| 1 - Cancellation Risk | Random Forest      | 92.5%    |
| 1 - Cancellation Risk | Logistic Regression | 61.1%    |
| 2 - Contact Center    | Logistic Regression | 82.5%    |
| 2 - Contact Center    | Random Forest       | 80.5%    |

---


