# Greenfield School Results: Excel Data Cleaning & Analysis

A guided Excel project: Cleaned and analysed three terms of messy school results in Excel (Power Query, formulas, charts) and summarised findings for a principal.

> **Note:** This is a training project from the Project Builders programme. The dataset and task brief were supplied. The cleaning, formulas, charts and written message are my own work.

## The brief

Greenfield Secondary School has 240 students in 6 classes (JSS1A to JSS3B), with results for three terms in one file. The principal wanted to know:

1. Which class is doing best, and which needs the most help?
2. Which subject is hardest?
3. Are students improving from First Term to Third Term?
4. Which students need extra support?

## What I did

**Cleaning (Power Query)**

The raw data had inconsistent class names and gender entries, messy student names, scores stored as text, scores above 100 (an extra zero typed), blank scores and duplicate rows. After cleaning, the data had 720 rows, 240 students and 6 classes. Blank scores were kept blank, as the school's rules require, and duplicates were removed only after the data was cleaned.

**Analysis (Excel formulas)**
- Total, Average and Grade per row (`SUM`, `AVERAGE`, `IFS`)
- Class rank within each term (`SUMPRODUCT`), plus the Third Term top 10 and top 3 per class
- Class summary by term: students, average score, pass rate (`COUNTIFS`, `AVERAGEIFS`)
- Subject averages overall and by term
- An at-risk list of Third Term averages below 50, highlighted with conditional formatting
- A Summary sheet with four key numbers and three charts

## Key findings

- **Best class (Third Term):** JSS3B, average 66.7 and a 90% pass rate. It also improved the most (+6.1 points).
- **Class needing most help:** JSS3A, with the lowest Third Term average (62.7), the lowest pass rate (80%) and the most at-risk students (8).
- **Hardest subject:** Maths, lowest in every term (55.4 across all terms, against 67.3 for Civic Education).
- **Students needing support:** 32 students had a Third Term average below 50, and 8 of them were below 40.
- **Overall Third Term pass rate:** 86.7%.

## What I would want to know next

- Before deciding where to put extra resources, I would like to know whether Maths scores are low because students are struggling with the subject or because the Maths papers are marked harder than the other subjects, since this data only shows scores and not how difficult each paper was																												
- I would like to know why 12 scores are blank, and whether those students were absent or simply not entered, before we judge their averages																												
## Skills practised

Data cleaning in Power Query · Excel formulas (`SUMIFS`, `COUNTIFS`, `AVERAGEIFS`, `IFS`, `SUMPRODUCT`, `INDEX`/`MATCH`, `RANK`) · conditional formatting · charts · summarising findings for a non-technical reader

## Limitations

- The data only contains scores. It cannot explain why a subject is low (for example, harder content versus harder marking).
- Twelve scores were blank. I kept them blank, so those students' averages are based on fewer subjects.

## File contains

(Raw data,Results, Clean Data, Rankings, Class Summary, Subjects, Improvement, At Risk, Summary, Bonus questions)
