# Insurance Claims Analysis Dashboard

## Project Overview

This project explores an insurance dataset containing 58,592 policies, with the aim of identifying patterns in claim activity across customer demographics, vehicle characteristics and regional groups. I developed an interactive dashboard in Microsoft Power BI to summarise key metrics and make the data easier to explore.

## Objectives

- Measure overall policy volume, claim volume and claim rate.
- Compare claim patterns across customer age groups, vehicle age groups, regions, fuel types and customer segments.
- Explore how claim rates vary across vehicle safety ratings.
- Enable users to investigate the data interactively using dashboard filters.

## Tools and Techniques

- **Microsoft Power BI:** Dashboard design, visualisation and interactive reporting.
- **DAX:** Measures for total policies, total claims and claim rate.
- **Power Query:** Data inspection, data-type checks and preparation.
- **Data validation:** Comparison of dashboard metrics against the original workbook.

## Key Metrics

| Metric | Result |
|---|---:|
| Total policies | 58,592 |
| Total claims | 3,748 |
| Overall claim rate | 6.40% |

The claim rate is calculated by dividing the total number of claims by the total number of policies. The dashboard uses these measures to compare both claim volumes and claim rates across different groups.

## Dashboard Features

The dashboard includes KPI cards for the main metrics, charts comparing claim activity across demographic and vehicle-related categories, and interactive filters for exploring the dataset. Claim-rate comparisons provide additional context by accounting for differences in the number of policies within each group.

## Learning Outcomes

This project developed my practical skills in data preparation, DAX measure creation, dashboard design and analytical reporting. It also reinforced the importance of validating calculations and distinguishing between claim volume and claim rate when comparing groups.

## Project Files

- `Insurance claims analysis.pbix` — Interactive Power BI dashboard.
- `Power BI Dashboard.png` — Screenshot preview of the completed report.
## Key Findings

Analysis of 58,592 insurance policies and 3,748 claims revealed several patterns:

- **Customer demographics:** Customers aged 40–49 accounted for the highest number of claims (1,982), while the 60+ age group had the highest observed claim rate at 8.61%, compared with the overall rate of 6.40%.
- **Vehicle age:** Vehicles aged 0–2 years had the highest claim volume (2,666) and claim rate (6.73%) among the vehicle-age groups analysed. The 5+ years group had a lower observed rate, but contained considerably fewer policies.
- **Safety ratings:** Claim rates were relatively similar across the recorded NCAP categories, ranging from 6.24% to 6.68%. The results did not show a clear, consistent relationship between the recorded rating and claim rate.
- **Fuel type and segment:** Petrol vehicles had a claim rate of 6.64%, while CNG vehicles had 6.07%. Segment B2 recorded the highest claim rate among vehicle segments at 6.86%.
- **Regional variation:** Region C18 had the highest observed claim rate (10.74%), whereas Region C8 had the highest number of claims (954). Differences in group sizes should be considered when interpreting these results.

These findings are descriptive and identify patterns for further investigation; they do not establish causation. Smaller groups, particularly the 60+ customer and 5+ years vehicle categories, should be interpreted with care.


# insurance-claims-analysis-dashboard
