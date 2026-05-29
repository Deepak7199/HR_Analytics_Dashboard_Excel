**HR Attrition Analytics Dashboard**

A dynamic and interactive Excel-based HR Analytics Dashboard designed to monitor, analyze, and uncover key trends behind employee attrition. The visual layout and background UI were custom-built using PowerPoint to provide a clean, modern, software-like presentation layer.

## Project Overview
Employee turnover costs businesses time and resources. This project explores a comprehensive HR dataset containing **1,470 employees** to identify the underlying drivers of attrition. By analyzing demographics, job roles, education, and satisfaction metrics, this dashboard equips HR leadership with data-backed insights to improve retention strategies.

<img width="1905" height="760" alt="image" src="https://github.com/user-attachments/assets/44b4e109-0aaf-4d9b-8408-c89d8b1fb844" />

## Key Insights & Metrics
* **Total Employees:** 1,470
* **Attrition Count:** 237 employees have left the organization.
* **Overall Attrition Rate:** 16.12%
* **Average Employee Age:** 37 years (36.9 unrounded)
* **Average Job Satisfaction Rating:** 2.63 / 4

<img width="1013" height="83" alt="image" src="https://github.com/user-attachments/assets/2e94a6dc-767f-4780-833c-499bc3882c9f" />


### Major Findings from the Visualizations:
* **Department & Role Risks:** The Research & Development department experiences the highest volume of attrition (56% of total exits), closely followed by Sales (38.8%). Specifically, **Laboratory Technicians** and **Sales Executives** are the most vulnerable roles.
* **Age Demographics:** Attrition heavily spikes in the **25–34 age band** (112 exits), with single employees within this bucket being the most prone to leaving.
* **Education Factor:** Employees holding a **Bachelor's Degree** make up the largest portion of the attrition count (99 exits).

<img width="291" height="205" alt="image" src="https://github.com/user-attachments/assets/dba5108c-971d-4466-92a9-c9affdb72a66" />

<img width="330" height="190" alt="image" src="https://github.com/user-attachments/assets/acb996a1-6b6e-49ee-b732-d1555bda5ef4" />

<img width="497" height="207" alt="image" src="https://github.com/user-attachments/assets/c159b718-c9e1-45a0-a0f9-8d5ac973febe" />

## Tools & Techniques Used

* **Microsoft Excel:**
  * **Pivot Tables & Pivot Charts:** For aggregating complex HR attributes.
  * **Formulas & Data DAX/Cleaning:** Custom field logic (`CF_attrition count`, custom grouping bands).
  * **Slicers:** Added interactive filters for *Department*, *Education Field*, and *Gender* to enable dynamic drill-downs.

 <img width="1490" height="391" alt="image" src="https://github.com/user-attachments/assets/6dcd7412-10e2-4bfe-90b4-9ac0bfcbcc46" />

<img width="905" height="561" alt="image" src="https://github.com/user-attachments/assets/67a9004d-6f19-4a81-88d2-465fdeddf613" />

<img width="211" height="217" alt="image" src="https://github.com/user-attachments/assets/f7a3859e-14c4-43f0-b90c-d55c05871118" />

* **Microsoft PowerPoint:**
  * Used to sketch and export a custom dark-themed UI canvas background, ensuring precise grid alignment and a modern look.

  <img width="1097" height="619" alt="image" src="https://github.com/user-attachments/assets/ba86c917-384a-4b84-851b-2d9ed9ccd101" />

## 📁 Repository Structure
```text
├── Data/
│   └── HR_Dataset.csv             # Raw anonymous HR employee data
├── Dashboard.xlsx                 # Main interactive Excel workbook 
└── README.md                      # Project documentation (this file)

**How to Use the Dashboard**

Download the Dashboard.xlsx file from this repository.

Open it using Microsoft Excel (Desktop version recommended for optimal macro/slicer performance).

Use the Slicers on the left-hand panel to filter the charts by specific departments or demographics to see real-time updates across the KPIs.

**Let's Network!**

If you have any questions about the data modeling, design process, or just want to chat about People Analytics, feel free to reach out on LinkedIn!
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/deepak-shukla-30b6492a9/?skipRedirect=true)
