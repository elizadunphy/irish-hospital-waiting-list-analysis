# Irish Hospital Waiting List Analysis

This project analyses Irish hospital outpatient waiting list data to examine trends in patient waiting times across hospitals.

---

## Overview

The dataset includes the number of patients waiting in different time bands (0–6 months, 6–12 months, 12–18 months, and 18+ months), broken down by hospital and patient type (Adult/Child).

The analysis focuses on:

- Waiting list trends over time  
- Distribution of waiting lists across hospitals  
- Long waiting times (18+ months)  
- Differences between Adult and Child patients  
- Distribution of patients across waiting time bands  

---

## Tools Used

- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- Google Colab  

---

## Key Findings

- The total waiting list shows an overall upward trend over time  
- A small number of hospitals account for a large proportion of total waiting list volumes  
- Long waiting times (18+ months) are concentrated in a small number of hospitals  
- Adult patients make up the majority of those waiting  
- Most patients are in shorter waiting time bands, though long waits remain a concern  

---

## Visualisations

### Waiting List Over Time
![Waiting List Over Time](charts/hospital_waiting_list.png)

### Top 10 Hospitals by Waiting List
![Top Hospitals](charts/top_10_hospitals.png)

### Long Waiting Times (18+ Months)
![Long Waits](charts/long_waits_18_months.png)

### Waiting List by Patient Type
![Adult vs Child](charts/adult_vs_child.png)

### Waiting Time Distribution
![Waiting Time Distribution](charts/waiting_time_distribution.png)

---

## Dataset

- Source: data.gov.ie  
- Dataset: Irish Hospital Waiting List Data  

---

## Notes

- Data required cleaning, including converting formatted numeric fields to numeric values  
- Analysis is based on aggregated data across the available time period  

---

## Author

Elizabeth Dunphy
