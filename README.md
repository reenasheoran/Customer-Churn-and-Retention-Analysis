# Customer Churn and Retention Analysis

**Customer attrition**, also known as customer churn, is the loss of customers or subscription to goods/services by a business for a given period of time.<br>
**Customer retention** is the collection of activities a business uses to increase the number of repeat customers and to increase the profitability of each existing customer.
## Important Terminology
* Customer attrition rate is the number of customers lost at the end of the period against the number of customers the business had at the start of the period.<br>
* Gross attrition is the loss of revenue from churned customers.<br>
* Net attrition is the loss of revenue from churned customers including the benefits from expansion (new customers, upgrades...)<br>
* Monthly Recurring Revenue (MRR) is the recurring revenue expected on monthly basis for the subscribed goods/services.<br>
* Gross Revenue Retention (GRR) rate measures the change in the MRR over the period, excluding benefits from expansion.<br>
* Net Revenue Retention (NRR) rate measures the change in the MRR over the period, including benefits from expansion.<br>
## Introduction
* Churn is a critical metric for subscription and SaaS companies as it tells us how the departing customers affects the company's monthly revenue and growth, consequently investors' confidence in the company as well.<br>
* The GRR is somewhat like a happiness indicator for the existing customers. Having high GRR shows that the company has high retention rates. Customers are happy with the services/products that they are provided with. Investors would be assured by this stability.
If a company has high GRR and even higher NRR, it shows that on top of retaining existing customers, the company has grown its customer base further.<br>
* High NRR coupled with low GRR implies that although the company has acquired many new customers, it has low retention rates.
So even if there is still revenue left over after the churn, there is high potential the new customers might churn too. The growth of the company becomes less predictable.
## Problem Statement
Telecommunication industry is highly sensitive to customer churns as technology advances and users' behaviour changed.<br>
* with Mobile Number Portability (MNP), customers can easily switch to another provider while preserving their number.<br>
* OTT players such as Netflix, Amazon Prime Video, Disney+ are bypassing the traditional operators network such as cable, broadcast and satelite television.<br>
* OTT applications such as WhatsApp, Google Hangout, Skype are cannibalizing the paid voice and messaging services.<br>
* customers are less enticed to be contract bounded for handsets as new models get released so frequently.<br>
## My analysis approach
In this notebook, I will look at the customer churn in the telecommunication sector.<br>
Using the Telco Customer Churn data from Kaggle, I explore the accuracy of 4 machine learning algorithms against the actual churn in the past month:<br>
* Logistic Regression Prediction<br>
* Logistic Regression (SMOTE) Prediction<br>
* Naive Bayes Prediction<br>
* SVM Classifier Linear Prediction<br>
I will compare the model's prediction against the same set of data for accuracy comparison.<br>

Assuming that the company wish to retain 90% NRR for this particular telco, I will explore the impact of each model on:<br>

* Predicted revenue loss<br>
* Number of customers to retain<br>
* Expense spent to retain or replace customer<br>
Finally, I will use what-if simulation to see how the above will change when I change:<br>

* the target NRR<br>
* the budget spent on customer retention or replacement
