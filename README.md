# Amazon-Sales-Power-BI-dashboard

## Description
This repository contains the Power BI artifact and documentation for the Amazon Sales dashboard. It is designed to help stakeholders explore key sales metrics, trends, and insights.

## Project title
Amazon Sales Power BI Dashboard

## Brief description
- Power BI Desktop report (.pbix) that analyzes Amazon sales data.
- Includes data model, visuals, and calculated measures to track revenue, units sold, order count, and top products by category.
- Documentation provides data fields, measures, data sources, and refresh guidance.

## Data sources
- Primary dataset: Local Power BI Desktop file containing the modeled data (no external data is published).
- If you are linking to public sources, include them here. Example (replace with your actual sources):
  - Amazon sales data public sample: https://example.com/public-amazon-sample-dataset
  - Supplied data dictionary schema: internal data dictionary (not public)

> Note: Do not publish sensitive or PII data. If your dataset contains confidential information, provide a sanitized or sample version and exclude raw data.

## Data privacy notes
- The repository contains a Power BI `.pbix` file. If the file contains sensitive data, consider removing or masking sensitive fields before publishing publicly.
- Do not publish PII or restricted data. Provide data dictionary and sample data only if appropriate for public sharing.
- License terms apply to the code and documentation; ensure you choose an appropriate license (e.g., MIT, Apache 2.0).

## How to run locally
1. Install Power BI Desktop (Windows) [version requirements: e.g., October 2024 update or later].
2. Open `Amazon_Sales_Report.pbix` in Power BI Desktop.
3. If the dataset connects to an external data source, connect using appropriate credentials or use the sample data (if provided in the repository).

Prerequisites:
- Power BI Desktop (Windows)
- Access to any data sources referenced by the report (if you intend to refresh with live data)

## How to refresh data
- Manual refresh (Power BI Desktop):
  1. Open `Amazon_Sales_Report.pbix`.
  2. Go to Home > Refresh.
  3. Enter credentials for any data sources if prompted.
- Schedule refresh (Power BI Service, if you publish there):
  - Not included in this repository. If you publish the report to Power BI Service, configure a dataset refresh schedule in the corresponding workspace settings.
  - Steps (high-level):
    1. Publish the `.pbix` to a workspace.
    2. In Power BI Service, navigate to the dataset.
    3. Configure a refresh schedule (frequency, time, credentials).
  - If you’re sharing a template (`.pbit`), you can guide users to connect to their own data sources and refresh locally.

## License
- Choose a license (e.g., MIT). Replace this section with your chosen license text or a link to the license.

## Notes
- This repository is intended for sharing non-sensitive artifacts of the Amazon Sales dashboard. Adjust contents if you need to keep data private.
- For larger files, consider hosting the `.pbix` in secure storage and linking to it from the README.
