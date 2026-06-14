# 📌 Project Overview

The objective of this project is to simulate a corporate-grade data analytics workflow, demonstrating how raw organizational attendance data can be transformed into meaningful business intelligence and actionable insights.

1. Data Preparation, Modeling & Transformation (Power Query)
*   Connected directly to the raw employee attendance dataset "Attendance-Sheet-2022-2023".
*   Cleaned and unpivoted the complex multi-sheet data structure to flatten dates into a normalized tabular model.
*   Handled missing data entries, standardized tracking codes, and accounted for half-day remote shifts to preserve analytical integrity.

2. Analytical Intelligence & Metric Formulation (DAX)
*   Established a scalable Star Schema data model inside Power BI Desktop.
*   Formulated robust DAX measures to compute dynamic high-level organizational benchmarks.
*   Engineered responsive logic to calculate explicit metrics including Presence %, Work From Home %, and Sick Leave %.

3. Visualization & Insights (Power BI)
*   Designed an interactive, executive-facing dashboard based on "HR ANALYTICS".
*   Visualized clear temporal variations, comparing attendance splits across standard workdays (e.g., Mondays vs. Fridays).
*   Enabled data-driven decision-making through dynamic slicers and comprehensive "slice-and-dice" cross-filtering capabilities.
  
4. Report & Presentation
*   Created a detailed project report summarizing key attendance anomalies, weekly workforce variations, and trend findings.
*   Provided tactical business recommendations to optimize office space costs and anticipate seasonal absenteeism spikes.
*   Developed a professional presentation deck to communicate technical architecture and system migration readiness to senior stakeholders.



🛠️ How to Use This Project

1. Clone the Repository
git clone https://github.com/PrathamGupta2001/Atliq-HR-Presence-Insights.git

2. Open Power BI Template
*  Navigate to the repository folder on your local machine.
*  Open the Atliq_Presence_Insights.pbix file using Power BI Desktop.

3. Review the Core Model
The data architecture contains:
*  Fact_Attendance: The unpivoted, normalized tabular data originating from "Attendance-Sheet-2022-2023".
*  Dim_Date: A customized calendar table mapping days, fiscal weeks, and target months for continuous timeline filtering.
*  Measures Table: Centralized storage holding all explicit DAX formulas for corporate KPIs.

4. Explore the Interactive Dashboard Layout
*  Top KPI Summary Tiles: Quickly scan high-level corporate statistics (94.0% Attendance %, 9.1% WFH %, 0.43% SL %).
*  Cross-Filtering Capabilities: Select any specific Day of the Week, Month Slicer, or individual Employee ID to view contextual metrics instantly.
*  Trend Tracking Visuals: Trace continuous timeline lines to evaluate performance drops or isolate unexpected sick leave outbreaks.

5. Review Documentation and Recommendations
Open the finalized project report to explore strategic business recommendations regarding hybrid workflow distributions and system migration blueprints.






