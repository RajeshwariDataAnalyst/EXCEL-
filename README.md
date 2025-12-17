# AI Powered Healthcare Data Insights And Dashboard

## Project Overview and Objective:
The system collects and process medical, clinical, and operational datasets, such as patient records,
diagnosis patterns, treatment outcomes, hospital performance metrics, and resource usage.
  
Using Excel tools such as Power Query, Power Pivot, Pivot Tables, Charts, Conditional Formatting,
and basic AI-powered features, the project converts raw medical and operational data into clear, actionable insights.

## Problem Statement:
- Healthcare providers struggle to make informed decisions due to fragmented, unorganized, and complex patient and clinical data.
- Without clear insights, it becomes difficult to identify inefficiencies, predict risks, and improve quality of care.
- Critical insights into patient trends, disease patterns, and treatment outcomes often remain hidden within large datasets.
- Hospitals face challenges in understanding their operational performance across departments.Healthcare teams need a way to identify high-risk patients and emerging trends before they escalate.
## Attribute (Column/Features) Details:
|Attribute | Data Type | Description |
|----------|-----------|-------------|
|Customer ID |Integer / String |Unique identifier for each patient.|
|First Name | String | patients First name|
|BMI| Float |Body Mass Index value indicating the patient's body fat ratio.|
|Weight Status | String | Weight Classification (e.g., Underweight, Normal, Overweight, Obesity).|
|Diabetes Status |Numeric (float) |A numeric indicator representing the severity/level of diabetes.|
|Heart Issues|String  |Shows whether the patient has any diagnosed heart-related issues.|
|Any Transplants|String |Indicates if the patient has undergone any organ transplant.|
|Cancer History | String |Indicates whether the patient has a history of cancer.|
| Number of Surgeries|String |The type/level of surgeries performed (e.g., No major surgery, One major surgery, Two major surgery, Three major Surgery).|
|Smoker |String |Indicates whether the patient is a current smoker.|
|Date of Birth |Date|Patient’s birth date, used for age validation or calculation.|
|Age | Integer|Patient’s current age.|
|Children |Integer |Number of children the patient has.|
|Charges|Float (Currency)|Total medical or insurance charges associated with the patient.|
|Hospital Tier| String | Category of the hospital the patient uses (e.g., tier - 1, tier - 2, tier - 3).|
|City Tier|String |Classification of the city where the patient resides (tier - 1, tier - 2, tier - 3).|
|State ID| String (alphanumeric)|Code identifying the state/region where the patient belongs (e.g., R1013, R1012).|
## Tools and Technologies:
### Excel :
   - **Power Query** : Cleaning And Transforming 
   - **Pivot Table** : Analysis
   - **Pivot Chart** : Visualization
   - **Dashboard** : Monitoring
## Data Pre-Process:
### Task Performed:
   - **Data Cleaning and Transfroming:** Removed duplicates,handled missing values,standardized formats.created calculated fields.
   - **Filtering & Sorting:** Organized data to focus on relevant rows.
   - **Pivot Table:** Generated Pivot Tables for data summarization and initial insights.Convert the data into Fact and Dimension Table.
## Analysis And Visualization:
### Dashboard Feature:
![Alt text](https://github.com/RajeshwariDataAnalyst/EXCEL-/blob/main/Excel%20Dashboard.png)   
### Interactive Visualizations:
- The dashboard includes various charts such as pie charts, bar charts, and line graphs to visualize
key healthcare metrics, including weight status, heart issues, smoking status, and number of surgeries.
### Dynamic Filtering:
- Slicers for attributes like Weight Status and Heart Issues enable users to filter data
   interactively and explore different patient segments.
## Insights:
- The dashboard clearly summarizes patient data by showing the distribution of Weight Status against Heart Issues,
  revealing that a significant portion of patients with obesity experience heart problems, as seen in the pie and bar charts. 
-  show the relationship between smoking and heart issues by comparing smoker and non-smoker groups.
- It also looks at how the number of surgeries a patient has had relates to their health conditions.
- This helps identify important risk factors, like smoking or multiple surgeries, that may contribute to heart problems.
- Understanding these links helps healthcare providers better address and manage patient health risks.
## Conclusion:
The use of Excel’s advanced tools such as Power Query, Pivot Tables, and interactive dashboards proved effective for comprehensive healthcare data analysis transforming raw data into meaningful insights and clear visual reports that support informed decision-making.

  



