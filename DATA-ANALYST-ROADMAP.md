# 📊 Data Analyst Roadmap — Beginner to Job-Ready

Welcome! This repository is my learning guide for anyone who wants to develop practical Data Analytics skills, build projects, and prepare for Data Analyst opportunities.

The roadmap brings together technical skills, learning resources, practice platforms, business thinking, and career preparation. It is designed for self-learners who want to progress step by step, using free resources wherever possible.

**My approach:** Learn a concept → Practice it → Apply it to a business problem → Document the result → Improve.

> This is a learning roadmap, not a guarantee of employment. Progress depends on consistent practice, project quality, and the requirements of each role.

## 📌 Table of Contents

1. [What Does a Data Analyst Do?](#-what-does-a-data-analyst-do)
2. [The Complete Learning Path](#-the-complete-learning-path)
3. [Statistics and Analytical Thinking](#1-statistics-and-analytical-thinking)
4. [Microsoft Excel](#2-microsoft-excel)
5. [SQL and Databases](#3-sql-and-databases)
6. [Business Intelligence: Power BI and Tableau](#4-business-intelligence-power-bi-and-tableau)
7. [Python for Data Analysis](#5-python-for-data-analysis)
8. [Soft Skills and Business Understanding](#6-soft-skills-and-business-understanding)
9. [Portfolio Projects](#7-portfolio-projects)
10. [Resume and Interview Preparation](#8-resume-and-interview-preparation)
11. [Free Practice Platforms and Communities](#-free-practice-platforms-and-communities)
12. [Suggested 90-Day Study Plan](#-suggested-90-day-study-plan)
13. [Progress Checklist](#-progress-checklist)
14. [Useful Career Resources](#-useful-career-resources)
15. [Contributing](#-contributing)

---

## 🎯 What Does a Data Analyst Do?

A Data Analyst helps people make better decisions by turning raw data into useful information.

Typical responsibilities include:

- Understanding business requirements and defining measurable questions.
- Collecting data from spreadsheets, databases, and other sources.
- Checking data quality and correcting errors.
- Exploring patterns, trends, and unusual results.
- Calculating metrics and comparing performance.
- Creating reports, dashboards, and visualizations.
- Communicating findings and recommending next steps.

### The data analysis workflow

**Business question → Data collection → Data validation → Data cleaning → Analysis → Visualization → Business recommendation**

For example, a business might ask:

*"Why did monthly sales decrease compared with the previous month?"*

An analyst could investigate sales by product, location, sales channel, and month; validate the data; identify the largest changes; and present evidence-based recommendations.

---

## 🗺️ The Complete Learning Path

| Stage | Focus                | What you should be able to do                                  |
| ----- | -------------------- | -------------------------------------------------------------- |
| 1     | Statistics           | Interpret averages, percentages, distributions, and variation  |
| 2     | Excel                | Clean, calculate, summarize, and visualize spreadsheet data    |
| 3     | SQL                  | Retrieve, combine, and analyze data from databases             |
| 4     | Power BI             | Build interactive dashboards and calculate business metrics    |
| 5     | Tableau              | Create visual analyses and share dashboards                    |
| 6     | Python               | Clean, explore, analyze, and visualize datasets                |
| 7     | Business skills      | Translate findings into clear recommendations                  |
| 8     | Portfolio and career | Demonstrate skills through projects and prepare for interviews |

**Suggested priority for beginners:** Excel → SQL → Power BI → statistics alongside practice → Python. Learn Tableau as an additional visualization tool or when a target job requires it.

You do not need to master every tool before starting projects.

---

## 1. Statistics and Analytical Thinking

Statistics helps you distinguish meaningful patterns from random variation and explain what the data actually shows.

### Topics to learn

- Mean, median, mode, minimum, maximum, range, and percentiles.
- Percentages, percentage change, ratios, and growth rates.
- Variance and standard deviation.
- Frequency distributions and outliers.
- Basic probability and common probability distributions.
- Sampling and sampling bias.
- Correlation versus causation.
- Confidence intervals and hypothesis-testing fundamentals.
- Descriptive statistics and introductory inferential statistics.
- Choosing appropriate metrics and interpreting uncertainty.

### Free learning resources

- [Khan Academy — Statistics and Probability](https://www.khanacademy.org/math/statistics-probability)
- [OpenStax — Introductory Statistics](https://openstax.org/details/books/introductory-statistics)
- [StatQuest — Statistics and related tutorials](https://statquest.org/)
- [Seeing Theory — Interactive statistics and probability](https://seeing-theory.brown.edu/)

### Practice ideas

- Compare average order values across product categories.
- Calculate month-over-month sales growth.
- Identify unusual transaction values.
- Compare median and mean salary in a sample dataset.
- Explain why correlation does not automatically prove causation.

**Deliverable:** A short statistical analysis with calculations, charts, and plain-English explanations.

---

## 2. Microsoft Excel

Excel is an important tool for organizing, cleaning, calculating, and summarizing business data.

### Beginner skills

- Workbook, worksheet, rows, columns, tables, and cell references.
- Sorting, filtering, and Excel Tables.
- Relative, absolute, and mixed references.
- Basic arithmetic and aggregation formulas.
- Number, date, currency, and percentage formats.
- Data validation and drop-down lists.

### Formulas and functions

**Basic calculations**

- `SUM`, `AVERAGE`, `MIN`, `MAX`, `COUNT`, `COUNTA`

**Conditional calculations**

- `IF`, `IFS`, `SUMIF`, `SUMIFS`, `COUNTIF`, `COUNTIFS`

**Lookups**

- `XLOOKUP`, `VLOOKUP`, `INDEX`, `MATCH`

**Text cleaning**

- `TRIM`, `CLEAN`, `LEFT`, `RIGHT`, `MID`, `SUBSTITUTE`, `TEXTSPLIT`

**Date and error handling**

- `DATE`, `YEAR`, `MONTH`, `TODAY`, `IFERROR`

**Dynamic arrays, where supported**

- `FILTER`, `SORT`, `UNIQUE`

### Intermediate and advanced skills

- Conditional formatting and duplicate identification.
- PivotTables and PivotCharts.
- Slicers and report filters.
- Data cleaning and consistency checks.
- Power Query for repeatable transformations.
- Combining files and appending or merging tables.
- Basic dashboard design and KPI reporting.
- Introduction to VBA or Office Scripts when automation is useful.

### Free learning resources

- [Microsoft Excel Help and Learning](https://support.microsoft.com/en-us/excel)
- [Excel — Microsoft Learn](https://learn.microsoft.com/en-us/training/browse/?products=excel)
- [ExcelJet — Formula explanations](https://exceljet.net/)
- [GCFGlobal — Excel tutorials](https://edu.gcfglobal.org/en/excel/)
- [Excel practice datasets — Kaggle](https://www.kaggle.com/datasets)

### Practice ideas

1. Clean customer names, dates, and inconsistent categories.
2. Find duplicates and investigate missing values.
3. Create a monthly sales summary using a PivotTable.
4. Build an employee or sales performance dashboard.
5. Use Power Query to repeat the same cleaning process on updated data.

**Deliverable:** An Excel workbook containing raw data, cleaned data, formulas, a summary report, and a dashboard.

---

## 3. SQL and Databases

SQL is used to retrieve and analyze data stored in relational databases. It is one of the most valuable skills for Data Analyst roles.

### Fundamentals

- Databases, tables, records, and columns.
- Primary keys and foreign keys.
- `SELECT`, `FROM`, `WHERE`, `ORDER BY`, `DISTINCT`.
- `LIMIT` or the equivalent in your database system.
- Comparison operators, `AND`, `OR`, `IN`, `BETWEEN`, and `LIKE`.
- Handling `NULL` values.

### Intermediate SQL

- Aggregate functions: `COUNT`, `SUM`, `AVG`, `MIN`, `MAX`.
- `GROUP BY` and `HAVING`.
- `INNER JOIN`, `LEFT JOIN`, and other join types.
- `CASE WHEN` for conditional logic.
- Subqueries and Common Table Expressions (CTEs).
- Date and string functions.
- Duplicate detection and data-quality checks.
- Set operations such as `UNION`.

### Advanced SQL for analytics

- Window functions: `ROW_NUMBER`, `RANK`, `LAG`, `LEAD`.
- Running totals and rolling calculations.
- Common ranking and cohort-analysis patterns.
- Query execution plans and basic performance awareness.
- Views and reusable queries.
- Transactions and database design fundamentals.

### Free courses and tutorials

- [SQLBolt — Interactive SQL lessons](https://sqlbolt.com/)
- [SQLZoo — SQL tutorials and exercises](https://sqlzoo.net/wiki/SQL_Tutorial)
- [Khan Academy — Intro to SQL](https://www.khanacademy.org/computing/computer-programming/sql)
- [PostgreSQL — Official documentation](https://www.postgresql.org/docs/)
- [W3Schools — SQL tutorial](https://www.w3schools.com/sql/)
- [Kaggle — Intro to SQL](https://www.kaggle.com/learn/intro-to-sql)
- [HackerRank — SQL practice](https://www.hackerrank.com/domains/sql)
- [LeetCode — Database problems](https://leetcode.com/problemset/database/)
- [8 Week SQL Challenge](https://8weeksqlchallenge.com/)

### Practice ideas

- Find the top five products by revenue.
- Calculate monthly sales and growth.
- Identify customers who have never placed an order.
- Rank employees by performance within each department.
- Calculate repeat-customer rates.
- Investigate missing records and duplicate transactions.

**Deliverable:** A folder of SQL scripts, business questions, query results, and explanations of your findings.

---

## 4. Business Intelligence: Power BI and Tableau

Business Intelligence tools transform prepared data into visual reports that help stakeholders monitor performance and make decisions.

### A. Microsoft Power BI

#### Topics to learn

- Power BI Desktop interface.
- Importing Excel, CSV, database, and other supported sources.
- Power Query Editor and data transformation.
- Relationships, cardinality, and data models.
- Star-schema fundamentals.
- Measures versus calculated columns.
- DAX fundamentals: `SUM`, `COUNTROWS`, `DISTINCTCOUNT`, `CALCULATE`, and filter context.
- KPI cards, bar charts, line charts, tables, maps where appropriate, and other visualizations.
- Slicers, filters, drill-through, and report navigation.
- Date tables and time-based analysis.
- Dashboard usability, accessibility, and performance basics.
- Publishing and sharing reports, subject to licensing and organizational access.

#### Free resources

- [Microsoft Learn — Power BI](https://learn.microsoft.com/en-us/training/powerplatform/power-bi/)
- [Power BI documentation](https://learn.microsoft.com/en-us/power-bi/)
- [Power BI Community](https://community.fabric.microsoft.com/)
- [Guy in a Cube — Tutorials](https://www.youtube.com/@GuyInACube)
- [SQLBI — DAX and data modeling](https://www.sqlbi.com/)
- [Enterprise DNA — Power BI learning content](https://www.youtube.com/@EnterpriseDNA)

#### Project ideas

- Monthly sales performance dashboard.
- Employee headcount and attrition analysis.
- Customer retention dashboard.
- Training attendance and completion report.
- Budget versus actual expenditure dashboard.

### B. Tableau

#### Topics to learn

- Connecting to files and data sources.
- Dimensions, measures, and data types.
- Basic charts and visual encodings.
- Filters, sorting, groups, and sets.
- Calculated fields and parameters.
- Dashboard layout and interactivity.
- Storytelling with visualizations.
- Publishing work using Tableau Public.

#### Free resources

- [Tableau Free Training Videos](https://www.tableau.com/learn/training)
- [Tableau Public](https://public.tableau.com/)
- [Tableau Community Forums](https://community.tableau.com/)
- [Tableau Help](https://help.tableau.com/)

**Deliverable:** At least one well-documented interactive dashboard. Start with either Power BI or Tableau; learn the second tool when your goals require it.

---

## 5. Python for Data Analysis

Python is useful for automating repetitive tasks, working with larger datasets, performing exploratory analysis, and creating reproducible workflows.

### Python fundamentals

- Variables and data types.
- Lists, tuples, sets, and dictionaries.
- Conditions and loops.
- Functions and modules.
- File handling and exceptions.
- Basic programming and debugging.
- Jupyter notebooks or another Python development environment.

### Important data libraries

- **Pandas:** Load, clean, transform, join, group, and summarize data.
- **NumPy:** Numerical operations and arrays.
- **Matplotlib:** Create charts.
- **Seaborn:** Statistical visualizations.
- **Jupyter:** Document analysis in notebooks.

### Learning resources

- [Python official tutorial](https://docs.python.org/3/tutorial/)
- [Python for Everybody](https://www.py4e.com/)
- [Kaggle — Learn Python](https://www.kaggle.com/learn/python)
- [Kaggle — Pandas](https://www.kaggle.com/learn/pandas)
- [Pandas getting started](https://pandas.pydata.org/docs/getting_started/)
- [NumPy quickstart](https://numpy.org/doc/stable/user/quickstart.html)
- [Matplotlib tutorials](https://matplotlib.org/stable/tutorials/)
- [Google Colab](https://colab.research.google.com/)

### Practice ideas

- Load and clean a CSV dataset.
- Investigate missing values and duplicates.
- Group sales by product and month.
- Combine customer and order datasets.
- Create charts showing trends and outliers.
- Automate a repetitive reporting task.

**Deliverable:** A Jupyter notebook with documented cleaning steps, analysis, visualizations, and conclusions.

---

## 6. Soft Skills and Business Understanding

Technical skills alone are not enough. Analysts must understand the business question and explain their findings to people who may not use analytical tools themselves.

### Skills to develop

**Analytical thinking**

- Break large questions into smaller, testable questions.
- Check assumptions and validate results.
- Distinguish facts from interpretations.

**Communication**

- Explain technical results in simple language.
- Write clear report summaries.
- Adapt the explanation to the audience.

**Problem-solving**

- Investigate the cause of a change rather than merely reporting it.
- Compare alternative explanations.
- Recommend actions supported by evidence.

**Teamwork**

- Clarify requirements with stakeholders.
- Document definitions and assumptions.
- Work with business, operations, finance, and technical teams.

**Business understanding**

- Understand KPIs, targets, costs, revenue, productivity, quality, and customer outcomes.
- Ask why a metric matters and what decision it supports.
- Understand the difference between a metric, a target, and an action.

**Data storytelling**

- State the business question.
- Show the most relevant evidence.
- Explain what changed and why it matters.
- Finish with a practical recommendation and its limitations.

### Practice exercise

For every project, answer these five questions:

1. What business problem am I solving?
2. Which data do I need?
3. What checks did I perform before analysis?
4. What are the most important findings?
5. What should the business consider doing next?

---

## 7. Portfolio Projects

A portfolio should demonstrate that you can apply your skills—not simply that you have completed tutorials.

### Suggested projects

| Project                        | Tools                | Questions to answer                                  |
| ------------------------------ | -------------------- | ---------------------------------------------------- |
| Sales performance analysis     | Excel, Power Query   | Which products and regions drive revenue?            |
| Customer order analysis        | SQL                  | Which customers return, and what do they purchase?   |
| Employee performance dashboard | Excel or Power BI    | How do headcount, attendance, or performance change? |
| Customer churn analysis        | SQL, Power BI        | Which customer groups show higher churn?             |
| Retail exploratory analysis    | Python, Pandas       | What patterns and anomalies appear in the data?      |
| End-to-end business case       | Excel, SQL, Power BI | What decision can the combined analysis support?     |

Use public datasets or synthetic data. Do not publish confidential company data, personal information, or employer-owned files without authorization.

### Recommended structure for each project

```text
project-name/
├── README.md
├── data/
│   ├── raw-data.csv
│   └── cleaned-data.csv
├── analysis/
│   └── analysis.sql
├── visuals/
│   └── dashboard-preview.png
└── findings.md
```

Include the problem statement, dataset source, cleaning rules, methods, findings, limitations, and business recommendations. Do not upload passwords, access tokens, or sensitive data.

### Free dataset sources

- [Kaggle Datasets](https://www.kaggle.com/datasets)
- [UCI Machine Learning Repository](https://archive.ics.uci.edu/)
- [Data.gov](https://data.gov/)
- [World Bank Open Data](https://data.worldbank.org/)
- [Google Dataset Search](https://datasetsearch.research.google.com/)

Check the terms of use and licenses before redistributing any dataset.

---

## 8. Resume and Interview Preparation

### Resume checklist

- Use a clear, readable layout.
- Include relevant tools and skills you can demonstrate.
- Highlight projects with specific questions, methods, and results.
- Explain your own contribution accurately.
- Include relevant work experience, education, and certifications.
- Tailor your resume to the job description.
- Use measurable achievements only when you can support them.
- Check spelling, formatting, dates, and links.

### Free resume resources

- [Canva Resume Templates](https://www.canva.com/resumes/templates/)
- [Microsoft Create — Resume templates](https://create.microsoft.com/en-us/templates/resumes)
- [Google Docs templates](https://docs.google.com/document/u/0/)

Template availability and account requirements may vary.

### Technical interview preparation

**Excel**

- Explain lookup functions and conditional formulas.
- Clean a dataset with inconsistent values.
- Summarize data using a PivotTable.

**SQL**

- Write joins and aggregation queries.
- Use CTEs and window functions.
- Solve a business question using multiple tables.

**Power BI / Tableau**

- Explain data modeling and visual selection.
- Describe a dashboard you built.
- Explain how you validated metrics.

**Statistics**

- Interpret mean, median, variation, and correlation.
- Explain percentage change and sampling limitations.

**Python**

- Clean a dataset using Pandas.
- Group and summarize data.
- Explain a visualization and its conclusions.

### Behavioral and case-study preparation

- Practice explaining a project from start to finish.
- Describe how you handled a data-quality issue.
- Explain how you resolved conflicting requirements.
- Use the STAR method for relevant experience-based questions.
- Practice mock interviews and explain your reasoning aloud.

### Job-search resources

- [LinkedIn Jobs](https://www.linkedin.com/jobs/)
- [Naukri](https://www.naukri.com/)
- [Indeed India](https://in.indeed.com/)
- [Glassdoor](https://www.glassdoor.co.in/)
- [Wellfound](https://wellfound.com/jobs)

Verify job descriptions, company details, and application requirements before applying.

---

## 🌐 Free Practice Platforms and Communities

| Platform                                              | Best use                                              |
| ----------------------------------------------------- | ----------------------------------------------------- |
| [Kaggle](https://www.kaggle.com/)                     | Datasets, notebooks, Python, and SQL learning         |
| [HackerRank](https://www.hackerrank.com/)             | SQL and programming exercises                         |
| [LeetCode](https://leetcode.com/problemset/database/) | SQL problem-solving practice                          |
| [SQLZoo](https://sqlzoo.net/wiki/SQL_Tutorial)        | Interactive SQL lessons                               |
| [SQLBolt](https://sqlbolt.com/)                       | SQL fundamentals                                      |
| [GitHub](https://github.com/)                         | Version control, documentation, and portfolio hosting |
| [Microsoft Learn](https://learn.microsoft.com/)       | Official Microsoft learning paths                     |
| [Tableau Public](https://public.tableau.com/)         | Explore and publish Tableau visualizations            |

Some platforms offer optional paid features. Start with their freely accessible learning materials.

---

## 📅 Suggested 90-Day Study Plan

This is a flexible plan, not a deadline for mastering every skill. Adjust the pace based on your schedule and prior experience.

| Period     | Focus                                     | Suggested output                                |
| ---------- | ----------------------------------------- | ----------------------------------------------- |
| Days 1–15  | Excel formulas and data quality           | Cleaned dataset and formula exercises           |
| Days 16–25 | Advanced Excel, PivotTables, Power Query  | Summary report and repeatable cleaning workflow |
| Days 26–40 | SQL fundamentals and joins                | Collection of query exercises                   |
| Days 41–50 | Advanced SQL and business questions       | SQL case study                                  |
| Days 51–65 | Power BI and data modeling                | Interactive dashboard                           |
| Days 66–75 | Statistics and analytical reasoning       | Written analysis with charts                    |
| Days 76–83 | Python and Pandas fundamentals            | Exploratory analysis notebook                   |
| Days 84–90 | Portfolio, resume, and interview practice | Documented end-to-end project                   |

Tableau can be studied alongside Power BI or after the first dashboard. If you are starting from zero, prioritize solid fundamentals over rushing through every topic.

---

## ✅ Progress Checklist

Track your progress as you learn.

### Foundations

- [ ] I can translate a business question into measurable questions.
- [ ] I can calculate and explain common statistical measures.
- [ ] I can validate the quality of a dataset.

### Excel

- [ ] I can use common formulas and lookup functions.
- [ ] I can clean inconsistent data.
- [ ] I can build PivotTables and a dashboard.
- [ ] I can use Power Query for repeatable transformations.

### SQL

- [ ] I can filter, sort, and aggregate data.
- [ ] I can join related tables.
- [ ] I can use CTEs and window functions.
- [ ] I can answer business questions with SQL.

### Visualization

- [ ] I can prepare a useful data model.
- [ ] I can create an interactive Power BI or Tableau report.
- [ ] I can explain the KPIs and findings in plain English.

### Python

- [ ] I can load and clean a dataset with Pandas.
- [ ] I can summarize and visualize data.
- [ ] I can document my analytical workflow.

### Career readiness

- [ ] I have at least two documented projects.
- [ ] My GitHub README files explain the purpose and findings.
- [ ] My resume links to relevant projects.
- [ ] I have practiced technical and behavioral interview questions.

---

## 💼 Useful Career Resources

- [Microsoft Learn](https://learn.microsoft.com/) — Official Microsoft learning paths.
- [GitHub Skills](https://skills.github.com/) — Learn GitHub workflows and collaboration.
- [LinkedIn Learning](https://www.linkedin.com/learning/) — Courses; access may require payment or an eligible subscription.
- [freeCodeCamp](https://www.freecodecamp.org/) — Free programming and data-related learning content.
- [Kaggle Learn](https://www.kaggle.com/learn) — Short practical courses.
- [DataCamp](https://www.datacamp.com/) — Interactive learning; free access is limited for some content.

Check current course availability, prerequisites, and licensing before choosing a resource.

---

## 🤝 Contributing

This roadmap is intended to improve over time.

You can contribute by:

- Suggesting useful free learning resources.
- Reporting broken links or outdated instructions.
- Sharing project ideas and practice datasets.
- Improving explanations for beginners.
- Opening an issue or submitting a pull request with proposed changes.

Please credit original creators when referencing their work, respect dataset licenses, and avoid copying other repositories wholesale.

## 👋 About This Repository

This roadmap is part of my Data Analytics learning journey. I am documenting concepts, practice exercises, projects, and lessons learned as I build practical skills.

My goal is to make the learning process clearer for beginners while building a portfolio that demonstrates what I can do with data.

**Learn → Practice → Build → Document → Share → Improve**

If you find this guide helpful, consider starring the repository and following along as it grows.

*Learning resources and platform features can change. Please check each linked website for current availability and terms.*
