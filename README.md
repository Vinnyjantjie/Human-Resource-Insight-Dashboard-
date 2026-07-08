# Human Resource Insight Dashboard 
This project analyses an HR employee dataset to answer the four core people analytics questions.

# HR Analytics Dashboard: Project Report

**Tools used:** Python · SQL · Power BI
**Dataset:** 1,200 employee records across 7 departments from 2016 to 2026

---

## 1. Project Overview

This project analyses an HR employee dataset to answer four core people analytics questions that most organizations track:

1. **Why are we losing employees and where?** (Turnover)
2. **Who is missing work and why does it matter?** (Absenteeism)
3. **How diverse is our workforce and is it equitable?** (Gender Diversity)
4. **Are we hiring enough and where are candidates coming from?** (Hiring Trends)

The workflow mirrors a real analytics pipeline and raw data was structured and cleaned with **Python**, explored and aggregated with **SQL** and turned into an interactive, decision ready **Power BI** dashboard with drill down filtering by department, gender and year.

---

## 2. Data

| Attribute | Detail |
|---|---|
| Records | 1200 employees |
| Fields | 23 (demographics, department/role, hire and termination dates, salary, absenteeism, satisfaction scores and recruitment source) |
| Time span | Hires from 2016 to 2026 |
| Departments | Sales, Research & Development, IT, Finance, HR, Marketing and Operations |
| Format | CSV · Excel · SQL |

The three files are structured identically so the same story can be told in Excel, SQL or Power BI showing range across tools rather than one dashboard alone.

---

## 3. Dashboard Structure

The Power BI report is organized into an **Overview** page plus one page per business question, with global slicers for **Department**, **Gender**, and **Hire Year** that filter every visual on every page.

### Page 1 - Overview
A summary landing page with headline KPI cards so a viewer gets the full picture in five seconds:

- **Total Employees:** 1,200
- **Turnover Rate:** 18.1%
- **Average Absenteeism:** 9.1 days per employee
- **Gender Split:**  49.0% Male · 48.7% Female · 2.3% Non-Binary

---

### Page 2 - Employee Turnover
**Visuals:** bar chart of turnover rate by department, line chart of terminations by year, donut of termination reasons and KPI cards for average tenure.

*What it explains:*
- Overall turnover sits at **18.1%** (217 of 1200 employees) which is on the high side of the healthy 10 to 15% benchmark most companies target which is a natural talking point for the dashboard.
- **Sales has the highest turnover (22.6%)**, followed by Operations (20.0%) and Finance (19.0%). **Marketing is the most stable** at 13.4%.
- Employees who leave do so much earlier as **average tenure at exit is 2.5 years** versus **5.4 years** for employees who stay. A classic sign that early tenure retention (onboarding and first year management) is the real problem, not long term burnout.
- Termination reasons are fairly evenly spread across resignations, retirements, layoffs and dismissals so no single cause dominates as leadership would need to look department by department rather than assume one root cause.

**Why it matters:** this page reframes "turnover" from a single number into an actionable insight, *Sales and early tenure employees* are where retention effort should focus first.

---

### Page 3 - Absenteeism
**Visuals:** bar chart of average absence days by department, scatter plot of job satisfaction vs. absence days, table of high absence employees (15+ days per year).

*What it explains:*
- Company wide average is **9.1 absent days per employee per year** with **74 employees (6.2%)** logging 15+ days which is a useful watch list size for HR to review.
- There's a clear inverse relationship between **job satisfaction and absenteeism** as employees who rate satisfaction "1" average **12.6 absent days**, while those rating "4" average just **7.5 days** at a 40% gap.
- Employees who work **overtime average more absences (10.5 vs. 8.5 days)**, hinting that overwork may be driving burnout related absence rather than just being a productivity trade off.

**Why it matters:** this page connects absenteeism to a *leading indicator* (satisfaction and overtime) rather than just reporting a lagging symptom as a level of insight that goes beyond a basic count of absences chart.

---

### Page 4 - Gender Diversity
**Visuals:** donut chart of gender split, stacked bar of gender by department, clustered column comparing average salary by gender and gender representation in management roles.

*What it explains:*
- Overall gender balance is close to even at **49.0% Male, 48.7% Female and 2.3% Non-Binary**.
- Average salary is broadly comparable across genders (**$48.6K Female, $49.5K Male, $51.5K Non Binary**) with no material pay gap in this dataset, which is itself worth stating explicitly rather than assuming.
- Representation in manager/director titled roles roughly tracks overall headcount (**215 Male, 198 Female, 6 Non Binary** in leadership titles), suggesting no obvious promotion bottleneck by gender as though a real analysis would also check *department-level* leadership representation and not just company wide.

**Why it matters:** rather than just showing a pie chart, this page actively checks for pay and promotion equity which is the questions a real DEI stakeholder would ask next.

---

### Page 5 - Hiring Trends
**Visuals:** line chart of new hires by year, bar chart of hires by recruitment source and stacked area of hires by department over time.

*What it explains:*
- Hiring has been **remarkably steady** averaging 113 new hires per year from 2016 to 2025, with no major hiring freeze or spike visible which is a useful context for workforce planning.
- **Employee Referral (208 hires) and Recruitment Agency (205 hires)** are the top two sources, narrowly ahead of University Fair, LinkedIn and Company Website, meaning recruitment spend is fairly diversified rather than over reliant on one channel.
- Combining this page with the Turnover page shows that **net headcount is still growing year over year** since hires consistently outpace terminations.

**Why it matters:** this page turns "hiring trends" into a workforce planning story which ask questions like, is the company growing, shrinking or flat and where do new hires actually come from?

---

## 4. Key Takeaways (Executive Summary)

1. **Turnover (18.1%) is concentrated in Sales and in the first two years of tenure** as retention efforts should target onboarding and Sales management not the whole company equally.
2. **Absenteeism correlates strongly with low job satisfaction and overtime** which is an early warning system based on these two fields could flag at risk employees before they become long term absence cases.
3. **Gender representation and pay are currently balanced** across the workforce and in leadership roles which are a positive finding worth monitoring rather than a fixed state to assume.
4. **Hiring has been stable and diversified across sources** and net headcount is growing while the business is not in a hiring crisis but Sales attrition is quietly offsetting some of that growth.


Contact
Vinny Shongwe — Data Analyst 📧 Vinnyjantjie@gmail.com
