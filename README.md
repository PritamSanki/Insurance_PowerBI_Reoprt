# PRISM INSURANCE DASHBOARD

## Power BI Business Intelligence Project Report

### Prepared By

**Sanki Susanta Pritam**

---

# Abstract

The Prism Insurance Dashboard is a Business Intelligence solution developed using Microsoft Power BI to analyze insurance policy data, claims information, customer demographics, and policy performance. The dashboard provides interactive visualizations, drill-through capabilities, and Row-Level Security (RLS) implementation to support secure and data-driven decision-making.

The project enables stakeholders to monitor premium collections, claim amounts, policy status, customer demographics, and claim settlement trends through a centralized reporting platform.

---

# Table of Contents

1. Introduction
2. Problem Statement
3. Objectives
4. Dataset Description
5. Data Preparation
6. Dashboard Development
7. Dashboard Visualizations
8. Drill Through Functionality
9. Row Level Security (RLS)
10. DAX Measures
11. Results and Findings
12. Challenges Faced
13. Future Enhancements
14. Conclusion

---

# 1. Introduction

The insurance industry generates large volumes of data related to customers, policies, claims, premiums, and coverage amounts. Managing and analyzing this information efficiently is critical for improving operational performance and customer service.

This project was developed using Microsoft Power BI to provide an interactive dashboard that allows users to explore insurance data and gain actionable insights through visual analytics.

---

# 2. Problem Statement

Insurance organizations often face challenges in:

* Monitoring policy performance
* Tracking premium collection trends
* Managing claim settlement processes
* Analyzing customer demographics
* Providing secure access to sensitive information

Traditional reporting methods are often static and time-consuming, making it difficult to identify patterns and make informed decisions.

---

# 3. Objectives

The primary objectives of this project are:

* Build an interactive insurance analytics dashboard.
* Monitor premium, coverage, and claim metrics.
* Analyze policy performance across different policy types.
* Track claim status and settlement trends.
* Implement Drill Through functionality for detailed analysis.
* Implement Row-Level Security for secure data access.
* Provide actionable business insights.

---

# 4. Dataset Description

The project utilizes an insurance dataset containing approximately 10,000 records.

## Dataset Fields

| Field Name      |
| --------------- |
| PolicyNumber    |
| CustomerID      |
| Gender          |
| Age             |
| Age Group       |
| PolicyType      |
| PolicyStartDate |
| PolicyEndDate   |
| PremiumAmount   |
| CoverageAmount  |
| ClaimNumber     |
| ClaimDate       |
| ClaimAmount     |
| ClaimStatus     |
| Active/Inactive |

---

# 5. Data Preparation

The following steps were performed during data preparation:

### Data Cleaning

* Removed inconsistencies.
* Validated missing values.
* Standardized data formats.

### Data Transformation

* Converted date columns.
* Created Age Group categories.
* Derived Active/Inactive policy status.

### Data Modeling

* Established data relationships.
* Created calculated measures using DAX.

---

# 6. Dashboard Development

The dashboard was developed using Microsoft Power BI Desktop.

## Key Features

* KPI Cards
* Slicers
* Bar Charts
* Donut Charts
* Area Charts
* Tables
* Drill Through Pages
* Row Level Security

---

# 7. Dashboard Visualizations

## Main Dashboard

### Insert Screenshot: Main Dashboard

The main dashboard provides an overview of:

* Premium Amount
* Coverage Amount
* Claim Amount
* Policy Status
* Claim Status
* Customer Demographics

### KPI Cards

Three KPI cards display:

* Total Premium Amount
* Total Coverage Amount
* Total Claim Amount

### Premium Amount by Policy Type

Policy categories analyzed:

* Travel
* Health
* Auto
* Life
* Home

The visualization identifies which policy types contribute the highest premium revenue.

### Active vs Inactive Policies

A donut chart displays the distribution of active and inactive insurance policies.

### Number of Claims by Status

Claim statuses include:

* Rejected
* Settled
* Pending

This visual helps monitor claim processing efficiency.

### Claim Amount by Age Group

Customer age groups:

* Young Adult
* Adult
* Elder

The chart identifies claim trends across different age segments.

### Claims Summary Table

Provides policy-wise breakdown of:

* Pending Claims
* Rejected Claims
* Settled Claims
* Total Claims

---

# 8. Drill Through Functionality

### Insert Screenshot: Drill Through Page

A dedicated drill-through page was developed to provide detailed policy-level information.

## Features

* Detailed customer records
* Policy information
* Claim details
* Dynamic filtering based on selected policy type

Benefits:

* Enhanced analysis
* Improved decision making
* Better user experience

---

# 9. Row Level Security (RLS)

### Insert Screenshot: RLS Configuration

Row-Level Security was implemented to restrict data visibility based on user roles.

## Roles Created

### Health Role

Filter Condition:

PolicyType = "Health"

### Travel Role

Filter Condition:

PolicyType = "Travel"

## Benefits

* Secure data access
* Department-specific reporting
* Improved governance
* Controlled information sharing

---

# 10. DAX Measures

## Total Premium Amount

DAX Formula:

SUM(InsuranceData[PremiumAmount])

## Total Coverage Amount

DAX Formula:

SUM(InsuranceData[CoverageAmount])

## Total Claim Amount

DAX Formula:

SUM(InsuranceData[ClaimAmount])

These measures drive the KPI cards displayed on the dashboard.

---

# 11. Results and Findings

The dashboard revealed several important insights.

## Key Findings

### Premium Analysis

Travel policies contribute the highest premium amount compared to other policy categories.

### Policy Status

Active policies significantly outnumber inactive policies, indicating strong customer retention.

### Claims Analysis

Rejected claims account for a considerable portion of total claims, highlighting an area for process review.

### Demographic Insights

Adult customers generate the highest claim amount among all age groups.

### Policy Performance

Travel and Health policies represent the most active insurance segments.

---

# 12. Challenges Faced

During project development, several challenges were encountered:

* Data cleaning and validation
* Dashboard layout optimization
* Implementing drill-through functionality
* Configuring Row-Level Security
* Maintaining dashboard performance with large datasets

These challenges were addressed through proper data modeling and Power BI best practices.

---

# 13. Future Enhancements

Potential improvements include:

* Dynamic Row-Level Security
* Power BI Service Deployment
* Automated Data Refresh
* Predictive Analytics
* Claim Forecasting Models
* Mobile Responsive Dashboard
* Advanced KPI Monitoring

---

# 14. Conclusion

The Prism Insurance Dashboard successfully demonstrates the use of Microsoft Power BI for insurance analytics. The dashboard integrates multiple visualizations, drill-through capabilities, and Row-Level Security to provide meaningful insights into policy performance, customer demographics, and claim management.

The project highlights the effectiveness of Business Intelligence solutions in transforming raw insurance data into actionable information that supports strategic decision-making.

---

# Technologies Used

* Microsoft Power BI Desktop
* DAX (Data Analysis Expressions)
* Excel / CSV Dataset
* Row-Level Security (RLS)

---

# Author

Sanki Susanta Pritam

Power BI Developer | Data Analyst

---

# Project Outcome

✔ Interactive Dashboard Developed

✔ Drill Through Implemented

✔ Row Level Security Configured

✔ Insurance Data Analysis Completed

✔ Business Insights Generated
