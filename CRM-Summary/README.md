# CRM-Summary Challenge

Challenge Link: https://lnkd.in/g67DDyjV

The problem was to create a summary report of deal counts by sales stage from CRM data, where each deal appears on multiple rows due to the inclusion of different products.

Here's how I approached it:

Identify Key Columns: Focused on the Deal ID and Sales Stage, since the sales stage remains consistent for each deal regardless of the product.

Remove Duplicates: Extracted the Deal ID and Sales Stage columns and removed duplicates to ensure each deal was counted only once.

Pivot Table Magic: Created a PivotTable to count the number of unique Deal IDs for each Sales Stage.

This method provided a clear summary of deal counts by stage, simplifying the analysis.