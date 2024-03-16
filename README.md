# FinancialYear
It calculate financial year related issue
<!-- doc updater -->

### update doc
----------------------------------------
<h3> Major Update in function name and stable version <h3>

### To update
```bash
    pip install --upgrade financialyear
```

- Input may be in 2022 or 2022-23 in 
- It Returns the start date and end date of a month for a given financial year and month.
________________________________________________________________________________________________________________
-    also set financial_month_start_month

-    year = "2023-24" and month as int (e.g., 4 for April)

-    month_start_date returns a date like "01-04-2023"

-    month_end_date returns a date like "30-04-2023"

-    month_list returns all months of the financial year from "04-2023" to "03-2024"

 # Example usage:

- financial_year = Finyear("2023-24")

-    print(financial_year.month_start_date(1))  # Output: 01-04-2023

-    print(financial_year.month_end_date(1))    # Output: 30-04-

-    print(financial_year.previous_month_dates(month=1))

-    print(financial_year.month_list())    # Output: ['04-2023', '05-2023', '06-2023', ..., '03-2024']
