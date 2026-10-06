# Week 01 — Excel + Data Analytics Resource

Part of my **90-Day Data Analytics Learning Journey**.

This folder is designed for both technical and non-technical learners. You do **not** need a coding background.

## 🎯 What you will learn

Excel can help you:
- clean data
- connect tables
- calculate KPIs
- apply business rules
- check data quality
- summarize information
- create dynamic analysis
- answer business questions

**Raw Data → Clean Data → Calculate → Analyze → Business Answer**

## 📂 Workbook

Open `Week-01-Excel-Data-Analyst-Formula-Guide.xlsx`.

Start with `START_HERE`, then follow sheets 01 → 10.

### Formula groups

1. Basic Math — SUM, AVERAGE, MIN, MAX, COUNT, COUNTA, COUNTBLANK, ROUND
2. Logical — IF, IFS, AND, OR, IFERROR, IFNA
3. Lookups — XLOOKUP, VLOOKUP, INDEX, MATCH, INDEX+MATCH, XMATCH
4. Criteria/Aggregation — SUMIF, SUMIFS, COUNTIF, COUNTIFS, AVERAGEIF, AVERAGEIFS, MAXIFS, MINIFS
5. Text — LEFT, RIGHT, MID, LEN, TRIM, UPPER, LOWER, PROPER, CONCAT, TEXTJOIN, SUBSTITUTE, FIND, SEARCH
6. Date/Time — TODAY, NOW, YEAR, MONTH, DAY, EOMONTH, DATEDIF, NETWORKDAYS, WEEKDAY
7. Data Quality — duplicate checks, blanks, ISBLANK, ISNUMBER, ISTEXT, ISERROR, ISNA
8. Dynamic Arrays — FILTER, UNIQUE, SORT, SORTBY
9. Analysis — SUBTOTAL, AGGREGATE, RANK.EQ, PERCENTILE.INC, MEDIAN, STDEV.S, CORREL
10. Practice — business questions to solve yourself

## 🌍 Real-world examples

**Employee MIS**
- Find department from Employee ID → XLOOKUP
- Count active employees → COUNTIFS
- Check target achievement → IF
- Detect duplicate IDs → COUNTIF
- Calculate average performance → AVERAGE

**Sales Analysis**
- Total Sales for Chennai → SUMIFS
- Number of orders for a product → COUNTIFS
- Highest sales → MAX
- Rank salespeople → RANK.EQ

**Data Quality**
- Missing values → COUNTBLANK / ISBLANK
- Duplicate IDs → COUNTIF
- Formula errors → IFERROR / ISERROR
- Numeric validation → ISNUMBER

## 🧠 For non-coding learners

Do not try to memorize every formula.

For every formula ask:

1. What problem does it solve?
2. What data do I need?
3. What business question can it answer?
4. Can I change the data and predict the result?

Example:

**Business question:** How many active employees are in Sales?

Think:

**Count + Sales + Active → COUNTIFS()**

This is the mindset of Data Analytics.

## 🚀 Mini Project

Build an **Employee Operations MIS Report** with:

- Employee Master
- Attendance
- Performance
- Data Quality
- Lookup Practice
- MIS Summary

Answer:

1. How many employees are active?
2. How many are in each department?
3. What is average performance?
4. Who achieved the target?
5. Which department has the highest actual?
6. Are there duplicate IDs?
7. Are there missing values?
8. Are all statuses valid?

## 📚 Official Excel Reference

Microsoft Excel Functions:
https://support.microsoft.com/en-us/excel/excel-functions-by-category

## ⚠️ Version note

XLOOKUP, FILTER, UNIQUE and some other newer functions require newer Excel versions. If you use Excel 2016, practice compatible alternatives such as VLOOKUP and INDEX + MATCH.

## 🔗 Learning approach

**Learn → Practice → Build → Apply → Share**

This repository will grow throughout my 90-Day Data Analytics Journey.
