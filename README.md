# Driver Pay Calculator

A formula-driven Excel workbook that estimates daily and weekly gross pay from mileage and paid-hour inputs.

![Driver Pay Calculator preview](driver-pay-calculator-preview.png)

## Problem

Driver compensation can include several categories, such as standard mileage, LCV mileage, delay time, and task time. Recalculating each category manually makes it harder to quickly estimate weekly earnings or notice when a result does not look right.

## Solution

This workbook provides one reusable place to enter daily work activity and pay rates. Excel formulas calculate each day's estimated gross pay and summarize the week automatically.

## Features

- Seven-day mileage and paid-hour entry table
- Separate rate inputs for standard miles, LCV miles, delay hours, and task hours
- Automatic daily gross-pay calculations
- Weekly totals for pay, mileage, and paid hours
- Color-coded input and formula cells
- Instructions and documentation sheet
- Employer-neutral fictional sample data for safe public sharing

## Formula

```text
Daily gross pay =
(Standard miles × standard mileage rate)
+ (LCV miles × LCV mileage rate)
+ (Delay hours × delay hourly rate)
+ (Task hours × task hourly rate)
```

## Skills Demonstrated

- Excel formulas
- Absolute and relative cell references
- Input-model design
- Summary metrics
- Spreadsheet formatting
- User-focused documentation
- Translating a real operational problem into a practical tool

## Files

- `driver-pay-calculator-portfolio.xlsx` — public portfolio workbook
- `driver-pay-calculator-preview.png` — workbook preview image

## Portfolio Note

This repository uses fictional sample rates and sample work entries. It does not contain official employer payroll information or personal trip records. The workbook provides estimates only and is not an official payroll, tax, or benefits calculation.

## Potential Improvements

- Add overtime rules when applicable
- Add multiple saved weeks
- Add pay-period summaries
- Add printable reports
- Add input validation and error messages

---

Created by Zachary Maness.
