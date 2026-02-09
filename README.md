
# Data Scientist

#### Technical Skills 
**Data Science**: Python, SQL, R, Spark, Machine Learning, Azure Databricks, Google Cloud Platform (GCP), CI/CD, Github Actions.

**Analytics**: Microsoft Fabric, Excel, Git, Azure Data Studio, PowerBI, Tableau, Looker, SSMS, MySQL, ETL, Data Modelling.


## Education
- MSc., Data Science | University of Nottingham
- BEng., Engineering | Federal University of Agriculture, Abeokuta, Nigeria.

## Work Experience
**Data Scientist @ Business Full Spectrum (_Jan 2025 - Present_)**
  
  - Predictive Analytics & Churn Modeling: Built and trained a machine-learning churn model across behavioural features, achieving 95.7% prediction accuracy and enabling identification of high-risk cohorts for a targeted 10% churn reduction strategy, using Python (scikit-learn), SQL and Databricks.
  - Experimentation & Statistical Validation: Designed and evaluated A/B tests using hypothesis testing (Mann–Whitney U, Chi-Square), validated statistically significant differences between customer groups prior to deployment, increasing confidence in retention interventions, using Python (SciPy), SQL and Power BI.
  - Business Intelligence & Reporting Accuracy: Built and maintained acquisition, activation, engagement and retention dashboards, improving management reporting accuracy by 30% and accelerating actions on at-risk segments, using Power BI (DAX, Power Query), SQL and Python.
  - RAG Prototype & Support Automation: Designed and evaluated a Retrieval-Augmented Generation customer support bot by reconstructing historical Twitter conversations and grounding LLM responses in agent data, reducing response time from 5 minutes to 5 seconds (98% improvement), using RAG methods, LLM tooling and Twitter data pipelines.
  - Data Governance & Process Automation: Owned the insight/reporting backlog and instituted validation rules and reconciliation checks, achieving a 90% reduction in reporting errors and cutting quarterly manual effort by 80%, using Power Query, Python and SQL.
    
**Project Analyst @ MRS Oil and Gas (_July 2022 – August 2023_)**
  - **Operational Analytics & Downtime Reduction: Delivered performance dashboards and led trend and variance analysis across regions, contributing to a 20% reduction in unplanned downtime, using Power BI, SQL and Azure Data Studio.
  - Data Quality Monitoring & Metrics Definition: Defined success metrics and instituted data quality monitoring, sustaining a monthly reporting cadence of 14 reports during the engagement and improving leadership visibility, using SQL, Power BI and documentation.
  - Cross-Functional Coordination & Data Flow: Coordinated inputs across teams to keep data flows accurate and consistent, ensuring timely delivery of 14 scheduled regional reports and stakeholder updates, using SQL, Azure Data Studio and stakeholder communication templates.
  - Stakeholder Communication & Insight Translation: Conveyed analysis and trend findings to non-technical stakeholders through concise executive updates, delivering 14 monthly executive summaries to support decision-making, using Power BI, Excel and presentation materials.
  - Process Oversight & Reporting Governance: Owned reporting cycles and stakeholder updates, standardising templates and delivery processes which sustained consistent reporting frequency over 14 months, using Power BI, SQL and reporting governance documentation.

**Data Scientist @ Hamoye AI Labs  (_Jan 2022 - April 2022_)**
  - Model Development & Predictive Performance: Built classification and regression models on structured and unstructured datasets, improving interpretation accuracy by 25% across projects, using Python (scikit-learn), R and SQL.
  - Reporting Automation & Compliance: Produced visualisations and automated reports for management and compliance reviews, delivering 4 automated reports during the engagement, using Python, Power BI and R.
  - Data Cleansing & Validation: Enforced cleansing and validation across multiple sources to improve input quality for models, reducing data-related issues in pipelines across the engagement period, using Python (pandas), SQL and validation scripts.
  - Technical Simplification & Stakeholder Support: Simplified technical outputs for business leaders and supported presentation materials and Q&A, contributing to clearer decision-making in 4 management review cycles, using Power BI, Python and slide decks.
  - Model Interpretation & Explainability: Enhanced model interpretability and documentation to support operational handover, producing model explanation artefacts for 4 projects and using SHAP-style techniques, Python and R.

## Projects - Data Science

