# drug-data-analysis-dashboard
Tableau dashboard for drug data analysis

# 💊 Drug Data Analysis Dashboard

## Project Overview
This project focuses on analyzing a healthcare dataset using data visualization techniques. An interactive dashboard is created using Tableau to explore patterns, trends, and relationships in patient data.

## Dataset
The dataset used is **drug200.csv**, which contains information about patients such as:
- Age
- Sex
- Blood Pressure (BP)
- Cholesterol
- Sodium-to-Potassium Ratio (Na_to_K)
- Drug prescribed

## Dashboard Features
The dashboard includes the following visualizations:

-  Scatter Plot (Age vs Na_to_K)  
-  Histogram (Age Distribution)  
-  Bar Chart (Drug Distribution)  
-  Stacked Bar Chart (BP vs Drug)  

## Interactivity Features
- Filters (Drug, BP, Cholesterol)  
- Highlight Actions  
- Tooltips  
- Drill-down (Use as Filter)

## Key Insights
- Most patients fall between age 30–60  
- DrugY and drugX are most commonly prescribed  
- Na_to_K ratio has strong influence on drug selection  
- No major anomalies found in dataset  

##  Tools Used
- Tableau Desktop  
- CSV Dataset  

## Dashboard Preview
![Dashboard Screenshot](your-image-file-name.png)

## 📂 Files Included
- `drug200.csv` → Dataset  
- `report.pdf` → Project report  
- `dashboard.png` → Dashboard screenshot  

## Conclusion
This project demonstrates how data visualization helps in understanding complex healthcare data and supports better decision-making through interactive dashboards.

## Dataset Explanation

The dataset used in this project is **drug200.csv**, which contains information about 200 patients and the drugs prescribed to them. It is commonly used for analyzing how medical attributes influence drug selection.

### Attributes Description

- **Age**  
  Represents the age of the patient (numerical variable).

- **Sex**  
  Indicates the gender of the patient (Male/Female).

- **BP (Blood Pressure)**  
  Categorized as HIGH, NORMAL, or LOW.

- **Cholesterol**  
  Indicates cholesterol level (HIGH or NORMAL).

- **Na_to_K (Sodium-to-Potassium Ratio)**  
  A numerical value that plays an important role in drug prescription.

- **Drug**  
  The target variable representing the drug prescribed to the patient (drugA, drugB, drugC, drugX, DrugY).

### Purpose of Dataset
The dataset is used to analyze relationships between patient health conditions and drug prescriptions. It helps in understanding which factors influence the selection of specific drugs.

### Type of Data
- Categorical Data → Sex, BP, Cholesterol, Drug  
- Numerical Data → Age, Na_to_K
