# Fundraising Performance & Data Quality Analysis

## Overview

This project evaluates fundraising campaign performance using supporter, campaign and response datasets.

The analysis combines data quality auditing, data validation, data cleansing and business analysis techniques to assess campaign effectiveness, donor behaviour, return on investment (ROI), channel performance and fundraising opportunities.

Before analysis, a structured data quality review was conducted to identify, document and address issues relating to completeness, consistency, accuracy, integrity and compliance across multiple datasets.

The objective was to produce reliable, decision-ready insights to support fundraising strategy, donor engagement and operational improvement.

---

## Business Questions

This analysis was designed to answer the following questions:

- Which campaigns generated the highest fundraising income?
- Which campaigns delivered the strongest return on investment?
- Which donor segments contributed the greatest value?
- Which communication channels performed most effectively?
- Are there demographic patterns in donor behaviour?
- Are there geographic differences in fundraising performance?
- What data quality issues could impact reporting accuracy and decision-making?
- What actions could improve future fundraising outcomes?

---

## Data Sources

The analysis was conducted using three linked datasets:

### Supporters
Supporter demographic, contact and communication preference information.

### Campaign Responses
Campaign engagement and donation activity.

### Campaign Master
Campaign metadata including campaign budgets and operational details.

The datasets were validated and combined to enable campaign, supporter and fundraising performance analysis.

---

## Data Quality Audit

A structured audit process was performed before analysis to improve reliability and trust in reporting outputs.

### Data Quality Activities

- Duplicate supporter detection and investigation
- Email standardisation and validation
- Phone number standardisation and error detection
- Date format standardisation
- Missing value assessment
- Campaign naming standardisation
- Channel label standardisation
- Communication preference compliance checks
- Join validation across supporter, campaign and response datasets
- Outlier and anomaly identification

### Key Issues Identified

- 30 supporter records with missing email addresses
- 24 records with missing dates of birth
- 21 records with missing postcodes
- Duplicate supporter profiles identified through repeated email addresses
- Invalid and incomplete phone numbers
- Future-dated records requiring review
- Missing supporter identifiers within campaign responses
- Communication preference inconsistencies
- Donation value outliers requiring validation

### Audit Outcomes

All identified issues were documented within an audit log together with remediation actions and review outcomes.

Data quality controls included:

- Standardisation of names, emails and phone numbers
- Validation flags for suspect records
- Join validation across datasets
- Date-format standardisation
- Campaign naming corrections
- Communication preference compliance checks
- Outlier identification and review

---

## Campaign Performance Analysis

### Highest Income Campaigns

| Campaign | Total Income |
|-----------|-------------:|
| Winter Appeal 2024 | £109,036 |
| Summer Gala 2024 | £66,208 |
| Digital Acquisition Spring | £58,237 |
| Annual Report Mailing | £45,579 |
| Spring Raffle 2025 | £33,613 |

Winter Appeal 2024 generated the highest fundraising income across all campaigns.

### Campaign Efficiency (ROI)

Income alone did not always indicate campaign effectiveness.

| Campaign | ROI |
|-----------|-----:|
| Volunteer Thank You Dinner | 6.1x |
| Annual Report Mailing | 5.5x |
| Winter Appeal 2024 | 3.4x |
| Spring Raffle 2025 | 3.2x |
| Digital Acquisition Spring | 1.9x |
| Monthly Giving Drive Q1 | 1.9x |
| Legacy Awareness Week | 1.8x |
| Christmas Gift Catalogue | 1.4x |
| Emergency Appeal – Flood Relief | 0.8x |
| Summer Gala 2024 | 0.5x |

Key observation:

- Volunteer Thank You Dinner delivered the strongest return on investment despite generating relatively lower total income.
- Summer Gala 2024 generated substantial income but produced the lowest ROI.

This demonstrates the importance of evaluating both income generation and fundraising efficiency.

---

## Channel Performance

