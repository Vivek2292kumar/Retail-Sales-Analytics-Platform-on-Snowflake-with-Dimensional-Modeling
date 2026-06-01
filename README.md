# Enterprise Retail Sales Analytics Platform | Snowflake Data Warehouse

## Overview

This project demonstrates the design and implementation of an enterprise-scale Retail Sales Analytics Platform built on Snowflake using dimensional modeling principles and Python-based data generation pipelines.

The solution simulates a real-world retail ecosystem by generating customer, product, store, loyalty, and sales transaction data and loading it into a scalable analytical warehouse architecture. The objective was to create a reporting-ready data platform capable of supporting business intelligence, operational reporting, and executive decision-making.

---

## Business Problem

Retail organizations generate large volumes of transactional data across multiple stores, products, and customer channels. Without a structured analytical platform, deriving actionable insights becomes difficult due to fragmented datasets and inconsistent reporting.

The goal of this project was to design a centralized analytics solution capable of:

* Consolidating retail transaction data.
* Supporting historical and trend-based analysis.
* Enabling customer, product, and store performance reporting.
* Providing a scalable foundation for business intelligence initiatives.
* Following enterprise data warehousing best practices.

---

## Solution Architecture

Source Data Generation

↓

Python Data Generation Layer

↓

Landing Layer

↓

Snowflake Staging Layer

↓

Dimension Processing

↓

Fact Table Processing

↓

Enterprise Data Warehouse

↓

Business Analytics & Reporting

---

## Technology Stack

### Cloud Data Warehouse

* Snowflake

### Programming

* Python
* Pandas
* NumPy

### Data Warehousing

* Dimensional Modeling
* Star Schema Design
* Fact & Dimension Modeling

### Data Engineering

* ETL Pipeline Development
* Batch Processing
* Incremental Data Loading

### Analytics

* Sales Analytics
* Customer Analytics
* Product Analytics
* Store Performance Analysis

---

## Data Warehouse Design

### Dimension Tables

#### DimCustomer

Stores customer demographic information and loyalty program attributes to support customer segmentation and behavioral analysis.

#### DimProduct

Contains product hierarchy information including category, sub-category, and brand details.

#### DimStore

Stores location, regional, and operational information for store-level reporting and benchmarking.

#### DimDate

Supports time intelligence, trend analysis, and period-over-period reporting.

#### DimLoyaltyProgram

Captures customer loyalty classifications and reward program structures.

---

### Fact Table

#### FactOrders

Central transactional fact table containing:

* Order Amount
* Sales Revenue
* Discount Amount
* Shipping Cost
* Quantity Ordered
* Transaction Metrics

The fact table is connected to all business dimensions through surrogate keys to enable scalable analytical reporting.

---

## Key Engineering Components

### Customer Data Generation Framework

Automated generation of customer master data including demographics, contact information, geographic distribution, and loyalty memberships.

### Product Data Generation Framework

Creation of realistic product catalogs with category and brand hierarchies.

### Store Data Generation Framework

Simulation of a distributed retail network consisting of multiple store locations.

### Historical Sales Generator

Generation of historical sales transactions to support trend and performance analysis.

### Incremental Sales Processing

Simulation of daily store-level transaction feeds to replicate real-world retail operations.

---

## Business Use Cases

### Revenue Performance Analysis

* Revenue trend monitoring
* Sales growth analysis
* Store-level sales tracking

### Customer Analytics

* Loyalty program effectiveness
* Customer segmentation
* Geographic customer analysis

### Product Analytics

* Product performance evaluation
* Category contribution analysis
* Brand-level reporting

### Store Analytics

* Regional performance comparison
* Store benchmarking
* Operational effectiveness analysis

---

## Data Modeling Approach

The solution follows Kimball dimensional modeling principles and implements a Star Schema architecture consisting of:

* Conformed Dimensions
* Fact Tables
* Surrogate Keys
* Historical Reporting Structures

This design enables high-performance analytical querying while maintaining simplicity and scalability.

---

## Project Highlights

✔ Snowflake Data Warehouse Implementation

✔ Enterprise Retail Data Model Design

✔ Star Schema Architecture

✔ Fact & Dimension Modeling

✔ Historical and Incremental Data Processing

✔ Automated Data Generation Framework

✔ Scalable Reporting Foundation

✔ Business Intelligence Ready Architecture

---

## Skills Demonstrated

Snowflake

SQL

Python

Pandas

NumPy

Data Warehousing

Dimensional Modeling

Star Schema Design

Fact & Dimension Modeling

ETL Development

Retail Analytics

Business Intelligence

Analytics Engineering

Data Architecture

---

## Future Enhancements

* Snowpipe Automation
* Stream & Task Based Processing
* Change Data Capture (CDC)
* Power BI Executive Dashboard
* Data Quality Framework
* SCD Type 2 Implementation
* Role-Based Access Control
* Automated Monitoring & Alerting

---

## Repository Structure

Enterprise-Retail-Sales-Analytics-Snowflake/

├── architecture/

├── data_generation/

├── snowflake/

├── documentation/

├── sample_data/

├── images/

└── README.md

---

## Author

Vivek Kumar

Data Analyst | Snowflake | SQL | Python | Power BI | Azure
