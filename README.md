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

## Tool
-MS Excel

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
- I created two columns Length Of Stay by subtracting Admission date from Discharge date using this function ```=M2-F2```, and Age Groups using ```=IF(A2<13, "Below 13",
   IF(A2<=19, "13-19",
   IF(A2<=29, "20-29",
   IF(A2<=39, "30-39",
   IF(A2<=49, "40-49",
   IF(A2<=59, "50-59",
   IF(A2<=69, "60-69",
   IF(A2<=79, "70-79", "Above 80"))))))))```.

## Key Findings
Some of the key insights derived from the analysis include:
- Identified the most prevalent disease conditions, frequently prescribed medication and distribution of test results.
- Demographic Trends: Uncovered trends in patient outcomes based on age, gender, and other demographics.
- Resource Utilization: Provided insights into how hospitals can optimize their resources for better patient care.

## Tools and Technologies
- Microsoft Excel: Primary tool used for data cleaning, analysis, and visualization.
- Excel Features: Utilized pivot tables, conditional formatting, VLOOKUP, and other advanced Excel functions.
- Data Visualization: Created charts and graphs using Excel's built-in charting tools
