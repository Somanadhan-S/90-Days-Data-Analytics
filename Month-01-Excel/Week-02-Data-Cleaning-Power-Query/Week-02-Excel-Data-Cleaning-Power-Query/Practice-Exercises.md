# Week 02 Practice Exercises

Use `data/raw_customer_orders.csv`. Try the tasks before comparing with the cleaned file.

## Level 1 — Inspect
1. Count the total rows.
2. Identify columns with blanks.
3. Find repeated `Order_ID` values.
4. Find inconsistent capitalization in City and Order_Status.
5. Identify dates that may not convert.

## Level 2 — Clean in Excel
6. Remove leading and trailing spaces.
7. Standardize City, Category, and Order_Status values.
8. Check whether Quantity contains non-numeric values.
9. Check whether Unit_Price contains non-numeric values.
10. Standardize valid dates to one format.
11. Flag missing Email values.
12. Create a duplicate check for Order_ID.

## Level 3 — Power Query
13. Import the raw CSV using Data → From Text/CSV.
14. Check and set each column's data type.
15. Use Trim and Clean where appropriate.
16. Standardize text values.
17. Inspect blanks and errors before deciding how to handle them.
18. Remove duplicate Order_ID values only if the business rule confirms they should be unique.
19. Load the result to a new worksheet named `Cleaned_Data`.
20. Refresh the query after changing a source value.

## Business questions
21. How many orders remain after cleaning?
22. Which city has the most orders?
23. How many orders are Delivered, Shipped, Pending, Returned, or Cancelled?
24. Which data quality issue would you fix first, and why?
25. What assumptions did you make? Document them.

## Reflection
- Which steps were easy?
- Which issue required a business decision rather than a formula?
- Which steps would you want to repeat automatically every week?
