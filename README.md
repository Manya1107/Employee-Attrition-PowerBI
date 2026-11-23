# Employee Attrition Analysis | Power BI

## Objective
Analyse attrition across 1,000 employees to identify where it concentrates and which factors show a measurable link to it.

## Approach
- Cleaned and modelled the data in Power Query.
- Created DAX measures (attrition rate, retention rate, active employees, averages) and banded fields (age, tenure, income, weekly hours).
- Added rating labels and a data-validation flag.
- Designed a five-page interactive dashboard with synced slicers and page navigation.

## Key Findings
1. **Overall attrition is 18.9%** (189 of 1,000 employees).
2. **IT (21.3%) and HR (20.9%) have the highest attrition.** Sales is lowest at 17.1%.
3. **Longer hours coincide with higher attrition:** 15.8% at 30–40 hours a week, 20.2% at 41–50 hours and 21.1% at 51+ hours.
4. **Employees aged 40 and over leave more** (20.6% to 20.7%) than those aged 30–39 (15.8%).
5. **Executive (20.6%) and Assistant (20.5%) roles** show higher attrition than Analyst (15.5%).
6. **Satisfaction, work-life balance, pay and overtime show no consistent relationship with attrition in this dataset.** Higher satisfaction scores did not coincide with lower attrition.

## Limitations
- Most group differences are 2–4 percentage points across groups of 200–500 people, so they should be treated as directional, not causal.
- 55% of records contained inconsistent tenure, age or promotion values, which are flagged on the dashboard. Tenure and promotion charts are indicative only.

## Tools
Power BI · Power Query · DAX · Data Validation · Dashboard Design

## Dashboard Preview
![Executive Overview](screenshots/page1-executive-overview.png)
