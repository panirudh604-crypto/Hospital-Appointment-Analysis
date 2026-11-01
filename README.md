
# Hospital Appointment Analysis Dashboard 

## Project Overview

An interactive Power BI dashboard built to analyze hospital appointment operations, doctor performance, patient experience and financial performance. It brings key healthcare metrics together to help identify appointment trends, workload patterns, patient revisit behaviour, and revenue collection gaps.

## Key Metrics

- **Total Appointments:** 58,183
- **Completion Rate:** 83.63%
- **Average Waiting Time:** 27 minutes
- **Patient Satisfaction Score:** 3.59 / 5
- **Total Billed:** $177M
- **Total Collection:** $165M
- **Outstanding Amount:** $12M

## Key Insights

- **Appointment Outcomes:** 48,656 appointments were completed, while 9,527 were cancelled or marked as no-shows, representing 16.37% of total appointments.
- **Department Demand:** Medical recorded the highest appointment volume with approximately 27K appointments.
- **Doctor Performance:** Waiting times varied across specialties, with Urology recording the highest average waiting time at 43 minutes followed by Orthopedics at 39 minutes.
- **Patient Revisits:** Chronic conditions recorded a higher 30-day revisit rate (14.24%) than non-chronic conditions (9.42%).
- **Revenue Collection:** $165M was collected against $177M billed, leaving $12M in outstanding payments.

## Dashboard Features

- Appointment status and monthly trend analysis.
- Department wise appointment distribution.
- Doctor workload and specialty level comparisons.
- Waiting time and patient satisfaction analysis.
- Revisit rate analysis by condition type.
- Billed, collected and outstanding amount tracking.
- Interactive filters for exploring different aspects of hospital performance.

## Data Model

The project uses a star schema with one central Appointments fact table and five dimension tables: Date, Payer, Branch, Doctor and Patient. The model organizes appointment records and related information for analysis across multiple dimensions.

## Tools Used

Power BI | Power Query | DAX | Data Cleaning | Data Modeling | Data Visualization

