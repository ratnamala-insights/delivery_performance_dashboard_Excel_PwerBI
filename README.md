# HexaKart Delivery Performance Analysis - Dashboard on PowerBI

<img width="1312" height="739" alt="image" src="https://github.com/user-attachments/assets/e564baf5-cfb2-4424-9561-02823d69c549" />


**Project Overview**

This project presents a Delivery Performance Dashboard built using Power BI to analyze logistics and delivery operations for an e-commerce platform called Hexakart(Dummy company).

The dashboard focuses on key operational metrics such as delivery success rate, return-to-origin (RTO) rate, delivery delays, delivery partner performance, and non-delivery reasons. It provides an interactive way to monitor delivery efficiency and identify operational challenges affecting logistics performance.

The purpose of the dashboard is to transform delivery data into actionable insights that support operational decision-making and performance monitoring.

**Objective**

The main objectives of this project are:

Analyze delivery success and failure rates

Evaluate performance across different delivery partners

Identify key causes of non-delivery (NDR)

Understand the impact of seasonal demand on delivery performance

Analyze delivery attempt success patterns

Track regional logistics performance

**Tools & Technologies Used**

Power BI – Data visualization and dashboard design

Microsoft Excel – Data source and preprocessing, cleaning

DAX (Data Analysis Expressions) – KPI calculations and measures



**Dataset**

The dataset contains logistics and operational delivery information including:

Delivery Partner

Delivery Status (Delivered / RTO)

Delivery Attempts

Region

Season (Festive / Non-Festive)

Delivery Time (TAT)

State-level delay data

Non-Delivery Reasons (NDR)

This data is used to analyze delivery efficiency and operational bottlenecks.

**Dashboard Features**
Key Performance Indicators (KPIs)


<img width="530" height="109" alt="image" src="https://github.com/user-attachments/assets/96a7fddf-07a8-4ba2-9b45-15a50e2947c6" />


The dashboard highlights important operational metrics:

Success Rate: 76.78%

NDR (RTO) Rate: 23.22%

Average TAT: 3.95 days

Delay Rate: 66%

These KPIs provide a quick overview of the overall performance of the delivery network.

**Delivery Partner Performance**

<img width="521" height="294" alt="image" src="https://github.com/user-attachments/assets/fa40e205-805f-4ad1-a19e-ad8b6bcf072b" />


A stacked bar chart compares delivery success vs RTO percentage across major delivery partners, including:

DTDC

Ecom Express

India Post

XpressBees

BlueDart

Delhivery

Flipkart

**Insights**

Most partners maintain delivery success rates above 75%.

Delhivery shows one of the highest delivery success percentages among partners.

Variations in RTO rates highlight operational efficiency differences between delivery partners.

**Delivery Performance by Season**

<img width="228" height="402" alt="image" src="https://github.com/user-attachments/assets/2631201c-3412-417e-83fb-6fc5510f1e54" />


This visualization compares delivery outcomes during:

Festive Season

Non-Festive Season

**Insights**

Non-festive periods account for the majority of successful deliveries (64.76%).

Festive seasons show higher operational pressure, leading to relatively higher RTO proportions.

**Top 5 Delayed Delivery States**


<img width="354" height="207" alt="image" src="https://github.com/user-attachments/assets/93bd1d52-3ed0-47df-9bbb-8c3deddc3184" />


A line chart highlights states with the highest delayed deliveries, including:

Delhi

Telangana

Madhya Pradesh

West Bengal

Karnataka

These states represent regions where delivery performance may require operational improvements.

**Delivery Attempt vs Outcome**

<img width="358" height="201" alt="image" src="https://github.com/user-attachments/assets/12199fcc-de3b-4ee7-b8e5-8081190054aa" />

This chart analyzes how delivery success changes across multiple delivery attempts.

**Observations**

First and second delivery attempts show higher success rates.

As attempts increase, RTO probability increases significantly.

Multiple attempts often indicate customer unavailability or address-related issues.

**Non-Delivery Reasons (NDR Analysis)**

<img width="756" height="238" alt="image" src="https://github.com/user-attachments/assets/2ac2230d-a208-467e-8182-9179df1f4c44" />


This section highlights the most common reasons for failed deliveries, such as:

Insufficient contact details

Customer unavailable

Incorrect address

Damaged during transit

Restricted delivery area

Customer refused delivery

**Key Insight**

A large share of delivery failures is caused by customer information issues, suggesting that better address validation and communication could reduce RTO rates.

**Regional Delivery Performance**


<img width="351" height="239" alt="image" src="https://github.com/user-attachments/assets/ea292dc2-3e0d-487e-b556-0b107cf4740b" />


A comparative table analyzes delivery partner performance across regions:

East

North

South

West

This helps identify regional strengths and weaknesses for each logistics partner.

**Key Insights**

The overall delivery success rate is approximately 77%, indicating relatively stable logistics performance.

Customer availability and incorrect addresses are major drivers of delivery failures.

Certain states show higher delay rates, indicating regional logistical challenges.

Delivery partner performance varies slightly, highlighting opportunities for optimization.

First-attempt delivery success is critical to reducing operational costs and RTO rates.

**Learning & Impact**

This project demonstrates practical experience in:

Logistics and operations analytics

KPI monitoring for delivery networks

Root cause analysis using data visualization

Building interactive Power BI dashboards for operational decision-making


