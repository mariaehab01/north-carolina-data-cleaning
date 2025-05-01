# North Carolina Data Cleaning Project

This project demonstrates how to clean, transform, and merge two real-world Excel datasets using Power Query in Excel. The datasets include county-level household income and racial demographics in North Carolina.

## Datasets

- **North Carolina Household Income by County**
- **North Carolina Race by County**

## Key Transformations

- Split columns (e.g., County/Population ➝ County + Population)
- Renamed and reordered columns
- Removed redundant or irrelevant columns
- Added custom calculated columns:
  - `% Black` (from total population)
  - `% Asian`
- Merged both tables using the common `County` column
- Adjusted data types and structure for analysis-ready format

## Tools Used

- Excel Power Query
- Excel Functions (basic)
- Merge & Transform Queries

## Output

The final cleaned and merged dataset is available in the `Output/` folder.

