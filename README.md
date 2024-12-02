# Patient_Healthcare
![](https://github.com/Farouk-Muda/Patient_Healthcare/blob/main/dataset-cover.jpg)

## Project Overview
This project involves the analysis of healthcare datasets to identify trends in patient outcomes, hospital performance, and other critical healthcare metrics. 

## Objectives
The primary objectives of this project are:
- To clean and prepare the healthcare dataset for analysis.
- To analyze patient outcomes and hospital performance using various statistical methods.
- To create interactive visualizations in Excel that provide insights into the data.
- To generate a comprehensive report that highlights key trends, insights, and recommendations for healthcare improvements.

## Tools and Technologies
- Microsoft Excel: Primary tool used for data cleaning, analysis, and visualization.
- Excel Features: Utilized pivot tables, conditional formatting, VLOOKUP, and other advanced Excel functions.
- Data Visualization: Created charts and graphs using Excel's built-in charting tools

## Dataset
- Source: This is a dummy dataset from kaggle [Healthcare Dataset](https://www.kaggle.com/datasets/prasad22/healthcare-dataset) contains information on various healthcare metrics, including patient demographics, treatment outcomes, hospital efficiency, and more.
- Size: It consists of 54,967 rows and 15 columns, each representing a synthetic patient healthcare record.
- Features: The columns are patient name, age, gender, blood type, insurance provider, hospital name, length of stay, admission type, billing amount and other relevant healthcare indicators.

## Data Cleaning and Preparation
Data cleaning and preparation were performed to ensure the dataset was ready for analysis:
- Handling incorrect capitalization: I created a new column and used the function ```=PROPER(A2)``` to ensure standardized name capitalization. 
- Handling Missing Values: I filtered columns to visually inspect rows with empty cells.
- Data Normalization: I ensured all ages are positive integers, within valid age range, standard gender labels, normalize blood types to standardized values, dates follow the same format. 
- Outlier Detection: I searched for extremely high or low values in columns like age and billing amount.
- I created two columns Length Of Stay and Age Groups to Calculate the number of days a patient stayed in the hospital and categorize
 patients into age groups for analysis respectively.
  
## Key Findings
Some of the key insights derived from the analysis include:
- The average age of patients is **52 years**.
- The male and female patient population is nearly balanced at **27.5K each**.
- The three primary types of admissions are nearly equally distributed: **Elective (18.47K), Emergency (18.39K)**, and **Urgent (18.10K)**.
- **Elective admissions** have the highest length of stay approximately 6K.
- Admissions have shown a sharp decline towards the end of the timeline.
- **Cigna** contributes the highest revenue at **€284.34M**, followed closely by **Medicare (€282.91M)**.
- The average billing amount is **€25,545**, which indicates the cost burden on patients or insurers.
- The leading conditions are **Arthritis, Diabetes, Hypertension, Obesity,** and **Cancer**, each affecting approximately **9.2K** patients.
- The most frequently prescribed medications are **Lipitor (11.04K)** and **Ibuprofen (11.02K)**.
- The doctor with the highest number of patients is **Michael Smith (27 patients)**, followed by **John Smith (22 patients)**.
- The age groups **40-49** and **50-59** are predominant, followed by **60-69**.
- The dataset provides the distribution of blood groups with significant representation across all types.
- Results are distributed among **Normal (18.33K)**, **Abnormal (18.44K)**, and **Inconclusive (18.20K**).

## Recommendations for stakeholders
- Focus resources on managing top medical conditions like Diabetes and Hypertension.
- Develop strategies to reduce the length of stay for elective cases.
- Monitor declining admission rates and identify the underlying causes.
- Collaborate with top revenue-generating insurance providers for strategic partnerships.
- Ensure sufficient supply of frequently prescribed medications to meet patient demand.
- Align staff resources with patient admission trends to maintain quality care delivery.

