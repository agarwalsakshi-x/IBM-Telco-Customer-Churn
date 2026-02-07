# Customer Churn Prediction in Telecom  

##  Project Overview
Customer churn is a major challenge for subscription-based businesses because retaining existing customers is significantly more cost-effective than acquiring new ones.

This project develops predictive machine learning models to:

- Estimate each customer’s **probability of churn**
- Identify **key behavioral and service drivers**
- Translate model outputs into **actionable business retention strategies**
  
## Business Questions
This analysis answers three strategic business questions:

1. **Revenue Impact** – What is the dollar value of reducing churn among high-revenue customers?  
2. **Customer Lifetime Value** – Which segments contribute most to long-term revenue?  
3. **Service Bundle Influence** – Which service combinations most strongly affect churn risk?  

## Dataset
- **Source:** IBM Telco Customer Churn  
- **Customers:** ~7,000 telecom users  
- **Features:** 21 variables including  
  - Demographics  
  - Service subscriptions  
  - Contract & billing details  
  - Churn status (target variable)

##  Modeling Approach
Three classification models were built and compared:

| Model | Purpose |
|-------|---------|
| **Logistic Regression** | Interpretability & business insight |
| **Decision Tree** | Clear operational decision rules |
| **Neural Network** | Non-linear predictive performance |

### Evaluation Metrics
- ROC-AUC  
- Precision, Recall, F1-Score  
- Business-aligned **cutoff optimization**

The logistic regression model achieved **~0.85 validation AUC**, showing strong predictive performance and generalization.

Optimizing the probability cutoff significantly improved **recall (~56% → ~79%)**, enabling better detection of at-risk customers for retention campaigns.

## Key Insights
- **Month-to-month contracts** and **fiber-optic customers with short tenure** show the **highest churn risk**.  
- **Long-tenure customers with bundled support services** demonstrate **higher loyalty and lifetime value**.  
- **Online security and technical support** act as **protective factors** that reduce churn probability.  

## Business Recommendations
- Convert high-risk **month-to-month customers** to longer-term contracts.  
- Improve **onboarding and early support** for new fiber-optic users.  
- Promote **bundled security and technical support services**.  
- Focus retention efforts during the **early customer lifecycle** where churn risk is highest.  

## Why Excel-Based Machine Learning?
This project was intentionally implemented in **Excel** to demonstrate:

- Real-world analytics in **business-first environments**
- **Transparent and interpretable** modeling for non-technical stakeholders
- **Decision-ready outputs** usable by marketing, operations, and retention teams  

This complements Python-based ML by showcasing **end-to-end business analytics capability**.

## Tools & Skills Demonstrated
- Excel Data Science add-ins  
- Logistic Regression, Decision Tree, Neural Network  
- Feature selection & cutoff optimization  
- Model evaluation (AUC, Precision, Recall, F1)  
- Translating ML insights into **business strategy**
