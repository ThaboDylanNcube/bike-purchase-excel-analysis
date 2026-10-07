# Bike Purchase Analysis (Excel)

An Excel portfolio project exploring which customer segments are more likely to purchase a bike. The cleaned dataset contains **1,000 unique buyers**.

## Key Findings
- **48.1%** of buyers purchased a bike (481 of 1,000).
- Buyers with a **0–1 mile** commute had the highest purchase rate at **54.6%** (200 of 366).  
  Buyers with a commute **over 10 miles** had the lowest rate at **29.7%** (33 of 111).
- Average income of buyers who purchased: **57,963** vs **54,875** for those who did not.  
  (Currency is not specified in the source data.)

These are descriptive comparisons only — they do not prove causation.

## What I Did
- Removed 26 duplicate buyer IDs → 1,000 unique records.
- Standardized category labels and created age groups with Excel formulas.
- Built interactive analysis using PivotTables, charts and slicers.

## Workbook Structure
| Sheet | Contents |
|-------|----------|
| `Dashboard` | Interactive dashboard with slicers (open in desktop Excel) |
| `Worksheet` | Cleaned records |
| `Pivot Table` | Summary tables |
| `bike_buyers` | Original source data |

## Tools
Microsoft Excel (data cleaning, formulas, PivotTables, charts, slicers)

## How to Use
1. Download the `.xlsx` file.
2. Open in **desktop Excel** (slicers work best there).
3. Go to the `Dashboard` sheet and use the slicers to explore.
