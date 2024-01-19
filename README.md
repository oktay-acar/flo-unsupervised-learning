# Customer Segmentation with Unsupervised Learning using [FLO](https://www.flo.com.tr/)'s Dataset

**Business Problem**

**FLO** wants to divide its customers into segments and determine marketing strategies according to these segments. To this end, customers' behaviors will be defined and groups will be created based on clusters in these behaviors.

**Dataset Story**

The dataset consists of the information obtained from the past shopping behaviors of customers who made their last purchases from **FLO** as OmniChannel *(both online and offline shopper)* in 2020-2021.

**Variables**
- **master_id:** Customer ID
- **order_channel:** Shopping platform *(Android, ios, Desktop, Mobile, Offline)*
- **last_order_channel:** The channel where the most recent purchase was made
- **first_order_date:** Customer's first order date
- **last_order_date:** Customer's last order date
- **last_order_date_online:** Customer's last offline order date
- **last_order_date_offline:** Customer's last online order date
- **order_num_total_ever_online:** The total number of orders made by the customer online
- **order_num_total_ever_offline:** The total number of orders made by the customer offline
- **customer_value_total_ever_offline:** The total price paid by the customer for offline orders
- **customer_value_total_ever_online:** The total price paid by the customer for online orders
- **interested_in_categories_12:** List of categories the customer has shopped in the last 12 months

---

## Requirements
~~~python
matplotlib==3.7.1
numpy==1.24.3
pandas==1.5.1
scipy==1.11.4
seaborn==0.12.1
sklearn==1.3.1
yellowbrick==1.5
~~~

---

## Author
[Oktay Acar](https://github.com/oktay-acar)