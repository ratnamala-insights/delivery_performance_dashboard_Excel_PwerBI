# FirstCry Delivery Performance Analysis

## Project Overview
This project provides a data-driven analysis of FirstCry’s logistics operations. By examining 5,000 order records, I identified key performance indicators (KPIs) related to delivery success, turnaround time (TAT), and return-to-origin (RTO) patterns.

The goal of this project was to evaluate delivery partner efficiency and pinpoint the primary reasons for non-delivery (NDR).

## Key Performance Indicators (KPIs)
Based on the analysis, the following high-level metrics were identified:
- **Delivery Success Rate:** 76.78%
- **RTO (Return to Origin) Rate:** 23.22%
- **Late Delivery Rate:** 66.24%
- **Average Turnaround Time (TAT):** 3.95 Days

## Tools & Methodology
### Microsoft Excel
- **Data Cleaning:** Handled missing delivery dates and standardized state/city naming conventions.
- **Pivot Analysis:** Created initial summaries to identify trends in NDR (Non-Delivery Report) reasons and seasonal performance.

### Power BI
- **Data Modeling:** Imported cleaned Excel data into Power BI for advanced visualization.
- **DAX & Calculated Fields:** Developed custom measures to track:
  - `Success Rate %`
  - `Late Delivery Flag` (Logic based on Promised vs. Actual dates)
  - `Actual TATcal` (Calculating working days for delivery)
- **Interactive Dashboard:** Built a multi-page dashboard featuring regional maps, vendor comparison charts, and a decomposition tree for NDR reasons.

## Insights & Findings
- **Top Performer:** **Delhivery** and **DTDC** maintained the highest success rates (78-80%).
- **Delivery Challenges:** "Insufficient contact details" and "Customer unavailable" accounted for the majority of delivery failures.
- **Regional Trends:** The **North** region showed the highest delivery efficiency, while the **East** region faced the highest percentage of RTOs.
- **Seasonality:** Performance dipped during the **Festive season**, suggesting a need for increased logistics capacity during peak sales periods.

## Repository Structure
- `/Data`: Contains the `FC_project.xlsx` source file.
- `/Dashboard`: Contains the `Firstcry_PowerBI.pbix` file.
- `README.md`: Project documentation.

## How to Use
1. Download the `.pbix` file.
2. Open it using **Power BI Desktop**.
3. Ensure the data source is linked to the provided Excel file to view the interactive elements.
