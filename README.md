Maji Ndogo: Water Infrastructure & Public Safety Analysis

- Project Overview
Maji Ndogo is a nation facing a severe water crisis. Using a dataset of over 60,000 water service records and 77,000 crime records, I developed this analytical project to identify where the water system is failing and how those failures impact the safety of citizens.

The core finding of this analysis is the "Cost of Waiting": a direct correlation between long queue times at shared taps and an increase in violent crime incidents affecting women and children.

- Technical Implementation
1. Data Modeling (The Brain)
I transformed raw Excel data into a relational Star Schema to ensure high performance and accurate filtering.

The Challenge: Resolved a "Filter Wall" where province-level filters weren't reaching the water source data.

The Solution: Implemented Bi-directional Cross-filtering between the Visits and Water Source tables.

2. ETL & Data Engineering (Power Query)
Time Intelligence: Extracted the "Hour" from time_of_incident to pinpoint exactly when crimes occur.

Queue Analysis: Cleaned and unpivoted gender data to visualize the disproportionate burden on female citizens.

Custom Sorting: Created a logical sort order for the "Day of the Week" to ensure chronological reporting (Mon-Sun).

- Key Findings

(A) The "Hour of Danger"
The analysis revealed a massive spike in water-related crimes between 4:00 AM and 7:00 AM. This identifies the high-risk window when women are traveling to water sources in the dark to beat the midday heat and crowds.

(B) Infrastructure = Safety
By comparing provinces, the data shows that Amanzi (with better infrastructure distribution) has significantly lower crime rates than Kilimani (high population, long queues). This proves that infrastructure investment is a direct public safety intervention.

- Tools Used: Power BI, Power Query, Star Schema Modeling, Data Visualization.
