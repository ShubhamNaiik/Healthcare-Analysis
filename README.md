# Healthcare Analysis Report

## Project Overview

This project explores patient data to evaluate Evidence-Based Medicine (EBM) outreach effectiveness. It leverages patient demographics and medical service data to identify disparities and opportunities for improvement across race, language, region, and ethnicity.

The dashboard was developed in Power BI, and the analysis uses a dataset of over 6,500 patients. Key performance metrics focus on EBM engagement, aiming to provide actionable insights for targeted healthcare interventions.

---
## Dashboard 

![image](https://github.com/user-attachments/assets/d2f3abd4-4c03-491e-892b-1dbc8240ecf7)

<p align="center">
  View the full Power BI report <a href="https://app.powerbi.com/groups/me/reports/1633dcf4-40d9-4ddc-95aa-f68580730b13/ReportSection?experience=power-bi">HERE</a>

## Dataset Description

The following table outlines the variables included in the dataset:

| Column Name                  | Description                                                       |
|-----------------------------|-------------------------------------------------------------------|
| Member ID Encrypted         | Unique identifier for each patient                                |
| EBM Numerator               | Indicates if the patient received EBM (1 = Yes, 0 = No)           |
| EBM Denominator             | Indicates if the patient was eligible for EBM (1 = Eligible)      |
| ORIG_PREFERRED_LANGUAGE     | Patient's originally recorded preferred language                  |
| SRC_LANGUAGE                | Source language field from system records                         |
| ORIG_RACE                   | Patient's originally recorded race                                |
| SRC_RACE                    | Race field from source system                                     |
| Original Member Ethnicity   | Patient's self-reported or recorded ethnicity                     |
| SRC_ETHNICITY               | Ethnicity field from source system                                |
| Zip (5-digit)               | Postal code used to identify region                               |

---

## Key Questions Answered

1. What percentage of eligible patients received EBM services?
2. How is EBM outreach distributed across different ethnicities, races, languages, and regions?
3. Are there identifiable trends or disparities based on demographic segmentation?

---

## Summary of Key Metrics

![image](https://github.com/user-attachments/assets/e99cf823-f9f0-4404-b362-8d15d9bef9c5)

- **Total Patients:** 6,597
- **EBM Received:** 4,184 (63%)
- **EBM Not Received:** 2,413 (37%)

---

## Insights and Analysis

### EBM by Ethnicity

![image](https://github.com/user-attachments/assets/d131855b-8a65-4e70-95bd-4b7a76d27019)


| Ethnicity                  | Count | Percentage |
|---------------------------|-------|------------|
| Not Hispanic or Latino    | 4,600 | 69.6%      |
| Hispanic or Latino        | 1,500 | 23.4%      |
| Unknown                   | 500   | 6.9%       |

Patients identifying as Hispanic or Latino represent a smaller portion of the overall group. Culturally appropriate outreach materials may be needed.

### EBM by Region

![image](https://github.com/user-attachments/assets/b6f30fb9-a878-4fab-9fba-6de297419c99)

| Region | Count | Percentage |
|--------|-------|------------|
| USCA   | 5,100 | 77.4%      |
| APAC   | 800   | 12.0%      |
| EMEA   | 700   | 9.9%       |

The majority of patients are located in the USCA region, which may already have better infrastructure or outreach programs.

### Preferred Language

![image](https://github.com/user-attachments/assets/f045d697-e668-4ced-b58c-102b4ecf380b)

| Language | Count |
|----------|-------|
| English  | 4,837 |
| Russian  | 499   |
| Korean   | 357   |
| Spanish  | 268   |

Over 73% of patients speak English, but the presence of significant non-English-speaking groups suggests the need for multilingual support.

### Race Breakdown

![image](https://github.com/user-attachments/assets/e258ecf9-48d0-4054-83e1-8b36154e0ad7)

| Race                    | Count |
|-------------------------|-------|
| White                   | 3,207 |
| Unknown                 | 1,539 |
| Asian                   | 883   |
| Black or African Amer.  | 175   |
| Do not wish to answer   | 604   |

A large portion of patients have unknown or unreported race information, limiting precise analysis.

---

## Recommendations

- Translate EBM education materials into top languages (Russian, Korean, Spanish)
- Investigate and address barriers affecting Hispanic and Asian populations
- Improve race/ethnicity data collection for better segmentation
- Explore targeted outreach in APAC and EMEA regions



