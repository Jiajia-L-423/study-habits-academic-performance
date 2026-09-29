# 📊 Study Habits and Academic Performance

> **Research Question:** How are students' study-related behaviors associated with their academic performance in a mathematics course?

## 📌 General Information

**Project Description:**  
This learning analytics project examines the relationship between students' study-related behaviors and their academic performance in a mathematics course. The study focuses on weekly study time, school absences, and participation in extracurricular activities, with the final mathematics grade used as the measure of academic performance.

**Researcher:** Jiajia Li  
**Affiliation:** Teachers College, Columbia University  
**Program:** M.S. in Learning Analytics  
**ORCID:** 0009-0000-4314-9794  
**Data Source:** UCI Machine Learning Repository – Student Performance Dataset  
**Subject Area:** Education / Learning Analytics  
**Keywords:** Learning Analytics, Study Habits, Academic Performance, Student Performance, Mathematics Education  
**Language:** English
**Geographic Location:** Portugal (data collected from two Portuguese secondary schools: Gabriel Pereira and Mousinho da Silveira)
**Data Collection Date:** Not specified in the dataset documentation  
**Funding:** Not specified in the dataset documentation
## 📁 Data & File Overview

This project uses the **Mathematics course dataset (`student-mat.csv`)** from the UCI Student Performance Dataset. The dataset contains student achievement data from two Portuguese secondary schools and includes student grades, demographic, social, and school-related information.

**Dataset Used:** Student Performance – Mathematics Course  
**Original File:** `student-mat.csv`  
**Working File:** `student-mat-clean.xlsx`  
**File Format:** CSV (original), XLSX (working copy)  
**Number of Cases:** 395 students  
**Number of Variables:** 33  
**Missing Values:** None reported in the original dataset documentation  
**Repository Source:** UCI Machine Learning Repository  
**Dataset DOI:** `10.24432/C5TG7T`

## 📂 File Structure

```text
study-habits-academic-performance/
├── README.md
└── data/
    ├── student-mat.csv
    └── student-mat-clean.xlsx
        ├── student-mat-clean (worksheet)
        └── Data Dictionary (worksheet)
```
## 🔓 Sharing & Access Information

**License:** Creative Commons Attribution 4.0 International (CC BY 4.0)

The original Student Performance dataset is publicly available through the UCI Machine Learning Repository. It may be shared and adapted for any purpose, provided that appropriate credit is given.

**Dataset Source:** UCI Machine Learning Repository – Student Performance Dataset

**Dataset DOI:** 10.24432/C5TG7T

**Recommended Citation:**  
Cortez, P. (2008). *Student Performance* [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5TG7T

**Access Restrictions:** None. The original dataset is publicly available.
## 🔬 Methodological Information

### Study Design
This project uses a quantitative, observational approach to examine the association between students' study-related behaviors and academic performance.

### Data Collection
The data were originally collected from two Portuguese secondary schools using school reports and questionnaires. This project uses the Mathematics course dataset (`student-mat.csv`), which contains 395 student records and 33 variables.

### Variables of Interest
The analysis focuses on three study-related variables:

- **studytime:** Weekly study time, coded from 1 to 4.
- **absences:** Number of school absences.
- **activities:** Participation in extracurricular activities, coded as `yes` or `no`.

Academic performance is measured using:

- **G3:** Final mathematics grade, ranging from 0 to 20.

### Data Processing
The original semicolon-delimited CSV file was preserved without modification. A separate working copy (`student-mat-clean.xlsx`) was created for data preparation and documentation. The data were separated into individual columns, variable names were retained, and a Data Dictionary worksheet was added to document the variables, measurement units, and allowed values or ranges.

### Data Quality Assurance
The working dataset was checked for proper column separation and variable structure. According to the original dataset documentation, no missing values are reported. Variable ranges and categorical codes were documented in the Data Dictionary to support consistency and interpretation.

### Software
- Microsoft Excel – data preparation, organization, and Data Dictionary creation
- GitHub – README documentation, file storage, and version tracking
## 🧾 Data-Specific Information

The Mathematics course dataset contains **395 student records and 33 variables**. Each row represents one student, and each column represents a demographic, social, school-related, behavioral, or academic variable.

### Variable Documentation
A complete Data Dictionary is included in the `Data Dictionary` worksheet of `student-mat-clean.xlsx`. The dictionary documents all 33 variables and includes:

- Variable name
- Description
- Data type
- Measurement / unit
- Allowed values / range

### Key Variables for This Project

| Variable | Description | Measurement / Allowed Values |
|---|---|---|
| `studytime` | Weekly study time | 1 = <2 hours; 2 = 2–5 hours; 3 = 5–10 hours; 4 = >10 hours |
| `absences` | Number of school absences | 0–93 |
| `activities` | Participation in extracurricular activities | yes; no |
| `G3` | Final mathematics grade | 0–20 |

### Missing Data
The original dataset documentation reports **no missing values**. Therefore, no special missing-value code is used in this dataset.

### Data Dictionary Location
`data/student-mat-clean.xlsx` → `Data Dictionary` worksheet
