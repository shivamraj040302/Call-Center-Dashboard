# Call Centre Operational Analysis Dashboard

## 📊 Project Overview
This Power BI project provides a comprehensive 360-degree view of Call Centre performance. It is designed to help Operations Managers identify volume trends, monitor Service Level Agreements (SLAs), and understand customer sentiment across multiple communication channels.

### Key Business Questions Addressed:
* What are the primary drivers of call volume?
* How does customer sentiment vary across different inquiry reasons?
* Which regions and channels are performing within or below SLA?
* What is the average handling time for complex billing issues?

## 🚀 Key Features
* **Executive Summary KPI Tiles:** Instant visibility into Total Calls (33K), Total Duration, and Response Time % (87.3%).
* **Sentiment Tracking:** A stacked column chart visualizing the relationship between call reasons and customer emotions.
* **Geospatial Analysis:** Integrated US Map to identify regional hotspots (Primary hubs: Los Angeles and Baltimore).
* **Granular Data Grid:** A dedicated "Grid View" for drill-through analysis of individual customer interactions.
* **Interactive Slicers:** Filter the entire report by Channel, Date Range, or specific Call Centre locations.

## 🛠️ Tools Used
* **Power BI Desktop:** For ETL (Power Query), Data Modeling, and DAX calculations.
* **Dataset:** (Mention your source here, e.g., CSV/SQL Database) containing call logs, timestamps, and sentiment scores.

## 📈 Insights & Recommendations
* **Billing Issues:** Since "Billing Questions" account for the majority of calls, implementing an automated IVR or improved FAQ section for billing could reduce human agent load.
* **Sentiment Gap:** The high volume of "Negative" sentiment calls correlates with "Service Outages." Improving proactive customer communication during outages could mitigate this.
* **Staffing:** Call volume peaks on Thursdays and Fridays; staffing levels should be optimized for the end-of-week surge.

## 📂 How to Use
1.  Download the `.pbix` file from this repository.
2.  Open the file in **Power BI Desktop**.
3.  Use the side navigation bar to switch between the **Visual Dashboard** and the **Data Grid**.
4.  Interact with the slicers on the left to filter by specific timeframes or channels.

---
*Created by **Shivam Raj**
