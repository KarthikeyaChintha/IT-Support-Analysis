# IT Support Analysis Dashboard

**Tools Used:** Advanced Excel · Pivot Tables · Pivot Charts · XLOOKUP · Conditional Formatting · Interactive Slicers · Dashboards
**Domain:** IT Support · Business Intelligence · Data Analytics

---

## Project Objective

IT support teams handle a large number of tickets related to system issues, software, hardware, and user access. Without proper analysis, it can be difficult to identify workload patterns, SLA performance, resolution bottlenecks, and factors affecting customer satisfaction.

This project analyzes **97,498 IT support tickets** to evaluate ticket distribution, resolution performance, SLA compliance, customer satisfaction, and category-wise workload, helping identify areas where support operations can be improved.

---

## Files in this Repository

| File                                     | Description                                                                                   |
| ---------------------------------------- | --------------------------------------------------------------------------------------------- |
| `IT_Support_Analysis.xlsx`               | Full Excel workbook containing the dataset, analysis, Pivot Tables, and interactive dashboard |
| `IT_Support_Analysis_Documentation.docx` | Detailed project documentation and analytical findings                                        |
| `IT_Support_Analysis_Presentation.pptx`  | Presentation summarizing the project analysis, insights, and recommendations                  |

---

## Data Analysis & Preparation

The IT support dataset was prepared and analyzed in Excel before creating the final dashboard.

Key preparation and analysis activities included:

| Area                  | Analysis Performed                                                   |
| --------------------- | -------------------------------------------------------------------- |
| Ticket Categories     | Classified tickets into Login Access, System, Software, and Hardware |
| Issue Type            | Analyzed IT Requests and IT Errors                                   |
| Resolution Time       | Calculated and compared resolution time across categories            |
| Satisfaction          | Analyzed customer satisfaction scores                                |
| SLA Performance       | Measured the percentage of tickets resolved within SLA               |
| Dashboard Preparation | Organized data using Pivot Tables, Pivot Charts, and slicers         |

---

## Key Analysis Performed

* **Ticket Volume Analysis:** Analyzed the distribution of 97,498 tickets across different support categories
* **Category Analysis:** Compared ticket volumes and resolution times for Login Access, System, Software, and Hardware
* **Issue Type Analysis:** Compared IT Requests and IT Errors
* **Resolution Performance:** Evaluated average resolution time across categories
* **Satisfaction Analysis:** Examined customer satisfaction and its relationship with resolution performance
* **SLA Analysis:** Measured the percentage of tickets resolved within the defined SLA
* **Workload Analysis:** Identified the categories contributing the highest support workload

---

## Key Performance Indicators

| KPI                         | Result        |
| --------------------------- | ------------- |
| Total Tickets               | **97,498**    |
| Average Resolution Time     | **4.55 days** |
| Average Satisfaction Rate   | **4.10 / 5**  |
| Tickets Resolved Within SLA | **53.27%**    |

---

## Ticket Distribution by Category

| Category     | Tickets | Percentage |
| ------------ | ------: | ---------: |
| System       |  39,002 |     40.00% |
| Login Access |  29,193 |     29.94% |
| Software     |  19,570 |     20.07% |
| Hardware     |   9,733 |      9.98% |

**System-related tickets represent the largest share of the support workload at approximately 40% of all tickets.**

---

## Issue Type Distribution

| Issue Type | Tickets | Percentage |
| ---------- | ------: | ---------: |
| IT Request |  73,220 |     75.10% |
| IT Error   |  24,278 |     24.90% |

**IT Requests account for the majority of support tickets, representing approximately 75% of the total workload.**

---

## Resolution Time by Category

| Category     | Average Resolution Time |
| ------------ | ----------------------: |
| Hardware     |           **7.63 days** |
| System       |           **6.62 days** |
| Software     |           **5.24 days** |
| Login Access |           **0.31 days** |

Hardware and System tickets have significantly higher resolution times compared with Login Access and Software tickets, highlighting potential areas for process improvement.

---

## Key Findings

* **System tickets are the largest workload:** They account for approximately **40%** of all support tickets.
* **IT Requests dominate:** Around **75%** of tickets are IT Requests, compared with approximately 25% IT Errors.
* **Hardware tickets take the longest to resolve:** Hardware has an average resolution time of **7.63 days**.
* **System tickets also show high resolution time:** System tickets require an average of **6.62 days** to resolve.
* **Login Access tickets are resolved quickly:** They have the lowest average resolution time at **0.31 days**.
* **SLA performance needs improvement:** Only **53.27%** of tickets were resolved within SLA.
* **Customer satisfaction is generally positive:** The overall average satisfaction score is **4.10 out of 5**.
* **Potential improvement area:** Tickets with **satisfaction below 3.65 and resolution time above 4.80 days** were identified as an area requiring attention.

---

## Dashboard

The Excel file includes an interactive dashboard with:

* Total Ticket KPI
* Average Resolution Time
* Average Satisfaction Rate
* SLA Resolution Percentage
* Ticket distribution by category
* **Ticket distribution by Issue Type**
* Category-wise resolution time
* Satisfaction and resolution analysis
* Interactive Pivot Tables and slicers

<img width="1792" height="556" alt="Dashboard_Preview" src="https://github.com/user-attachments/assets/c9373c12-2dc4-4392-989d-54d89f468fe6" />


---

## Excel Features Used

* `XLOOKUP` for data lookup and mapping
* `COUNTIF` / `COUNTIFS` for ticket analysis
* `AVERAGEIF` / `AVERAGEIFS` for category-wise averages
* `IF` / `IFERROR` for conditional calculations
* Pivot Tables for data summarization
* Pivot Charts for visualization
* Slicers for interactive dashboard filtering
* Conditional Formatting for identifying performance areas
* Excel Dashboard techniques for KPI and trend visualization

---

## Business Recommendations

Based on the analysis, support teams should focus on:

* Reducing resolution time for **Hardware and System tickets**
* Improving **SLA compliance**, which is currently at 53.27%
* Investigating tickets with **low satisfaction and high resolution time**
* Reviewing the high volume of **IT Requests** to identify opportunities for self-service or automation
* Monitoring System-related workload because it represents the largest ticket category

---

## Project Dataset

The project uses an IT support ticket dataset containing **97,498 records** with information related to ticket categories, issue types, resolution time, satisfaction, and SLA performance.

---

## 👨‍💻 Project Overview

This project demonstrates practical skills in **Excel-based data analysis, Pivot Tables, Pivot Charts, dashboard development, KPI tracking, and business insight generation** using a real-world IT support scenario.
