# International Students Mental Health Analysis (PostgreSQL)

## Project Overview
This project analyzes 2018 survey data from a Japanese international university to explore the mental health challenges faced by international students. Using SQL (PostgreSQL), the analysis investigates whether depression levels are associated with:

- **Social connectedness** (SCS score)
- **Acculturative stress** (ASISS score)
- **Length of stay** in Japan

The goal was to validate conclusions from the university's original study using data-driven insights.

## Dataset Overview
Each row in the dataset represents a student and includes columns such as:

- `inter_dom`: International or domestic student
- `japanese_cate`: Japanese language proficiency level
- `english_cate`: English language proficiency level
- `academic`: Academic level (undergraduate or graduate)
- `age`: Student age
- `stay`: Years spent in Japan
- `todep`: Depression score (PHQ-9 test)
- `tosc`: Social connectedness score (SCS test)
- `toas`: Acculturative stress score (ASISS test)

## Key Findings
- International students with **low social connectedness** or **high acculturative stress** tended to have higher depression scores.
- Students who had been in Japan longer showed mixed trends in depression, suggesting prolonged adaptation or persistent stress may influence outcomes.
- SQL analysis supports the original study’s conclusion that both **social integration** and **cultural stress** significantly impact mental health.

## Tools Used
- PostgreSQL (via DataCamp Datalab)
- SQL queries using filtering, aggregation, grouping, and sorting
- CSV data exported and analyzed directly through SQL

## Skills Demonstrated
- Data exploration and analysis with SQL
- Use of psychological and demographic metrics in structured queries
- Hypothesis-driven investigation and reporting

## How to Use
1. Load `students.csv` into your PostgreSQL environment
2. Run SQL queries (provided in the notebook) to reproduce the insights
3. Modify filters and groupings to explore additional questions
