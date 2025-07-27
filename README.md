# NYC K-8 Public School Student Educational Outcomes: Before & After the Covid-19 Pandemic Lockdown (2016-2024) 
___

## Project Overview

This project aims to find insights, trends and patterns among the NYC K-8 Public School student academic performance and population to determine which factors/combinations of factors may have impacted educational outcomes. 

The project will analyze chronic absenteeism rates, New York State Math Test results  and ELA (English Language Arts) for 3-8th grade students, student enrollment percentages, demographics, and more across the five Boroughs (The Bronx, Manhattan, Brooklyn, Queens, Staten Island.)

Data from before (pre-2020) and after the Covid-19 Lockdown will be compared to establish a baseline from which to evaluate changes from school year to school year (2016-2024)

This information will be used to populate an interactive Tableau Dashboard.

The project is a companion piece to [my other project](https://github.com/thetechleila/NYC-Public-High-School-Student-Performance-2016-to-2024) that examines the same educational ouctomes for **NYC _High School_ students** from 2016-2024 along with Regents exam results and graduation/drop out rates.
___

## Data Sources

The information was obtained from [NYC Open Data](https://opendata.cityofnewyork.us/).

The following datasets were used:

- [**2019-20 Demographic Snapshot - Borough**](https://data.cityofnewyork.us/Education/2019-20-Demographic-Snapshot-Borough/2a5f-5ryi/about_data)
    - Student demographic and enrollment data by **Borough** from 2016-17 through 2020-21.

    - Starts during the 2016-17 school year and ends during the 2020-21 school year

- [**2016-17 - 2020-21 End-of-Year *Borough* Attendance and Chronic Absenteeism Data**](https://data.cityofnewyork.us/Education/2016-17-2020-21-End-of-Year-Borough-Attendance-and/peyw-qepe/about_data)
    - Displays attendance and chronic absenteeism data organized by Borough (Manhattan, Brooklyn, The Bronx, Queens, Staten Island)
     - Overall attendance data include students in Districts 1-32  
        - District 75 (Special Education) and Students in District 79 (Alternative Schools & Programs), charter schools, home schooling, and home and hospital instruction are *excluded.* 
        - Pre-K data do not include NYC Early Education Centers or District Pre-K Centers; therefore, Pre-K data are limited to those who attend K-12 schools that offer Pre-K.

- [**2018-19 - 2023-24 End-of-Year _Borough_ Attendance and Chronic Absenteeism Data Set**](https://infohub.nyced.org/reports/students-and-schools/school-quality/information-and-data-overview/end-of-year-attendance-and-chronic-absenteeism-data)

- [**English Language Arts (ELA) Test Results 2013-2023**](https://data.cityofnewyork.us/Education/English-Language-Arts-ELA-Test-Results-2013-2023/iebs-5yhr/about_data)

    - This report includes results for the New York State English Language Arts exams for the years 2013-2023.
    - Data is organized by Borough, School District, and overall Citywide.
    - The New York State ELA Test is administered to 3rd - 8th grade students


- [**Math Test Results 2013-2023**](https://data.cityofnewyork.us/Education/Math-Test-Results-2013-2023/74kb-55u9/about_data)

    - This report includes results for the New York State Math exams for the years 2013-2023.
    - Data is organized by Borough, School District, and overall Citywide.
    - NY State Math Exams are administered to 3rd - 8th grade students
___

## Tools

- Python
- NumPy for mathematical & statistical operations
- Pandas for data manipulation
- Matplotlib & Seaborn for data visualization
- Jupyter Notebooks