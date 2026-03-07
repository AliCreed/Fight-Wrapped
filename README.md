# Fight Wrapped

## Project Overview
This interactive **Power BI dashboard** was designed to track and analyze personal fight-viewing habits throughout **2026**. The project focuses on visualizing combat sports data across multiple sports and eras, providing deep insights into fighter appearances, promotion trends, and total viewing time.

**Github Link:** https://github.com/AliCreed/Fight-Wrapped

---

## Data Model Architecture
- **Fact Table:** `2026` – Main fight log containing match details, fighters, duration, and event metadata  
- **Dimension Table:** `Date` – Calendar table providing date attributes (DayOfWeek, MonthName,...) for time-based analysis  
- **Support Table:** `Fighter Leaderboard` – Disconnected table used for advanced DAX filtering and ranking calculations

---

## How to View
1. Download the `Jan_2026_Fight_Log_Dashboard.pbix` file found in this folder.  
2. Open using **Power BI Desktop**.  
3. Alternatively, refer to `Jan_2026_Fight_Log_Dashboard.pdf` for a static overview of the design and layout.

---

## Tools Used
- **Power BI Desktop:** Visual design and UI/UX
- **Excel** – Initial data organization and validation before model import  
- **Power Query:** Data cleaning and index generation  
- **DAX:** Advanced measures for duration summing and cross-column filtering  
- **Gemini/ChatGPT (AI Collaborator):** Leveraged as an adaptive AI peer to troubleshoot data model architecture and optimize DAX syntax
