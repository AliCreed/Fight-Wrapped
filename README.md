# Fight Wrapped

## Project Overview
This interactive **Power BI dashboard** was designed to track and analyze personal fight-viewing habits. The project focuses on visualizing combat sports data across multiple sports and eras, providing deep insights into fighter appearances, promotion trends, and total viewing time.

**Github Link:** https://github.com/AliCreed/Fight-Wrapped

---

## Data Model Architecture
- **Fact Table:** `Fight Log` – Main fight log containing match details, fighters, duration, and event metadata  
- **Dimension Table:** `Date` – Calendar table providing date attributes (DayOfWeek, MonthName,...) for time-based analysis  
- **Support Table:** `Fighter Leaderboard` – Disconnected table used for advanced DAX filtering and ranking calculations

---

## How to View
1. Download the `Fight_Wrapped_Dashboard.pbix` file found in this folder.  
2. Open using **Power BI Desktop**.  
3. Alternatively, refer to `Fight_Wrapped_Dashboard.pdf` for a static overview of the design and layout.

---

## Tools Used
- **Power BI Desktop:** Visual design and UI/UX
- **Google Sheets:** Cloud-based data source used for initial data structuring and validation, connected to Power BI for data ingestion.
- **Power Query:** Data cleaning and index generation  
- **DAX:** Advanced measures for duration summing and cross-column filtering  
- **Gemini/ChatGPT (AI Collaborator):** Leveraged as an adaptive AI peer to troubleshoot data model architecture and optimize DAX syntax