### Healthcare Tweet Sentiment Classification
[Project Details](https://github.com/helen-oy/Big-Data-Analytics-projects)

Business Goal
“The goal was to automatically classify large volumes of unstructured text into meaningful topics to understand public sentiment at scale.”

What I Did
“I used Spark SQL and Spark ML to process high-volume tweet data and built a multinomial Naive Bayes model, comparing local modelling with a global self-supervised learning approach.”

What It Enabled
“This enables organisations to automatically monitor customer or public feedback, identify key themes, and prioritise response strategies at scale.”

![Hot Healthcare Topics](imgfolder/tweetsPicture.png)


### Bus Arrival Time Prediction
[Project Details](https://github.com/helen-oy/Transport-Data-Analysis-Big-data-project-)

Used Artificial Neural Network combined with k-means clustering for predicting bus arrival times for Department of Transports’ Bus Open Data Service, United- Kingdom. Applied K-means clustering to segment travel times and trained ANN models to classify travel times into delay categories:  zero, low, moderate, and high. This approach led to better identify temporal trends, such as peak delays during weekday mornings and minimal delays in off-peak hours. The results contributes to improving the public transport systems by offering more reliable arrival time predictions.

![Bus Arrival Time Prediction](imgfolder/CDM-predicting-bus-arrival-time-at-21-st-bus-stop-station.png)

### Customer Lifetime Prediction and Churn Analysis
[Project Details](https://github.com/helen-oy/Customer_Lifetime_Value_ML_Model)

Deployed Machine learning model to predict customer lifetime value segment on **Google Cloud**. Used Revenue, Frequency, Monetary Value Analysis with  **Python** to predict lifetime value within a 6-month window for over 600,000 customer records. Predicted churn rate of 3000+ customers, identified high-risk churn segments using **Xgboost** model and  achieved 92% prediction accuracy. Diagnosed and mitigated overfitting caused by class imbalance in revenue distribution using model simplification.

![CustomerLifeTimeValueSegments](imgfolder/clvprediction.png) [Link to deployed model]()


## Projects - Data Analytics

### Helpdesk Ticket Status Report
[Project Details](https://lookerstudio.google.com/reporting/2b302444-1d67-4be8-a9e2-ae1bdabfb073)

Designed an interactive dashboard that shows performance of the helpdesk support team in handing incidence and requests tickets using **Google Looker Studio**. Identified areas for improvements by departments, needs for new hires and recommended introduction of self service options to reduce workload and improve ticket processing speed.

![Helpdesk Ticket Report](imgfolder/Helpdesk_ticket_Looker_Report.jpg)


### Customer Churn Dashboard
[Project Details](https://public.tableau.com/app/profile/helen.soremekun/viz/Tableau_Telco_customer_churn/Churn_Rate_TrendsPatterns?publish=yes)

An ideal churn rate is 5-7% per year, depending on if you measure customers or revenue. The churn rate in this project was calculated overall, for a period of 72 months (3 years) based on the data set fields: customer segments, service types, monthly charges, payment methods, tech support, streaming services and contract type using **SQL queries** and **Tableau** for visualization. In the period of three years, churn rate was 26.54%, with  a 1.8% per year churn rate increase above an ideal 7% upper band churn rate.

![Churn rate by Demographics](imgfolder/Churn_Rate_Trends&Patterns.png)


### Contact Centre KPI metrics Reporting
[Project Details](https://docs.google.com/spreadsheets/d/1C1dyJY6WyH9LOfsDYhYvVm60t2eqBTHzQCTRJGB4S2M/edit?gid=34913950#gid=34913950)

Created a dashboard to report weekly, monthly, and yearly KPI metrics such as average answer rate, average abandon rate, and call trends for a Call Centre to support workflow and workforce and management using **Google sheets**. Identified that call center 3.4% Average Abandon Rate from 669, 671 Inbound calls and peak calls occuring in October.

![Contact Centre KPI metrics report](imgfolder/CallCenter_KPI'sDashboard.jpg)


### Automobile Sales Analysis Report
[Project Details](https://app.powerbi.com/view?r=eyJrIjoiMjc4YzFmOTMtMTY2MC00YTYyLTlhNTMtNWFmOGEwMGJjMmQwIiwidCI6ImNlZWI4M2FiLTMzOTItNGViYy05ZWYxLTNmYTc2YmYzYzI0MiJ9
 )
 
Designed an Interactive Dashboard using **Power BI**, **DAX queries** and **SQL** **scripts** to obtain monthly and yearly sales key performance indicators such as total revenue, total sales, top-performing products, top-performing products subcategories, production costs, profit after tax and products performance by country between 2016 to 2019. In 2018, the highest sales and profits were recorded and North Americ yield the most profit from the 7 continents.

![Automobile Sales Analysis Dashboard](imgfolder/AutomobileSalesAnalysisReport.jpg)


### Superstore Sales Insights Dashboard
[Project Details](https://public.tableau.com/app/profile/helen.soremekun/viz/tableauproject_sales_insight/Dashboard1?publish=yes)

Created an Interactive dashboard and interpreted 150,000+  transactional data into a user-friendly interface, providing the managing director with key insights using **Tableau desktop** connected to **MySQL** server .Presented key performance indicators (KPIs) such as total revenue, total sales, top-performing products, customer demographics, and sales trends with simple and clear visualizations. Delhi NCR region generated the most revenue and the customer with the most revenue "Electricalsara Store", generated over 40% of the total revenue in 2018. 
![Superstore Sales Insights Dashboard](imgfolder/StationerySuperstoreDashboard.png)

### Count-based Analysis of Pet breeds 
Using **Excel** functions like pivot tables, slicers, vlookups, xlookups, pivot charts, created a summary of the count-based analysis of cat and dog breeds based on their different subgroups such as weight, physical characteristics, temperament, price, and average sales. Identified that Quantity sold is independent of the popularity of dog and cat breeds. High/less-popular breeds have almost the same quantity sold. In the selection of top breeds to stock up are Turkish van, American shorthair, LaPerm and Persian cats promises to yield the most revenue, based on average price and quantity sold.
 








