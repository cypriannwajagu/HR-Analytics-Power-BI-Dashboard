# HR-Analytics-Power-BI-Dashboard
A professional, executive-grade HR Analytics dashboard built in Microsoft Power BI Desktop, designed for strategic workforce decision-making across a 500-employee, 10-country organization.

# 📋 Table of Contents
- 📌 Project Overview
- ⚙️ Tools
- 🗄️ Data Sources & Data Model
- 🔍 Key Observations & Business Recommendations

# 📌 Project Overview
This is a  HR Analytics solution built to transform raw employee data into actionable workforce intelligence. The dashboard enables HR leaders and executives to monitor compensation equity, attendance trends, workforce distribution, and demographic composition — all from a single, interactive Power BI report.

## Business Context
| Attribute | Detail |
|-----------|--------|
| Organization Size | 500 Employees |
Geographic Footprint | 10 Countries · 4 Continents |
| Departments | 6 (Engineering, Finance, HR, IT, Marketing, Sales) |
| Positions | 5 Levels (Analyst, Engineer, Executive, Manager, Specialist) |
|Data Period | January 2010 – December 2024 |
| Total Annual Payroll | $45,406,194 |
| Report Pages | 4 Interactive Dashboard Pages |

 ## Goals
 - Surface compensation inequities across departments, positions, and gender.
 - Monitor attendance performance against the 80% organizational target.
 - Identify workforce aging risks and succession planning gaps.
 - Provide geographic and demographic workforce distribution intelligence.
 - Enable drill-through, slicer-driven, and tooltip-enhanced interactivity for executive presentations.

# ⚙️ Tools & Technologies
| Tool | Version | Purpose |
|------|---------|---------|
| Microsoft Power BI Desktop | Latest | Dashboard development & publishing |
| Microsoft Excel (.xlsx) | Office 365 | Source data & star schema delivery |
| DAX (Data Analysis Expressions) | Built-in | KPI measures & calculated columns |

# 🗄️ Data Sources & Data Model

## Source Dataset
### The raw dataset was restructured into a star schema with one central fact table and five dimension tables, following Power BI best practices for optimal query performance and clean relationship management.
| Attribute | Detail |
|-----------|--------|
| File | dataset.xlsx |
| Rows | 500 employees |
| Columns | 18 raw fields |
| Format | Microsoft Excel (.xlsx) |

# 🔍 Key Observations & Business Recommendations

### 1. Attendance Crisis — Systemic, Not Departmental
#### Observation:
Organizational attendance sits at 79.9% — marginally below the 80% target. However, this average masks a critical pattern: 5 of 6 departments fall below the benchmark. Only Engineering exceeds it at 81.4%. HR, the department responsible for designing engagement programs, records the lowest attendance at 79.5%.
#### Business Recommendation:
Attendance should not be managed as a singular metric — it is a symptom of engagement, compensation, and work mode alignment. The organization should:
- Commission a departmental engagement survey focused on the 5 underperforming departments.
- Investigate whether the 68% remote/hybrid workforce lacks the visibility and accountability structures needed for consistent attendance.
- Study Engineering's practices — its above-target attendance despite being the second-lowest paid department suggests management culture, not compensation, is the primary driver.
- Set department-level attendance targets with quarterly reviews rather than a single org-wide KPI.


