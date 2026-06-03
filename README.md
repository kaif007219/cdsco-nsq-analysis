# CDSCO NSQ Intelligence

Analysis of CDSCO Not of Standard Quality (NSQ) drug alerts to identify pharmaceutical quality failure patterns across dosage forms, therapeutic classes, and manufacturers.

## Problem Statement

Pharmaceutical quality failures can arise due to formulation issues, manufacturing variability, stability concerns, or process deviations. This project transforms publicly available CDSCO NSQ alerts into actionable quality intelligence with a special focus on dissolution-related failures.

## Dataset

* CDSCO NSQ Alert Reports
* March 2025
* June 2025

## Methodology

1. Extracted tabular data from CDSCO PDF reports using Camelot
2. Cleaned and standardized failure records
3. Categorized laboratory observations into major failure categories
4. Classified products by dosage form and therapeutic class
5. Performed exploratory and cross-tabulation analysis
6. Built interactive visualizations and dashboards

## Key Findings

* Assay and Dissolution were the most common NSQ failure categories
* Dissolution failures were concentrated in oral solid dosage forms
* Certain therapeutic classes appeared repeatedly among dissolution-related alerts
* Injectable products showed stronger associations with particulate matter and sterility-related failures

## Sample Visualizations

<img width="1152" height="679" alt="output_29_0" src="https://github.com/user-attachments/assets/dbc1739d-4a23-4954-9806-8940b61d1b55" />
<img width="977" height="659" alt="output_34_0" src="https://github.com/user-attachments/assets/3bb56ed7-113a-4a62-8113-dc787b7ee2f2" />
<img width="1016" height="790" alt="output_41_0" src="https://github.com/user-attachments/assets/ac46b77a-3e29-44e8-b7d5-7f1e8a50a728" />
<img width="1016" height="790" alt="output_52_0" src="https://github.com/user-attachments/assets/0f2837c0-c184-4a1e-bfa6-3ec93269fc78" />

## Tech Stack

* Python
* Pandas
* Matplotlib
* Seaborn
* Camelot
* Jupyter Notebook

## Author

Altamash Alam
Biomedical Engineering, IIT (BHU) Varanasi
