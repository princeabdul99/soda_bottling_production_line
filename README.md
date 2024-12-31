# Project Background
Manufacturing Downtime

The company has significant amount of data on its manufacturing Productivity and Downtime that has been previously underutilized. 
This project thoroughly analyzes and synthesizes the data in order to uncover critical insight that will improve the bottling production line success.

Insights and recommendations are provided on the following key areas:
- **Efficiency:** An evaluation on the current line of efficiency.
- **Operator Performance:** An assessment on operators performance, understanding their impact on production.  
- **Downtime Factor:** An assessment on the leading factor of downtime.
- **Operator Challenges:** An evaluation on operators challenges with different downtime factors.

An interractive PowerBI dashboard can be accessed [here](https://app.powerbi.com/view?r=eyJrIjoiY2E0NjhlODEtOTA2My00Nzc5LTgwN2UtMmU4ZDRlZTUxNTk0IiwidCI6IjJkZTU1ZjVjLWQwMDMtNGQyYS04MjZiLWVhZDJhOWYyYjljZCJ9)

# Data Structure & Initial Checks
The CSV data file consist of multiple tables: Products, Line productivity, Line downtime, Downtime factors with a row count of 94 records.

![image_alt](https://github.com/princeabdul99/soda_bottling_production_line/blob/2c9f2cb52248f81d8c53f1cd8ecce258a0b503b4/manufacturing_downtime-erd.png)

Prior to begining the analysis, a variety of checks where conducted for quality control and familiarization with datasets. The raw data file can be found [here]()

# Executive Summary

### Overview Findings
The current line efficiency, at a critically low 11%, underscores significant operational inefficiencies that demand immediate attention. Operator performance analysis reveals varying levels of productivity and efficiency. Charles and Dee show moderate performance, achieving efficiencies of 66.84% and 64.08% while working on three products each. Dennis exhibits slightly lower efficiency (63.17%) with three products, indicating potential underperformance. Mac, although achieving the highest efficiency at 71.94%, works on four products with the lowest productivity (12hrs or 720 minutes), suggesting an imbalance in workload distribution and operational capability. These findings highlight the need for a more strategic allocation of tasks and enhanced performance support.

Downtime factors further illustrate systemic issues impacting productivity. Machine Adjustment (23.92%) and Machine Failure (18.3%) are the leading contributors, indicating the need for improved equipment reliability and maintenance schedules. Inventory shortages (16.21%) and batch-related issues such as Batch Changes (11.53%) and Batch Coding Errors (10.45%) exacerbate inefficiencies. Operator-specific challenges reveal significant error rates: Charles and Dennis struggle with Machine Adjustments (118 and 120 errors, respectively), while Mac's high Batch Change errors (130) indicate procedural inefficiencies. Dee shows gaps in Calibration (25 errors) and Labelling Switches (23 errors), highlighting skill gaps in detail-oriented tasks. Addressing these issues through targeted training, workflow optimization, and investment in automation and preventive maintenance is critical to enhancing operational efficiency and minimizing downtime.

Below is the overview page from the PowerBI dashboard and more examples are included throughout the report. The entire interractive dashboard can be downloaded [here]()

#### Operator Performance:
- Highest Efficiency: Mac (71.94%) – likely due to focus on fewer time-consuming tasks.
- Highest Productivity Hrs: Charles (19.30 Hrs or 1158 Minutes) – indicative of sustained engagement.
- Potential Underperformance: Dennis has the lowest productivity and efficiency among those handling 3 products. May require additional training or workload adjustments.
    ##### Individual Performance
    - **Charles**
        - Productivity Time: 19.30 Hrs or 1158 Minutes
        - Operator Efficiency: 66.84%
        - Number of Products Worked On: 3
        - Observation: Moderate efficiency; productivity minutes are the highest among operators. No signs of underperformance.
    - **Dee**
        - Productivity Time: 17.17 Hrs or 1030 Minutes
        - Operator Efficiency: 64.08%
        - Number of Products Worked On: 3
        - Observation: Slightly lower efficiency and productivity than Charles but still within acceptable range. No significant underperformance.
    - **Dennis**
        - Productivity Time: 13.67 Hrs or 820 Minutes
        - Operator Efficiency: 63.17%
        - Number of Products Worked On: 3
        - Observation:  Lowest efficiency among operators working on 3 products. Productivity minutes are notably lower than Charles and Dee, indicating potential underperformance.
    - **Mac**
        - Productivity Time: 12 Hrs or 720 Minutes
        - Operator Efficiency: 71.94%
        - Number of Products Worked On:  4
        - Observation: Highest efficiency but lowest productivity minutes. Managed to work on 4 products despite lower overall time. No significant underperformance.
     
          
##### Downtime Factor:
- 
-
-
-
##### Operator Challenges:
- 
-
-
-

### Recommendations:
Based on the unconvered insights, the following recommendations have been provided;
- Investigate factors affecting Dennis’s performance (e.g., complexity of tasks, resource availability, or skills gap).
- Consider if Mac’s higher efficiency could be leveraged to redistribute tasks or optimize workflows.
- Maintain monitoring of Dee's and Charles’s performance to ensure consistency.
