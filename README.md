# HealthCare Readmission Analysis(Interactive Dashboard created using PowerBi)
## Project Overview
Interactive Power BI dashboard developed to analyse patient readmission patterns using healthcare data. Includes KPIs, DAX measures, interactive slicers, and data visualizations to compare readmission patterns across different patient and clinical groups.

## Dataset 
The dataset used for this project is:

Healthcare_Patient_Readmission_250k

- 250,000 patient records
- 47 fields
- Time period: 2023–2025
- Main outcome analysed: `Readmission_Flag`
- <a href="https://github.com/Varsha-Kookkal/Healthcare-Readmission-Analysis-PowerBI/blob/main/hospital_bed_occupancy_dataset.xlsx">Dataset</a>
## Questions (KPIs)
- What is the total number of patients?
- How many patients were readmitted?
- What is the overall readmission rate?
- What is the average length of hospital stay?
- What is the average out-of-pocket cost for patients?
- What is the average patient risk score?
- Which disease category has the highest readmission rate?
- Which year has the highest readmission rate?
- Which age group has the highest readmission rate?
- How does readmission rate compare between ICU and Non-ICU patients?
- How are readmissions distributed across severity levels?
- Dashboard Interaction <a href="https://github.com/Varsha-Kookkal/Healthcare-Readmission-Analysis-PowerBI/blob/main/Screenshot%202026-09-06%20080140.png">View Dashboard</a>

## Tools & Technologies

- Microsoft Power BI – Dashboard creation and data visualization
- DAX – Creating measures and calculations
- Power Query – Data cleaning and transformation
- Data Modelling – Creating relationships and Date Table
- Data Visualization – KPIs, charts, and interactive visuals
  
  ## Data Preparation

- Imported the healthcare dataset into Power BI.
- Checked the data for missing values, empty values, and errors.
- Checked and corrected data types where required.
- Selected the relevant fields needed for readmission analysis.
- Created Age Groups for easier comparison of patient age ranges.
- Created ICU Status to convert the 0/1 ICU values into ICU and Non-ICU labels.
- Created a Date Table for date-based analysis.
- Created a relationship between the Date Table and Admission Date.

  
## DAX Measures

Created DAX measures for the main dashboard KPIs:

- Total Patients
- Total Readmissions
- Readmission Rate
- Average Length of Stay
- Average Out-of-Pocket Cost
- Average Patient Risk Score

  ## Dashboard
  <img width="844" height="496" alt="Screenshot 2026-09-06 080140" src="https://github.com/user-attachments/assets/1457542a-3731-4871-be1c-8a7610250ed8" />

  ## Key Insights

- Nephrology had the highest displayed readmission rate among the disease categories.
- The displayed readmission rate showed a slight decline from 2023 to 2025.
- The 61–75 age group had the highest displayed readmission rate.
- ICU and Non-ICU groups had almost similar displayed readmission rates.
- Readmissions were fairly evenly distributed across the different severity levels.

  ## Interactive Features

- Year slicer to analyse readmission patterns for a specific year.
- Severity Level slicer to focus on a specific severity category.
- Interactive filtering across dashboard visuals.
- KPIs and charts update based on the selected filters.

  ## Limitations

- This project is mainly descriptive and shows patterns in the available data.
- The analysis does not establish the exact causes of patient readmission.
- The project does not predict whether an individual patient will be readmitted.
- The quality of the analysis depends on the quality and completeness of the dataset.

 ## Future Scope

- Develop a machine learning model to predict patient readmission risk.
- Include additional patient and hospital-related data for deeper analysis.
- Perform more advanced risk factor analysis.
- Improve the dashboard with additional insights and visualizations.

## Conclusion

This project helped me analyse patient readmission patterns using Power BI and DAX. The interactive dashboard provides a simple way to explore key patient and readmission metrics and compare patterns across different groups.

The insights can help healthcare teams monitor readmission patterns, identify areas that may need closer attention, and support hospital planning and data-driven decision-making.

Overall, this project improved my understanding of data cleaning, DAX, data modelling, data visualization, and interactive dashboard development.

