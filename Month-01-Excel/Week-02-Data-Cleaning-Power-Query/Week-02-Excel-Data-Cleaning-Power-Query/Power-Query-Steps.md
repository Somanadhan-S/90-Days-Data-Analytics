# Power Query — Beginner Workflow

Power Query imports and transforms data through recorded steps that can be refreshed. Menu names may vary by Excel version.

## Start
1. Open Excel.
2. Choose **Data → Get Data → From File → From Text/CSV**.
3. Select `data/raw_customer_orders.csv`.
4. Choose **Transform Data**.

## Recommended steps
1. Confirm the first row is used as headers.
2. Review data types: IDs and descriptive fields should usually be text; dates should be Date; Quantity should be Whole Number; Unit_Price should be Decimal/Currency.
3. Select text columns and use **Transform → Format → Trim**. Use Clean where appropriate.
4. Standardize text values and verify them against allowed categories/statuses.
5. Filter to inspect blanks and errors before deciding what to do.
6. Handle inconsistent dates carefully; use **Change Type → Using Locale** if needed.
7. Check duplicates. Select `Order_ID` and remove duplicates only if the business rule confirms it should be unique.
8. Convert Quantity and Unit_Price; inspect conversion errors.
9. Rename steps clearly, e.g. `Trim Text`, `Standardize Status`, `Check Order ID`.
10. Choose **Home → Close & Load**.

## Validate
- Compare row counts before and after cleaning.
- Confirm removed rows were true duplicates.
- Count remaining blanks and errors.
- Keep the raw file unchanged.
- Record assumptions and decisions.

Power Query repeats the steps you choose; it does not decide the business rule for you. Validate output before using it in a report.
