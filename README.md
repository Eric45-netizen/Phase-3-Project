# Phase-3-Project
Customer Churn Analysis 
# **SyriaTel Customer Churn Prediction**

## **Overview**
Customer churn is a significant challenge in the telecommunications industry. This project aims to build a predictive model that identifies customers who are likely to churn, enabling **SyriaTel** to take proactive steps to retain them. By analyzing customer behavior and service usage patterns, we can provide actionable insights to **reduce churn rates and improve customer satisfaction**.

## **Business and Data Understanding**
### **Stakeholder Audience:**
- **SyriaTel Business Team** – To develop strategies for reducing customer churn.
- **Customer Service Department** – To identify at-risk customers and improve engagement.
- **Marketing & Retention Teams** – To design targeted campaigns for customer retention.

### **Dataset Description:**
- **Source:** SyriaTel Customer Churn Dataset
- **Size:** 3,333 customer records
- **Target Variable:** `churn` (Binary: `True` = churned, `False` = retained)
- **Key Features:**
  - **Account length** – How long the customer has been with the company
  - **Total Day Minutes & Charges** – Usage and associated costs during the day
  - **Customer Service Calls** – Number of times the customer contacted support
  - **International Plan** – Whether the customer has an international calling plan
  - **Total Intl Calls & Charges** – International call usage

## **Modeling**
We applied multiple classification models and evaluated their performance based on accuracy, precision, recall, and F1-score.

### **Models Implemented:**
- **Logistic Regression**
- **Decision Tree**
- **Random Forest**
- **K-Nearest Neighbors (KNN)**
- **Naive Bayes**

## **Evaluation**
### **Model Performance Comparison:**
| Model                 | Accuracy |
|----------------------|----------|
| **Random Forest**       | **94.00%**   |
| Decision Tree        | 90.25%   |
| K-Nearest Neighbors (KNN) | 88.61%   |
| Logistic Regression  | 85.76%   |
| Naive Bayes         | 85.31%   |

- **Random Forest performed the best (94.00% accuracy)** and was selected as the optimal model for churn prediction.
- **Customer Service Calls and High Charges were key indicators of churn.**

## **Conclusion**
### **Key Findings:**
- **Random Forest was the most effective model for predicting churn.**
- **Customer service call frequency and high usage costs were key indicators of churn.**
- **Customers with an International Plan were more likely to leave.**

### **Recommendations:**
✅ **Target High-Risk Customers:** Use predictive analytics to identify at-risk customers early and offer personalized retention offers.
✅ **Improve Customer Service:** A high number of service calls correlates with churn. Streamlining support processes can enhance customer satisfaction.
✅ **Optimize Pricing for High-Usage Customers:** Many customers with high usage and charges are likely to leave. Offering discounts or tailored plans may improve retention.
✅ **Reassess International Plan Pricing:** Customers with international plans are more likely to churn. A competitive pricing strategy can help reduce attrition.
✅ **Introduce Loyalty Programs & Bundled Services:** Encouraging long-term engagement through discounts and bundled services can enhance customer retention.

---
By following these insights, **SyriaTel can take proactive steps to reduce churn, improve customer satisfaction, and optimize their business strategy.** 🚀

