# Technical Support Operations Analytics (Excel | Python | SQL | Power BI)

# Business Objective
Analyze 2,330 technical support tickets to assess SLA performance, identify factors contributing to SLA breaches, and provide operational recommendations to improve service delivery.
Built across the full analytics workflow: **Excel → Python → SQL → Power BI.**

# What I found
The centre answers fast but closes slow.** 87% of tickets meet the first-response
target, but only **81% are resolved on time** — about **1 in 5 tickets breaches** the
resolution SLA.

The misses aren't random.** They cluster in **Pricing & licensing tickets**,
chat-channel tickets**, and **medium-priority work** — while urgent (high-priority)
tickets are actually handled best.
**Demand peaks mid-week and mid-afternoon** (busiest on Wednesdays, around 3 PM) —
useful for staffing.

# What I recommended
Protect the **medium-priority queue**, which slips the most.
Review how **chat tickets** are handled — they breach far more than email.
Add resolution capacity for **Pricing & licensing**, the biggest source of misses.


# Tools used
Tools & Technologies
Excel (Data Collection & Preparation)
Python (Data Cleaning & Validation)
PostgreSQL (Data Analysis)
Power BI (Dashboard Development & KPI Reporting)

# Data Preparation
The dataset was cleaned and validated using Python.

Tasks included:
Handling missing values
Standardizing ticket categories
Validating SLA calculations
Formatting date and time fields
Preparing the dataset for SQL analysis and Power BI reporting


# What's in this repo

| File | What it is |
|------|------------|
| `Raw.Technical Support Dataset.xlsx` | The original raw data |
| `Pycleanedtickets-checkpoint.ipynb` | Python cleaning notebook |
| `SQLqueries` | SQL analysis queries |
| `Technical Support Dashboard KPI Report.pbix` | Power BI dashboard |

**Dashboard Preview**

<img width="1307" height="730" alt="image" src="https://github.com/user-attachments/assets/446b75df-2a3e-4cc5-9d10-c75529fe6e7c" />


<img width="1305" height="731" alt="image" src="https://github.com/user-attachments/assets/2501d093-be19-418a-b075-d0ca65c136aa" />

An interactive Power BI dashboard was developed to monitor SLA performance and operational efficiency across the support center.

# Dashboard Features

SLA Resolution Tracking
SLA First Response Tracking
Ticket Volume Monitoring
Priority-Based Performance Analysis
Topic-Level SLA Violation Analysis
Agent Group Performance Comparison
Monthly Trend Analysis
Interactive Slicers and Filters

# Data Model

The dashboard was built using multiple connected tables and a relational data model.
Relationships were created between ticket records and supporting lookup data to enable dynamic filtering and KPI calculations across the report.

# DAX Measures
Custom DAX measures were created to calculate:
SLA Resolution %
SLA First Response %
SLA Compliance %
Total Tickets
Finished Tickets
SLA Violations
Average Resolution Time


# Key Business Impact
This analysis helped identify the primary drivers of SLA breaches and highlighted operational opportunities to improve service performance, 
resource allocation, and ticket resolution efficiency.


# Author
Rahul B
rahulforreal4747@gmail.com
