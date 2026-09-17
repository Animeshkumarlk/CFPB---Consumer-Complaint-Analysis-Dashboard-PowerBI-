# 📊 CFPB Consumer Complaint Analysis Dashboard | Power BI

## 📌 Project Overview

The **CFPB Consumer Complaint Analysis Dashboard** is an interactive Power BI dashboard created to analyze consumer complaints related to financial products and services reported to the Consumer Financial Protection Bureau (CFPB). The project covers complaint data from **2017 to 2023** and focuses on understanding complaint volumes, financial products, complaint issues, geographic distribution, submission channels, company responses, resolution types, and timely response performance.

The dashboard is designed to transform raw consumer complaint data into an easy-to-understand business intelligence solution that can help stakeholders identify complaint patterns, monitor operational performance, understand customer issues, and explore potential areas for deeper root-cause and predictive analysis.

![CFPB Consumer Complaint Analysis Dashboard](<img width="1957" height="1096" alt="CFPB_preview" src="https://github.com/user-attachments/assets/1ad0c3c9-3a4b-4496-be69-e31509997038" />
)

---

## 🎯 Project Objective

The primary objective of this project is to use Power BI and data visualization techniques to understand the factors behind consumer complaints and evaluate how complaints are handled. The dashboard moves from basic business questions such as which products and states generate the highest complaint volumes to deeper questions involving operational performance, recurring issues, complaint trends, and potential drivers of delayed responses.

The analysis is structured around five levels: basic business analysis, operational performance, root-cause analysis, time-series analysis, and executive-level analysis.

---

## 📊 Dashboard Overview

The dashboard provides a consolidated view of more than **62K consumer complaints**, covering **9 financial product categories, 51 states, and 76 complaint issues**. It includes key performance indicators for total complaints, timely response percentage, total products, total states, total issues, and average response days.

The dashboard also includes interactive filters for date submitted, state, product, timely response, and submission channel, allowing users to explore specific segments of the complaint dataset.

---

## 🔎 Product, State & Complaint Issue Analysis

The first analytical section focuses on understanding where complaints are concentrated. The **Top Products by Complaints** visualization compares complaint volumes across financial products, while the **Top States by Complaints** visualization highlights states with higher complaint volumes. The **Top Complaint Issues** visualization identifies the issues most frequently mentioned by consumers.

Together, these visualizations provide an overview of the major sources of complaint activity and help answer questions such as which products generate the highest number of complaints, which states have the highest complaint volumes, and what issues are most commonly reported.

![Product, State and Issue Analysis](Screenshots/cfpb-product-state-issue.png)

---

## 📈 Complaint Trends & Geographic Distribution

The **Total Complaints by Year** visualization tracks complaint volumes from 2017 through 2023. This time-series analysis makes it possible to observe changes in complaint activity across different years and identify periods where complaint volumes increased or decreased.

The dashboard also includes a **Complaint Distribution by State** map, providing a geographic view of complaint activity across the United States. This allows users to visually identify areas with relatively higher concentrations of complaints.

![Complaint Trend and Geographic Distribution](Screenshots/cfpb-trend-map.png)

---

## ⏱️ Response & Resolution Analysis

Customer response performance is another important component of the dashboard. The **Timely Response vs Target** gauge provides a high-level view of the percentage of complaints receiving timely responses, with the displayed dashboard showing approximately **94% timely responses**.

The **Complaint Resolution Types** visualization analyzes how companies responded to complaints, including categories such as closed with explanation, closed with monetary relief, closed with non-monetary relief, in progress, and closed. The **Complaint Submission Channels** visualization shows how consumers submitted complaints through channels such as web, referral, phone, and postal mail.

This section helps connect complaint volume with customer service and operational performance.

![Resolution, Submission Channels and Timely Response](Screenshots/cfpb-resolution-response.png)

---

## 💡 Key Insights

The current dashboard view shows more than **62K consumer complaints** across multiple financial products and U.S. states. Checking and savings accounts represent the highest complaint volume among the displayed products, followed by credit card and credit reporting-related categories.

California, Florida, and Texas appear among the states with the highest complaint volumes in the displayed analysis. The dashboard also shows approximately **94% of complaints receiving timely responses**, while web-based submissions represent the dominant complaint submission channel in the current view.

