# Cyber Threat Analysis

## Power BI Portfolio Case Study

This project is a multi-page **Power BI dashboard** designed to analyze cyber incidents across attack types, industries, years, and countries. It brings together operational, financial, and geographic views of cyber risk so decision-makers can quickly identify where incidents are concentrated, which attack patterns are most damaging, and where response performance may need improvement.

The dashboard is structured around four business questions:

- How is cyber activity changing over time?
- Which attack types and vulnerabilities are driving the most incidents and losses?
- Which industries and countries appear most exposed?
- Where are response times longest, and what does that imply for risk management?

## Project Objective

The goal of this dashboard is to turn raw cyber incident data into an executive-ready risk monitoring tool. Rather than looking at incidents in isolation, the report connects **incident volume**, **financial loss**, **users affected**, and **resolution time** to help stakeholders prioritize mitigation efforts and allocate resources more effectively.

## Dashboard Walkthrough

### 1. Global Threat Overview

![Global Threat Overview](images/Global%20Threat%20Overview.png)

*Latest screenshot of the Global Threat Overview page, showing KPI cards, the incident trend over time, top targeted industries, attack-type distribution, and the global threat map.*

This landing page provides a high-level summary of the cyber threat environment. Key headline metrics shown in the dashboard include:

- **72 total incidents**
- **$4,124M financial loss**
- **41M users affected**
- **37 average resolution hours**

The time series shows incident counts fluctuating across the reporting period, with a visible spike in **2022**, suggesting a year of elevated threat activity. The industry breakdown indicates that **Education, Healthcare, and IT** are among the most targeted sectors, while the attack type distribution shows activity spread across multiple vectors rather than being dominated by a single category.

### Business Insight

This view suggests that cyber exposure is broad-based, but not evenly distributed. A concentrated level of targeting in sectors such as education and healthcare may reflect environments with large user populations, legacy systems, or higher disruption sensitivity. The 2022 spike also signals the need for year-over-year monitoring rather than relying on static risk assumptions.

### 2. Threat Intelligence Analysis

![Threat Intelligence Analysis](images/Threat%20Intelligence%20Analysis.png)

This page focuses on how attack patterns and exploited vulnerabilities evolve over time.

The stacked incident chart shows cyber events distributed across attack types including:

- DDoS
- Malware
- Man-in-the-Middle
- Phishing
- Ransomware
- SQL Injection

The vulnerability analysis highlights **Social Engineering** and **Unpatched Software** as the most exploited weakness categories, followed by **Zero-day** and **Weak Passwords**. The resolution-time trend also shows that response performance varies materially by vulnerability type from year to year.

### Business Insight

The vulnerability view points to a clear operational theme: many incidents appear to be linked not only to advanced threats, but also to **preventable control gaps**. Social engineering, weak credentials, and unpatched software all indicate that foundational security hygiene remains critical. The year-by-year resolution swings further suggest that some attack classes are less predictable operationally and may require more specialized response playbooks.

### 3. Risk and Impact Analysis

![Risk and Impact Analysis](images/Risk%20and%20Impact%20Analysis.png)

This page translates cyber activity into business impact metrics.

Headline KPIs shown in the dashboard include:

- **$4,124M total financial loss**
- **57M average loss per incident**
- **37 average resolution hours**
- **41M users affected**

The financial impact by attack type shows that:

- **DDoS** has the highest financial loss at **$1,137M**
- **Phishing** follows at **$762M**
- **Man-in-the-Middle** contributes **$705M**
- **SQL Injection** contributes **$617M**
- **Malware** contributes **$574M**
- **Ransomware** contributes **$330M**

The users-affected chart indicates that **DDoS** accounts for the largest share of impact, while the resolution-time chart shows that **Man-in-the-Middle** and **SQL Injection** incidents require the longest average handling time among the displayed attack types.

Industry loss analysis shows the highest financial exposure in:

- **IT**
- **Healthcare**
- **Education**

### Business Insight

This page makes an important distinction between **frequency** and **severity**. The most operationally visible attacks are not always the ones with the longest recovery effort, and the attacks with the largest user impact are not always the most numerous. That distinction matters for leadership teams deciding where to invest. A response model built only around incident counts would underweight attack types that create longer disruption windows or higher financial consequences.

### 4. Geographic Risk Analysis

![Geographic Risk Analysis](images/Geographic%20Risk%20Analysis.png)

This page analyzes cyber risk by country.

The dashboard highlights:

- **Australia** as the highest risk country at **14%**
- **10 total countries impacted**
- **USA** as the country with the longest response time

The bar charts show that total incidents are highest in **Australia, China, and India**, while financial losses are led by **Australia and France**, with **China, India, and Germany** also showing high loss levels. The response-time chart indicates that the **USA** has the slowest incident resolution, followed by **China** and the **UK**.

### Business Insight

The geographic view shows that risk should not be assessed only by incident count. Some countries combine high volume with high financial loss, while others stand out because response time is slower. That means regional cyber posture should be evaluated across three dimensions at once: **incident frequency**, **business impact**, and **response effectiveness**.

## Key Takeaways

- Cyber risk in this dataset is distributed across multiple attack vectors, with no single threat type explaining the full picture.
- **DDoS** appears especially important from a business-impact perspective because it leads in financial loss and users affected.
- **Man-in-the-Middle** and **SQL Injection** deserve attention from an operations standpoint because they show longer average resolution times.
- **Social Engineering** and **Unpatched Software** stand out as major exploited vulnerabilities, pointing to control gaps that are often addressable through process and preventive security measures.
- **IT, Healthcare, and Education** appear to be the most financially or operationally exposed sectors in this dashboard.
- Country-level risk is uneven, with **Australia** standing out on risk share and the **USA** standing out on response duration.

## Recommendations

- Prioritize mitigation for high-impact attack types, especially **DDoS**, where business disruption and financial exposure appear greatest.
- Strengthen foundational controls around **patching, password security, and phishing resistance**, since the vulnerability analysis points to recurring preventable weaknesses.
- Review incident response workflows for attack types with longer handling times, particularly **Man-in-the-Middle** and **SQL Injection**, to reduce containment and recovery delays.
- Use industry targeting patterns to guide sector-specific controls, especially for **IT, Healthcare, and Education**, where the dashboard shows elevated pressure.
- Evaluate country-level response readiness separately from incident volume; regions with slower resolution may need additional staffing, automation, or escalation support.
- Monitor trends over time, especially years with visible spikes such as **2022**, to determine whether threat surges reflect temporary events or a sustained shift in risk.

## Technical Highlights

- Built in **Power BI**
- Designed as a **four-page interactive report**
- Includes slicers for **Attack Type**, **Year**, and **Country**
- Combines **KPI cards**, **time-series analysis**, **bar charts**, **donut charts**, and **map visuals**
- Supports both **executive summary reporting** and **drill-down analysis** by threat type, geography, and industry

## Why This Project Matters

This case study demonstrates how analytics can make cybersecurity data more actionable for business stakeholders. Instead of treating cyber incidents as isolated technical events, the dashboard frames them in terms of financial impact, operational burden, affected users, and geographic concentration. That makes the report useful not just for analysts, but also for leaders responsible for risk prioritization, resilience planning, and resource allocation.
