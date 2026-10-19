# Week 02 — Excel Data Cleaning & Power Query

Welcome to Week 02 of my 90-Day Data Analytics Learning Journey.

This beginner-friendly practice lab covers cleaning messy data, checking data quality, and learning repeatable transformation steps with Excel and Power Query.

## Learning goals
- Identify duplicate records and missing values.
- Standardize names, cities, categories, and statuses.
- Check date, quantity, and price data types.
- Keep raw data unchanged and document cleaning decisions.
- Learn how Power Query records repeatable steps.
- Prepare a clean table for analysis.

## Files
- `data/raw_customer_orders.csv` — deliberately messy synthetic data.
- `data/cleaned_customer_orders.csv` — an example cleaned result.
- `Practice-Exercises.md` — tasks to complete.
- `Power-Query-Steps.md` — guided workflow.
- `Resources.md` — free learning and practice links.

## How to practise
1. Open the raw CSV in Excel.
2. Save a working copy before changing anything.
3. Try the exercises before opening the cleaned file.
4. Use Excel tools or Power Query; you do not need both.
5. Compare your output with the sample cleaned file.
6. Document any different decisions you made.

## Issues included
- Extra spaces and inconsistent capitalization.
- Duplicate order records.
- Missing quantity and email.
- Non-numeric quantity (`two`) and price (`N/A`).
- Inconsistent date formats and one invalid date.
- Different capitalization in order statuses.

## Sample cleaning rules
- Trim extra spaces.
- Standardize capitalization in text fields.
- Convert recognizable dates to `YYYY-MM-DD`.
- Leave invalid dates blank rather than guessing.
- Convert quantity to a whole number and price to a decimal; leave invalid values blank.
- Lowercase email addresses and preserve missing email as blank.
- Remove duplicate `Order_ID` values by keeping the first occurrence in this example.

These are practice rules, not universal business rules. In real work, confirm whether repeated IDs are true duplicates and how missing values should be handled. Never delete records without checking what the ID means.

## Mini project
Create a Data Quality Report with:
- Total raw rows and rows after deduplication.
- Missing emails.
- Invalid dates.
- Invalid quantities.
- Invalid prices.
- A short note explaining each cleaning decision.

**Workflow:** Raw Data → Profile → Clean & Standardize → Validate → Document → Analysis-Ready Data

Power Query features can vary by Excel version.