The yearly trend indicates that complaint volumes changed considerably between 2017 and 2023, with the highest displayed annual complaint volume occurring in 2022.

These observations represent the dashboard's current displayed/default view and can change when interactive filters are applied.

---

## 🧠 Business Questions

The dashboard was developed around a series of business questions. At the basic business level, the analysis explores which products generate the highest number of complaints, which states generate the highest complaint volumes, and how customers submit complaints.

At the operational performance level, the dashboard examines the percentage of complaints receiving timely responses and provides a framework for identifying products and states with weaker response performance.

At the root-cause level, the analysis explores the most common complaint issues, product-issue combinations generating high complaint volumes, and whether similar issues occur across multiple products.

The time-series analysis focuses on how complaint volumes have changed over time, which products may be experiencing faster complaint growth, and whether complaint activity changed significantly after specific years.

At the executive level, the project also explores questions such as whether certain complaint channels are associated with faster resolution, whether web-based complaints are more likely to receive timely responses, and what factors may be associated with delayed responses.

---

## 🤖 Potential Machine Learning Extension

The project can be extended beyond descriptive analytics into predictive analysis. One potential extension would be to build a machine learning model capable of predicting whether a complaint is likely to receive a delayed response.

Potential predictive features could include the **product, state, submission channel, and complaint issue**, while the response outcome could be represented using the timely response field, such as **Timely = Yes** or **Timely = No**.

This extension would allow the project to move from understanding what happened toward identifying patterns that may be associated with delayed responses.

---

## 🛠️ Tools & Technologies

This project was developed using **Microsoft Power BI** for data visualization, interactive dashboard development, KPI creation, filtering, geographic analysis, time-series analysis, and business intelligence reporting.

The project demonstrates concepts including **data analysis, exploratory analysis, KPI development, business intelligence, customer experience analytics, operational performance analysis, root-cause analysis, trend analysis, geographic analysis, and data storytelling**.

---

## 🎨 Dashboard Design

The dashboard uses a dark modern interface with high-contrast KPI cards, cyan/turquoise visual accents, interactive filters, charts, a geographic map, and an executive summary section. The layout was designed to provide a quick overview of the most important metrics while allowing users to explore the underlying complaint patterns through interactive visualizations.

The dashboard combines descriptive analysis and executive-level reporting into a single interface, making it possible to move from high-level KPIs to detailed complaint analysis.

---

## 📂 Repository Structure

The repository contains the Power BI dashboard file, dashboard screenshots, and supporting project documentation. The recommended structure is:

CFPB-Consumer-Complaint-Analysis/

├── README.md

├── Dashboard/

│   └── CFPB_Consumer_Complaint_Analysis.pbix

├── Screenshots/

│   ├── cfpb-dashboard-full.png

│   ├── cfpb-product-state-issue.png

│   ├── cfpb-trend-map.png

│   └── cfpb-resolution-response.png

└── Documentation/

    └── Project-Questions.md

---

## 🚀 Future Improvements

Future development of this project could include dedicated drill-through pages for individual products and states, product-versus-issue heatmaps, detailed delayed-response analysis, year-over-year growth calculations, dynamic tooltips, additional DAX measures, and deeper root-cause analysis.

A machine learning model for predicting delayed responses could also be developed as an advanced analytics extension using product, state, channel, and issue-related features.

---

## 👨‍💻 Skills Demonstrated

This project demonstrates practical experience with **Power BI, data visualization, business intelligence, dashboard design, KPI development, data analysis, customer experience analytics, operational analytics, trend analysis, geographic analysis, root-cause analysis, and data storytelling**.

---

## 📜 Disclaimer

This project is created for educational and portfolio purposes. The dashboard represents an independent analysis of consumer complaint data and should not be interpreted as an official CFPB report or official statement from the Consumer Financial Protection Bureau.

---

## ⭐ Conclusion

The CFPB Consumer Complaint Analysis Dashboard demonstrates how consumer complaint data can be transformed into an interactive business intelligence solution. By combining complaint volume, product analysis, geographic distribution, complaint issues, submission channels, resolution types, response performance, and time-series analysis, the project provides a structured approach to understanding customer complaints and identifying opportunities for deeper operational and predictive analysis.
