# HR Analytics Power BI Dashboard
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

### 2. HR Department Compensation Paradox
#### Observation:
The HR department — responsible for talent acquisition, compensation design, and employee experience — is simultaneously the lowest paid ($82,763 avg) and the worst attending (79.5%) department in the organization. HR also has the fewest high earners at only 24 employees above $100K, compared to Finance's 43.
#### Business Recommendation:
This is a structural risk. An underpaid, disengaged HR team will struggle to attract and retain talent across the rest of the organization. The board should:
- Conduct an immediate HR compensation benchmarking study against industry data.
- Target at minimum a 10% salary uplift for HR to bring it closer to the organizational average.
- Address the irony directly in the next board report — the function that manages compensation equity is itself experiencing it.
- Introduce HR-specific KPIs on the dashboard (time-to-hire, retention rate, offer acceptance rate) to make the team's value visible.

### 3. Aging Workforce — Succession Planning Is Urgent
#### Observation:
The 51–60 age cohort is the single largest group at 128 employees (25.6%) of the workforce. The 21–30 cohort follows at 120 employees. Within the next 5–10 years, more than a quarter of the organization could transition into retirement, taking with them years of institutional knowledge, client relationships, and organizational context.
#### Business Recommendation:
- Build a Retirement Risk Dashboard (Power BI page or sub-report) that projects retirement-eligible headcount (age 60+) by department and position for years 1, 3, 5, and 10.
- Launch a formal Knowledge Transfer Program targeting the 128 employees aged 51–60 — pairing them with Junior Analysts, Engineers, and Specialists for structured mentorship.
- Prioritize succession plans for Executive and Manager roles held by the 51–60 cohort (22.4% of all roles are Executive — many likely in this age group).
-Review hiring strategy: the 21–30 cohort at 120 employees is healthy but must be grown faster to offset future attrition.

 ### 4. Strong Global Diversity — Leverage It Strategically
#### Observation:
The organization has a near-perfectly balanced global presence across 10 countries and 4 continents, with headcount ranging from just 39 (Brazil) to 56 (Japan). This exceptional geographic diversity is not accidental — it reflects a deliberate global talent strategy and a strong foundation for building a truly inclusive organization.
#### Business Recommendation:
- Normalize salaries to Purchasing Power Parity (PPP) by country — an employee in Nigeria earning $88K has dramatically different real compensation than a US employee at $92K.
- Develop country-specific attendance and engagement benchmarks rather than applying a single global 80% target.
- Report diversity metrics in the executive summary as a competitive advantage in annual reports and investor communications.
- Ensure the Filled Map visual on Page 4 is presented in every board meeting as a live testament to geographic workforce strategy.