### Total Fundraising Income by Channel

| Channel | Total Income |
|----------|-------------:|
| Email | £148,771 |
| Direct Mail | £138,412 |
| Digital | £95,968 |
| SMS | £33,698 |
| Social Media | £17,778 |
| Telephone | £2,338 |

Key findings:

- Email generated the highest fundraising income.
- Direct Mail remained a major contributor.
- Digital generated substantial income despite lower overall volume than Email and Direct Mail.

---

## Donor Segmentation Analysis

### Total Income by Segment

| Segment | Total Income |
|----------|-------------:|
| Major Donor | £288,703 |
| One-Time Donor | £61,706 |
| Legacy Pledger | £42,280 |
| Mid-Value | £19,012 |
| Lapsed | £7,626 |
| Regular Giver | £4,895 |
| Prospect | £2,777 |

Key findings:

- Major Donors contributed the largest share of fundraising income.
- Income generation was heavily concentrated within a relatively small number of donor groups.
- Legacy Pledgers represented another important contributor to fundraising performance.

---

## Demographic Analysis

### Total Income by Age Group

| Age Group | Total Income |
|------------|-------------:|
| 18–34 | £27,483 |
| 35–49 | £118,079 |
| 50–64 | £149,208 |
| 65+ | £109,077 |

Key findings:

- Supporters aged 50 and above generated the majority of fundraising income.
- The 50–64 age group produced the highest contribution.
- Younger supporters contributed a significantly smaller share of total income.

---

## Geographic Analysis

### Highest Performing Counties

| County | Total Income |
|----------|-------------:|
| South Glamorgan | £64,927 |
| Hampshire | £32,750 |
| Oxfordshire | £27,808 |
| Norfolk | £24,860 |
| Strathclyde | £24,157 |

### Lowest Performing Counties

| County | Total Income |
|----------|-------------:|
| Bedfordshire | £1,135 |
| Lothian | £1,231 |
| Somerset | £1,422 |
| Antrim | £1,468 |
| Cheshire | £2,004 |

The analysis identified significant regional variation in fundraising performance.

---

## Key Insights

### Insight 1 – Income and Efficiency Are Not the Same

Winter Appeal 2024 generated the highest fundraising income.

However, Volunteer Thank You Dinner and Annual Report Mailing delivered significantly stronger returns on investment.

### Insight 2 – Major Donors Drive Fundraising Performance

Major Donors generated the largest share of total income, highlighting both a fundraising strength and a dependency risk.

### Insight 3 – Email and Direct Mail Remain Critical

Email and Direct Mail generated the highest levels of fundraising income across all channels.

### Insight 4 – Older Supporters Generate Most Income

Supporters aged 50 and above contributed the majority of fundraising income.

### Insight 5 – Data Quality Directly Impacts Reporting Reliability

Missing values, duplicate records, inconsistent formats and identifier issues were identified across the datasets and required remediation before analysis.

---

## Recommendations

Based on the analysis, five actions could strengthen fundraising performance:

1. Prioritise campaigns that deliver strong return on investment.
2. Review high-cost fundraising activities such as Summer Gala 2024.
3. Focus future campaign investment on high-performing channels, particularly Email and Direct Mail.
4. Strengthen relationships with Major Donors and Legacy Pledgers.
5. Develop engagement strategies to attract younger supporters and diversify the donor base over time.

---

## Tools Used

- Microsoft Excel
- Pivot Tables
- XLOOKUP
- IF Statements
- Data Validation
- Conditional Formatting
- Lookup Functions
- Data Cleansing Techniques
- Business Analysis
- Data Quality Auditing

---

## Skills Demonstrated

- Data Analysis
- Data Quality Assessment
- Data Validation
- Data Cleansing
- Business Intelligence
- Stakeholder Reporting
- Fundraising Analytics
- Campaign Performance Analysis
- Donor Segmentation
- Insight Generation
- Recommendation Development
