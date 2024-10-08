# Healthcare Dataset SQL Analysis

This project analyzes a healthcare dataset sourced from Kaggle [(link)](https://www.kaggle.com/datasets/prasad22/healthcare-dataset). The SQL queries conducted on the Healthcare database provided comprehensive insights into various facets of patient demographics, medical conditions, treatments, financial aspects, and hospital performances. These findings facilitate informed decision-making processes and offer valuable insights for healthcare management and analysis.

## Table of Contents

1. [Data Overview & Basic Statistics](#data-overview--basic-statistics)
2. [Medical Conditions & Medications](#medical-conditions--medications)
3. [Insurance Providers & Hospitals](#insurance-providers--hospitals)
4. [Financial Analysis & Duration of Hospitalization](#financial-analysis--duration-of-hospitalization)
5. [Blood Type Analysis & Donation Matching](#blood-type-analysis--donation-matching)
6. [Yearly Admissions & Insurance Analysis](#yearly-admissions--insurance-analysis)
7. [Patient Risk Categorization](#patient-risk-categorization)
8. [Dataset Column Descriptions](#dataset-column-descriptions)

## Data Overview & Basic Statistics

The dataset was explored to gather a comprehensive view of patient information and healthcare records. Queries included:
- Counting total records.
- Finding the maximum and average ages of hospitalized patients.
- Analyzing patient demographics based on age.

## Medical Conditions & Medications

Detailed insights were derived regarding:
- Prevalent medical conditions.
- Medications prescribed for specific conditions.
- The frequency of their occurrence.

This information assists in understanding the distribution and treatment of various health issues within the dataset.

## Insurance Providers & Hospitals

The project delved into:
- Patient preferences for insurance providers and hospitals based on frequency.
- This data aids in resource allocation, understanding coverage preferences, and evaluating the prominence of healthcare services across different facilities.

## Financial Analysis & Duration of Hospitalization

Financial aspects were scrutinized by examining:
- Average billing amounts associated with different medical conditions.
- Total billing amount and duration of hospital stays for patients across various hospitals.

This helps in understanding costs, hospital efficiency, and patient care duration.

## Blood Type Analysis & Donation Matching

The analysis explored the distribution of blood types among patients, highlighting:
- Potential correlations between age groups and blood type occurrences.
- A stored procedure, `Blood_Matcher`, was created to identify potential donors and recipients based on specific criteria of blood types, age, and hospital affiliation or non-affiliation.

## Yearly Admissions & Insurance Analysis

The analysis extended to:
- Identifying hospitals with patient admissions in specific years (2024 and 2025).
- Understanding billing patterns across different insurance providers.

This aids in understanding patient inflow trends and disparities in billing practices among insurance companies.

## Patient Risk Categorization

A column was created to categorize patients into high, medium, or low-risk categories based on their medical conditions and test results. This categorization allows for a quick assessment of patient status and required follow-up actions.

## Dataset Column Descriptions

Here’s a brief explanation of each column in the dataset:

1. **Name**: Represents the name of the patient associated with the healthcare record.
2. **Age**: The age of the patient at the time of admission, expressed in years.
3. **Gender**: Indicates the gender of the patient, either "Male" or "Female."
4. **Blood Type**: The patient's blood type, which can be one of the common blood types (e.g., "A+", "O-", etc.).
5. **Medical Condition**: Specifies the primary medical condition or diagnosis associated with the patient, such as "Diabetes," "Hypertension," "Asthma," and more.
6. **Date of Admission**: The date on which the patient was admitted to the healthcare facility.
7. **Doctor**: The name of the doctor responsible for the patient's care during their admission.
8. **Hospital**: Identifies the healthcare facility or hospital where the patient was admitted.
9. **Insurance Provider**: Indicates the patient's insurance provider, which can include "Aetna," "Blue Cross," "Cigna," "UnitedHealthcare," and "Medicare."
10. **Billing Amount**: The amount billed for the patient's healthcare services during their admission, expressed as a floating-point number.
11. **Room Number**: The room number where the patient was accommodated during their admission.
12. **Admission Type**: Specifies the type of admission: "Emergency," "Elective," or "Urgent."
13. **Discharge Date**: The date on which the patient was discharged from the healthcare facility, based on the admission date and a random number of days within a realistic range.
14. **Medication**: Identifies a medication prescribed or administered to the patient during their admission (e.g., "Aspirin," "Ibuprofen," "Penicillin," etc.).
15. **Test Results**: Describes the results of a medical test conducted during the patient's admission (e.g., "Normal," "Abnormal," "Inconclusive").

This dataset provides specific information about patients, their admissions, and the healthcare services provided, making it suitable for various data analysis and modeling tasks in the healthcare domain.
