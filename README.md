
# Telco Customer Churn Analysis using Power BI


## Project Overview:

An interactive dashboard to represent some analysis of "Telco customer churn" data and the reasons that made customers churn using Microsoft Power BI.


## About Dataset:

- **Telco customer churn:** This sample data module tracks a fictional telco company's customer churn based on a variety of possible factors. The churn column indicates whether or not the customer left within the last month. Other columns include gender, dependents, monthly charges, and many others with information about the types of services each customer has.

- **Source:** IBM.

- **The Telco customer churn data module is composed of 5 tables:**

    - Demographics
    - Location
    - Population
    - Services
    - Status

- **These tables are separated into multiple files:**

    - ```Telco_customer_churn_demographics.xlsx```
    - ```Telco_customer_churn_location.xlsx```
    - ```Telco_customer_churn_population.xlsx```
    - ```Telco_customer_churn_services.xlsx```
    - ```Telco_customer_churn_status.xlsx```

**You can know more about the dataset here:** 

[Telco customer churn (11.1.3+)](https://www.kaggle.com/datasets/ylchang/telco-customer-churn-1113)

## Data Modeling:

A star schema model is built for a faster-analyzing process.
The Telco Customer Churn Star Schema Model contains: 
- **One fact table:**
    - ```Telco_Churn_Fact```
- **Four dimensions tables:**
    - ```Services_Dim```
    - ```Demographics_Dim```
    - ```Location_Dim``` which contains sub-dimension ```Population_Dim```
    - ```Status_Dim```

![DataModel](https://github.com/praakumar/Churn_Analysis_project-PowerBI-/blob/main/ScreenShots/DataModel.png)


## Power BI Dashboard:

The dashboard consists of multiple pages, and each page provides an analysis of a specific topic for better visualization, in addition to an overview page which provides a summary of the dataset and KPIs about the whole dashboard.

A filter that filters the whole dashboard based on the customer status is used for a better understanding of the customers' behavior and analyzes each and its results separately.

The dashboard contains:

- **Home Page** which provides a summary description of the data, KPIs overview, and navigations to dashboard parts.

- **General Insights Page** which provides a general analysis of the customers, their behavior, and the churn reasons.

- **Customer Demographics Page** which analyzes the customers' demographics based on gender and age.

- **Service and Contract Page** which analyze the services that customers subscribed to, services types, contract types, and all related topics.

- **Churn and Revenu Page** which analyzes the revenue from each customer type, customers' states at the end of the year, churned customers, and their reasons to churn.

![1](https://github.com/praakumar/Churn_Analysis_project-PowerBI-/blob/main/ScreenShots/1.png)

![2](https://github.com/praakumar/Churn_Analysis_project-PowerBI-/blob/main/ScreenShots/2.png)

![3](https://github.com/praakumar/Churn_Analysis_project-PowerBI-/blob/main/ScreenShots/3.png)

![4](https://github.com/praakumar/Churn_Analysis_project-PowerBI-/blob/main/ScreenShots/4.png)

![5](https://github.com/praakumar/Churn_Analysis_project-PowerBI-/blob/main/ScreenShots/5.png)





