# Project Background
**Manufacturing Downtime**

Productivity & downtime data for a soda bottling production line, including information on the operator, product, start & end times, and dowtime factors for each batch.

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
The current line efficiency, at a critically low 11%, underscores significant operational inefficiencies that demand immediate attention. Operator performance analysis reveals varying levels of productivity and efficiency. Charles and Dee show moderate performance, achieving efficiencies of 66.84% and 64.08% while working on three products each. Dennis exhibits slightly lower efficiency (63.17%) with three products, indicating potential underperformance. Mac, although achieving the highest efficiency at 71.94%, works on four products with the lowest productivity time (12hrs or 720 minutes), suggesting an imbalance in workload distribution and operational capability. These findings highlight the need for a more strategic allocation of tasks and enhanced performance support.

Downtime factors further illustrate systemic issues impacting productivity. **Machine Adjustment** (23.92%) and **Machine Failure** (18.3%) are the leading contributors, indicating the need for improved equipment reliability and maintenance schedules. **Inventory shortages** (16.21%) and batch-related issues such as **Batch Changes** (11.53%) and **Batch Coding Errors** (10.45%) exacerbate inefficiencies. Operator-specific challenges reveal significant error rates: Charles and Dennis struggle with **Machine Adjustments** (118 and 120 minutes errors, respectively), while Mac's high **Batch Change errors**(130 mins) indicate procedural inefficiencies. Dee shows gaps in **Calibration** (25 mins errors) and **Labelling Switches** (23 mins errors), highlighting skill gaps in detail-oriented tasks. Addressing these issues through targeted training, workflow optimization, and investment in automation and preventive maintenance is critical to enhancing operational efficiency and minimizing downtime.

Below is the overview page from the PowerBI dashboard and more examples are included throughout the report. The entire interractive dashboard can be accessed [here](https://app.powerbi.com/view?r=eyJrIjoiY2E0NjhlODEtOTA2My00Nzc5LTgwN2UtMmU4ZDRlZTUxNTk0IiwidCI6IjJkZTU1ZjVjLWQwMDMtNGQyYS04MjZiLWVhZDJhOWYyYjljZCJ9)
![image_alt](https://github.com/princeabdul99/soda_bottling_production_line/blob/8594047cfcb302ebd0e9a7a561ffe0023b2ced96/overview.jpg)

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
     
          
#### Downtime Factor:
- **Major Contributors to Downtime**
    - **Machine Adjustment**: 23.92%. Leading cause of downtime, suggesting the need for regular maintenance or operator training to minimize adjustments.
    - **Machine Failure**: 18.30%. Significant contributor to downtime, emphasizing the need for improved machine reliability or a preventive maintenance schedule.
    - **Inventory Shortage**: 16.21% Highlights a supply chain or inventory management issue that needs attention.
      
- **Moderate Contributors**
    - **Batch Change**: 11.53% Reflects time spent transitioning between batches. Streamlining processes could reduce downtime here.
    - **Batch Coding Error**: 10.45% Indicates potential issues in the coding process that may require better automation or operator training.
    
- **Minor Contributors**
    - **Calibration Error**: 3.53% Low impact but still requires periodic calibration checks.
    - **Labelling Error**: 3.03% Indicates manageable but noticeable downtime due to labeling issues.
    - **Labelling Switch**: 2.38% Minimal impact; still worth monitoring for further reduction.
    - **Product Spill**: 4.11% Suggests some inefficiency in handling or equipment setup.
    - **Others**: 5.33% Catch-all category; further analysis may be needed to identify and address recurring issues.


![image_alt](https://github.com/princeabdul99/soda_bottling_production_line/blob/a6b32c30a6a03ec254fc0555ea5ceb4cad888d8e/dowtime-factor.jpg)

#### Operator Challenges:
- **Charles**
      - Struggles significantly with Machine Adjustment (118 mins errors), the highest for this category.
      - Moderate issues with Batch Coding Errors (46 mins) and Calibration Errors (24 mins).
      
- **Dee**
      - Exhibits a balanced error distribution but stands out in Labelling Switch Errors (23 mins) and Calibration Errors (25 mins).
      
- **Dennis**
      - Machine Adjustment (120 mins errors) is a clear area of struggle, the highest among operators.
  
- **Mac**
      - Exceptional struggles with Batch Changes (130 mins errors), far exceeding others in this category.
      - Moderate issues with Batch Coding Errors (47 mins).

  
![image_alt](https://github.com/princeabdul99/soda_bottling_production_line/blob/087872658037b1549eb096258b96a435ee0c6160/operator%20downtime%20factor.jpg)

### Recommendations:
Based on the unconvered insights, the following recommendations have been provided;
1. **Training and Skill Development:**
   - **Charles and Dennis**: Provide targeted training on equipment operation and maintenance to reduce **Machine Adjustment** errors.
   - **Mac**: Conduct training on batch change procedures and explore automation to reduce manual interventions.

2. **Process Optimization:**
   - Review and streamline Batch Change workflows, especially for **Mac**, to identify inefficiencies and implement improvements.
   - Standardize calibration procedures and enhance quality control to address issues faced by **Charles and Dee**.

3. **Enhanced Monitoring and Support:**
   - Implement real-time error monitoring to identify recurring patterns and address issues promptly.
   - Assign mentors or supervisors to operators with high error counts for immediate feedback and guidance.

4. **Invest in Automation:**
   - Evaluate opportunities for automation in high-error processes, such as **Batch Changes** and **Machine Adjustments**, to reduce reliance on manual operations and improve consistency.

By focusing on these targeted interventions, overall operator performance can be enhanced, reducing errors and improving operational efficiency.
