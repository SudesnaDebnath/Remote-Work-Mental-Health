# Remote-Work-Mental-Health
Analyzing Mental Well-being in a Remote Work Era

## The Situation:
Help an organization to find **impact of remote work on Mental Health** by creating a Analytics Dashboard using **PowerBI**

## Raw Data
You can directly access and download the raw [CSV file](https://github.com/SudesnaDebnath/Remote-Work-Mental-Health/blob/main/Impact_of_Remote_Work_on_Mental_Health.csv)

#### About Dataset
As remote work becomes the new norm, it's essential to understand its impact on employees' mental well-being. This dataset dives into how working remotely affects stress levels, work-life balance, and mental health conditions across various industries and regions.

With 5,000 records collected from employees worldwide, this dataset provides valuable insights into key areas like work location (remote, hybrid, onsite), stress levels, access to mental health resources, and job satisfaction. It’s designed to help researchers, HR professionals, and businesses assess the growing influence of remote work on productivity and well-being. 🌿📈

**Columns:**

Employee_ID: Unique identifier for each employee.

Age: Age of the employee.

Gender: Gender of the employee.

Job_Role: Current role of the employee.

Industry: Industry they work in.

Work_Location: Whether they work remotely, hybrid, or onsite.

Stress_Level: Their self-reported level of stress.

Mental_Health_Condition: Any mental health condition reported (Anxiety, Depression, etc.).

Social_Isolation_Rating: A self-reported rating (1-5) on how isolated they feel.

Satisfaction_with_Remote_Work: How satisfied they are with remote work arrangements (Satisfied, Neutral, Unsatisfied).

## The Objective:
#### 1. Connect and Transform the Raw Data
Using Query Editing Tools in **PowerBI** Transform the raw data in the back-end, and organized them before loading data into front-end of PowerBI

#### 2. Create Calculated Columns & Measures with DAX
Use calculted columns for filtering.
Use measures for aggreating values.
Use Expllicit measures.(Explicit measures can be referenced anywheere, and nested within ohter measures)
Use fully-qualified column references in measures(This makes DAX more readable, and differentiates column references from measure references)

**Note:** 
Here We have only one Table(one csv file) 
so No need to build a relational data model 
No need to worry about the relationship between tables

#### 3. Design an Interactive Dashboard to Visualize the Data
Use Matrix, KPI, Cards, Bar Charts, Pie Charts, Donut Charts,... etc. Filtering, formating, and design to get better view for End User. Also use Interractions to customize how filters applied to one visual impact other visuals on the page Use Bookmarks capture the current state of a page, and allow users to return to that state using report actions.
**Target:** Easy to understand for End-User

## Conclusion:
A well-designed dashboard should serve a distinct purpose for a distinct audience, use clear and effective metrics and visuals, and provide a simple, intutive user experience.

[Check Dashboard](https://github.com/SudesnaDebnath/Remote-Work-Mental-Health/blob/main/Remote%20Work%20%26%20Mental%20Health%20Report.pbix)

