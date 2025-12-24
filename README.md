# rfm-customer-segmentation

## Project Result Showcase

<img width="3840" height="1080" alt="image (4)" src="https://github.com/user-attachments/assets/f326f294-5424-4c18-bef5-b16ba264f5fc" />


rfm customer segmentation dashboard ulr : https://lookerstudio.google.com/reporting/76f4ce60-48ed-4ae9-a5dc-5c6cd0c00df8


----------------------------------------------------------------------

## Project Overview
----------------------------------------------------------------------
This project focuses on customer segmentation using RFM (Recency, Frequency, Monetary) analysis based on transactional data.
The goal is to classify customers into meaningful behavioral segments in order to better understand purchasing patterns and customer value.

Each customer is evaluated using:

Recency (R): how recently the customer made their last transaction (measured as the number of days since the most recent purchase)

Frequency (F): how often the customer makes purchases (measured by total transaction count)

Monetary (M): how much the customer spends (measured by total sales amount)

These three metrics are converted into discrete scores and combined using rule-based logic to assign each customer into a predefined segment.

----------------------------------------------------------------------

## Segmentation Logic

Customer segments are determined using explicit rules based on R, F, and M scores, rather than machine learning or clustering models (clarification: this ensures interpretability and business transparency).

Example of segmentation rules:

Champions: customers with the highest recency, frequency, and monetary scores

Loyal Customers: frequent buyers with strong engagement

Potential Loyalists: recent customers showing early signs of loyalty

At Risk: previously active customers with declining recency

Hibernating: inactive customers with low engagement

Others / About to Sleep: customers that do not strongly fit into other segments

This approach allows stakeholders to clearly understand why a customer belongs to a specific segment (clarification: each label is directly traceable to RFM score conditions).

----------------------------------------------------------------------
