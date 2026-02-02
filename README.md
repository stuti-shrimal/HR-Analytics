# HR Analytics Dashboard

A comprehensive HR Analytics dashboard built with Tableau to visualize and analyze key human resources metrics, focusing on employee attrition patterns, demographics, job satisfaction, and workforce composition. This project enables data-driven decision-making for HR professionals and organizational leadership.

## 📊 Project Overview

This Tableau workbook analyzes HR data for 1,470 employees across multiple dimensions including demographics, job roles, satisfaction levels, and attrition patterns. The interactive visualizations help identify key factors contributing to employee turnover and provide insights into workforce composition and employee satisfaction.

## 🎯 Key Features

- **Comprehensive Attrition Analysis**: Multiple views analyzing attrition by gender, age groups, education level, and department
- **Employee Demographics**: Detailed breakdown of workforce by age bands, gender, department, and education field
- **Job Satisfaction Metrics**: Track and analyze employee satisfaction ratings across different dimensions
- **KPI Dashboard**: Monitor key performance indicators including attrition rate, active employees, and attrition count
- **Age Group Analysis**: Visualize employee distribution and attrition patterns across different age bands
- **Department-wise Insights**: Compare metrics and attrition rates across organizational departments
- **Interactive Parameters**: Adjustable bin sizes for flexible age group analysis

## 📈 Worksheets Included

1. **KPI**: Key performance indicators showing attrition count, attrition rate, and active employees
2. **Attrition by Gender**: Gender-based attrition analysis with custom color palette
3. **Attrition Rate By Gender for different Age Groups**: Cross-sectional analysis of gender and age
4. **Attrition by Education**: Breakdown of attrition patterns by education level
5. **Department wise Attrition**: Comparative analysis of turnover across departments
6. **Job Satisfaction Rating**: Employee satisfaction metrics and trends
7. **Number of Employees by Age**: Age distribution visualization with adjustable bin parameters

## 🛠️ Built With

- **Tableau Desktop 2025.3.2** - Data visualization and dashboard creation
- **Data Source**: Excel file (HR Data.xlsx) containing 1,470 employee records
- **Version**: Tableau 2025.3 (Build 20253.26.0109.0333)


## 🚀 Getting Started

## 📊 Data Structure

The HR Data.xlsx file contains 39 fields analyzing 1,470 employee records:

**Employee Information:**
- Employee Number, Age, Gender, Marital Status
- Distance From Home, Over18 status

**Job Details:**
- Department, Job Role, Job Level
- Business Travel frequency
- Years At Company, Years In Current Role
- Years Since Last Promotion, Years With Curr Manager
- Total Working Years, Num Companies Worked

**Compensation:**
- Monthly Income, Monthly Rate
- Daily Rate, Hourly Rate
- Percent Salary Hike, Stock Option Level

**Performance & Satisfaction:**
- Performance Rating
- Job Satisfaction, Environment Satisfaction
- Relationship Satisfaction, Work Life Balance
- Job Involvement

**Education:**
- Education (level)
- Education Field

**Attrition:**
- Attrition (Yes/No)
- Over Time (Yes/No)
- Training Times Last Year

**Calculated Fields:**
- CF_age band (custom age groupings)
- CF_attrition label (custom attrition labels)
- CF_current Employee (active employee indicator)
- Attrition Count (calculated measure)
- Attrition Rate (calculated measure)
- Active Employees (calculated measure)

## 💡 Key Insights

This dashboard helps answer critical HR questions such as:

- **What is the overall attrition rate?** Track the percentage of employees leaving and count of attritions
- **How does attrition vary by gender?** Compare male vs female attrition patterns with custom visualizations
- **Which age groups have the highest turnover?** Analyze attrition across different age bands
- **Does education level impact retention?** Examine relationship between education and attrition
- **Which departments experience the most attrition?** Department-wise comparison of turnover rates
- **What are the job satisfaction levels?** Monitor employee satisfaction ratings across the organization
- **How is the workforce distributed by age?** View employee count across age groups with adjustable bin sizes
- **What factors correlate with attrition?** Explore relationships between overtime, business travel, work-life balance, and turnover

