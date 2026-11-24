# HR Analytics Power BI Dashboard

An interactive Power BI dashboard built to analyze employee attrition patterns, workforce demographics, compensation slabs, tenure, and job satisfaction scores across departments.

## Key KPIs & Visuals
- **KPI Cards:** Total Employees, Attrition (`AttritionCount`), Attrition Rate (%), Average Age, Average Monthly Salary, and Average Years at Company.
- **Department Slicer:** Dynamic cross-filtering across Human Resources, Research & Development, and Sales.
- **Visual Breakdowns:**
  - Attrition by Education Field (Donut Chart)
  - Attrition by Age Group (Column Chart)
  - Job Role vs. Job Satisfaction Score (Matrix)
  - Attrition by Salary Slab (Horizontal Bar Chart)
  - Attrition by Years at Company (Area Chart)
  - Gender Distribution (Treemap)

## Data Preparation & Modeling (Power Query & DAX)
- Cleaned missing/null values, checked duplicates, standardized categorical values, and verified data types in **Power Query Editor**.
- Created an `AttritionCount` conditional column (`Yes` → `1`, `No` → `0`) to enable accurate summation across visuals.
- Built DAX measures (including **Attrition Rate**) and formatted percentages and numeric precision cleanly.

## Key Insights
- Tracks where attrition is highest by age bracket, salary tier, tenure milestone, and job role to support targeted retention actions.
