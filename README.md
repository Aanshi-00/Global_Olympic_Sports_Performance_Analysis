# Global Olympic Sports Performance Analysis

**Team ID:** EN25CS3010016  
**Project Date:** 28 October 2026  
**Platform:** Tableau Public  
**Project Type:** Olympic sports data analytics and visualization

## Project Overview

Global Olympic Sports Performance Analysis is a Tableau-based analytics project exploring Olympic medal performance, athlete participation, regional medal-efficiency patterns, host-country results, and comparisons across investment categories.

The project combines four institutional CSV datasets and presents the analysis through eight visualizations, three interactive dashboards, and a four-part Tableau Story. It aims to make historical sports data easier to explore and support evidence-informed analysis for sports strategists, analysts, and media storytellers.

## Objectives

- Compare total medal counts across countries.
- Examine gold, silver, and bronze medal distributions.
- Explore medal trends across years and Olympic seasons.
- Analyze athlete participation by sport and gender.
- Compare the recorded medal-efficiency measure across regions.
- Explore medal performance by host country.
- Compare medal results across the dataset's investment categories.
- Use interactive filters to explore years, seasons, and sports.

## Datasets

The project uses the following four institutional CSV datasets:

| Dataset | Description | Size |
|---|---|---|
| `alltime_country_rankings.csv` | Country-level historical rankings and medal summary fields, including country, NOC code, region, games entered, and total gold | 60 rows, 13 fields |
| `athletes.csv` | Athlete records and attributes such as athlete ID, name, gender, age, sport, and NOC code | 8,000 rows, 26 fields |
| `games_summary.csv` | Olympic Games summary information, including year, host city/country, and season | 18 rows, 10 fields |
| `medal_results.csv` | Medal-result records, including year, host, country/NOC, season, and medal details | 910 rows, 19 fields |

**Combined file row count:** 8,988 rows across the four CSV files (the sum of the individual file rows, not a count of unique records).

The CSV files were connected directly in Tableau, with relationships configured to support the analysis. No Snowflake warehouse or SQL views were used.

### Dataset folder

Google Drive folder containing the project datasets:  
https://drive.google.com/drive/folders/1FUnbqjwH1Apyb2NjwW-D-NIEONIEL1ig

## Technology Stack

- **Data source:** CSV files
- **Data visualization and analytics:** Tableau
- **Calculated field:** `Unique Athletes`
- **Interactive controls:** Year, Season, and Sport filters where applicable
- **Repository:** GitHub

## Visualizations

The workbook contains eight visualizations:

1. **Top Countries by Total Medals** — compares countries by total medal count.
2. **Gold, Silver & Bronze Comparison** — compares medal types across leading countries.
3. **Olympic Medal Trends by Year** — displays changes in recorded medal totals over time.
4. **Athlete Participation by Sport** — compares unique athlete counts across sports.
5. **Athlete Gender Analysis** — shows the gender distribution in the athlete dataset.
6. **Average Medal Efficiency by Region** — compares the recorded medal-efficiency measure across regions.
7. **Medal Performance by Investment Category** — compares the displayed measure for High, Medium, and Low investment categories.
8. **Medal Performance by Host Country** — compares medal totals associated with host countries.

## Tableau Public Dashboards

### Dashboard 1 — Global Olympic Performance Analysis

URL: https://public.tableau.com/views/Global_Olympic_Performance_Analysis-dashboard1/GLOBALOLYMPICPERFORMANCEANALYSIS?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

Includes:
- Top Countries by Total Medals
- Olympic Medal Trends by Year
- Gold, Silver & Bronze Comparison
- Year and Season filters

### Dashboard 2 — Athlete & Regional Insights

URL: https://public.tableau.com/views/Global_Olympic_Performance_Analysis-dashboard2/ATHLETEREGIONALINSIGHTS?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

Includes:
- Athlete Participation by Sport
- Athlete Gender Analysis
- Average Medal Efficiency by Region
- Year, Season, and Sport filters

### Dashboard 3 — Host & Investment Insights

URL: https://public.tableau.com/views/Global_Olympic_Performance_Analysis-dashboard3/HOSTINVESTMENTINSIGHTS?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

Includes:
- Medal Performance by Investment Category
- Medal Performance by Host Country
- Year, Season, and Sport filters

## Tableau Story

### Story 1 — Global Olympic Games: Performance & Trends

URL: https://public.tableau.com/views/Global_Olympic_Performance_Analysis-story1/Story1GlobalOlympicGamesPerformanceTrends?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

Explores country medal rankings, medal-type comparisons, and medal trends over time.

### Story 2 — Athlete & Regional Insights

URL: https://public.tableau.com/views/Global_Olympic_Performance_Analysis-story2/Story2AthleteRegionalInsights?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

Explores sport-wise athlete participation, gender representation, and regional medal-efficiency patterns.

### Story 3 — Host Advantage & Investment Patterns

URL: https://public.tableau.com/views/Global_Olympic_Performance_Analysis-story3/Story3HostAdvantageInvestmentPatterns?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

Compares host-country medal performance and the measure across investment categories. These comparisons show patterns in the available data; they do not prove that hosting or investment causes medal success.

### Story 4 — Key Findings & Conclusion

URL: https://public.tableau.com/views/Global_Olympic_Performance_Analysis-story4/Story4KeyFindingsConclusion?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

Summarizes the key takeaways, interpretation limits, and overall conclusion.

## Project Demonstration

Demonstration video: https://drive.google.com/file/d/1bwXhvH2OnmpVhI8SPT0YyffthtNTwLma/view?usp=drivesdk

## How to Explore the Project

1. Open any dashboard URL above.
2. Use the available Year, Season, and Sport filters to change the displayed data.
3. Compare countries, medal types, sports, regions, host countries, and investment categories.
4. Open the Story URLs to follow the analysis in a guided sequence.

## Key Takeaways

- The dashboards make country-level medal comparisons easier to explore.
- Medal-type and year-based views help reveal differences and changes in recorded results.
- Athlete and regional views provide context on participation and the dataset's medal-efficiency measure.
- Host-country and investment-category views offer additional comparisons for further investigation.

## Limitations

- Findings depend on the coverage, structure, and definitions in the supplied datasets.
- The investment-category visualization should not be interpreted as proof of a causal relationship between spending and medals.
- Host-country comparisons alone do not establish that hosting caused a country's medal performance.
- This is a Tableau analytics and visualization project; a separate Flask web application is not included in the current implementation.

## Future Scope

- Add more recent, verified Olympic data when suitable datasets become available.
- Expand analysis with additional sport, country, and time-period comparisons.
- Improve documentation of metric definitions and data-preparation steps.
- Consider a web-based interface for presenting the dashboards in a unified project portal.

## GitHub Repository

https://github.com/Aanshi-00/Global-Olympic-Sports-Performance-Analysis