## 🔧 Technical Details

### Calculated Fields

The workbook includes several key calculated fields:

1. **Attrition Count**: Counts the number of employees who have left
2. **Attrition Rate**: Calculates the percentage of employee turnover
3. **Active Employees**: Tracks current employee headcount

### Parameters

- **Age Bin**: Adjustable parameter (range: 2-10) for customizing age group bin sizes in the age distribution analysis

### Custom Color Palette

- **Attrition by Gender**: Uses a custom color palette (#fbb78f, #9467bd) for gender-based visualizations

## 🔄 Future Enhancements

- [ ] Add time-series analysis to track attrition trends over months/years
- [ ] Create predictive models for attrition risk scoring
- [ ] Build compensation analysis dashboard comparing salary vs performance
- [ ] Add promotion path visualization showing career progression patterns
- [ ] Include correlation analysis between job satisfaction and retention
- [ ] Integrate cost-per-hire and recruitment metrics
- [ ] Develop manager-level dashboards with drill-down capabilities
- [ ] Add employee tenure analysis and survival curves

## 📝 Usage Instructions

### Exploring the Worksheets

1. **KPI Sheet**: Start here to see overall metrics - total attrition count, attrition rate percentage, and active employee count

2. **Attrition by Gender**: View gender-based attrition patterns with custom color coding

3. **Attrition Rate By Gender for different Age Groups**: Analyze how age and gender intersect in attrition patterns

4. **Attrition by Education**: Understand which education levels have higher turnover rates

5. **Department wise Attrition**: Compare attrition across different organizational departments

6. **Job Satisfaction Rating**: Examine employee satisfaction levels across the organization

7. **Number of Employees by Age**: Visualize workforce age distribution
   - Use the Bin Size parameter (2-10) to adjust age group granularity

### Interactive Features

- **Filters**: Apply filters for specific departments, job roles, or demographic segments
- **Highlighting**: Click on any data point to highlight related information across visualizations
- **Parameters**: Adjust the Bin Size parameter to change age group intervals
- **Tooltips**: Hover over visualizations for detailed information

### Exporting & Sharing

- Export worksheets as images: Right-click > Export > Image
- Share insights: File > Export > PDF to create comprehensive reports

## 📊 Dataset Overview

- **Total Records**: 1,470 employees
- **Data Points**: 39 fields per employee
- **Analysis Focus**: Attrition patterns, demographics, job satisfaction, and compensation
- **Custom Fields**: 3 calculated dimensions and 3 calculated measures
- **Visualizations**: 7 interactive worksheets with multiple chart types

## 🌟 Project Highlights

- **Comprehensive Analysis**: Multi-dimensional view of HR data including demographics, satisfaction, and attrition
- **Custom Calculations**: Purpose-built measures for attrition rate, active employees, and attrition count
- **Interactive Parameters**: Adjustable bin sizes for flexible age group analysis
- **Custom Visualizations**: Gender-based attrition analysis with custom color schemes
- **Clean Design**: Professional visualizations optimized for executive presentation

## 💼 Business Applications

This dashboard can be used by various stakeholders:

**HR Managers:**
- Identify high-risk departments for targeted retention programs
- Understand demographic patterns in workforce composition
- Monitor satisfaction levels to improve employee engagement

**Executive Leadership:**
- Track key HR KPIs at a glance
- Make data-driven decisions on talent strategy
- Identify cost implications of attrition

**Department Heads:**
- Compare their department's metrics against organizational averages
- Understand team composition and satisfaction levels
- Plan for succession and recruitment needs

**Talent Acquisition:**
- Identify patterns in successful hires (low attrition)
- Understand educational and demographic profiles of retained employees
- Optimize recruitment strategies based on attrition data

## 👤 Author

**Stuti Shrimal**
