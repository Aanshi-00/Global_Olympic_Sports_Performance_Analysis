# Global Olympic Sports Performance Analysis

## Project Overview
**Global Olympic Sports Performance Analysis** is a Tableau-based data analytics project exploring Olympic medal performance, athlete participation, regional medal-efficiency measures, host-country medal patterns, and comparisons across investment categories.

The project presents Olympic data through charts, interactive dashboards, and a Tableau Story so users can explore patterns without manually reviewing raw CSV records.

## Project Objectives
- Compare total medal counts across countries.
- Examine gold, silver, and bronze medal distributions.
- Explore changes in recorded medal totals over time.
- Analyze athlete participation by sport and gender distribution.
- Compare the available regional medal-efficiency measure.
- Explore host-country medal totals and investment-category comparisons.
- Present findings through dashboards and a guided Tableau Story.

## Datasets
The project uses four institutional CSV datasets:

| Dataset | Rows | Fields | Description |
|---|---:|---:|---|
| `alltime_country_rankings.csv` | 60 | 13 | Country rankings and summary measures, including country, NOC code, region, Games entered, and medal totals. |
| `athletes.csv` | 8,000 | 26 | Athlete information, including identifiers, gender, age, and sport-related fields. |
| `games_summary.csv` | 18 | 10 | Olympic Games details such as year, host city, host country, and season. |
| `medal_results.csv` | 910 | 19 | Medal-result records and associated Games/country information. |

These counts describe each file individually; they are not a count of unique records across all connected datasets.

## Tools and Technologies
- **Tableau Desktop / Tableau Public** — visualizations, dashboards, and Story.
- **CSV files** — source data.
- **Tableau data relationships** — connect relevant fields across datasets.
- **Tableau calculated field** — `Unique Athletes`.
- **GitHub** — project files and documentation.

The CSV datasets are connected directly to Tableau. A separate SQL database or Snowflake warehouse is not used in this implementation.

## Visualizations
The workbook contains eight visualizations:
1. **Top Countries by Total Medals**
2. **Gold, Silver & Bronze Comparison**
3. **Olympic Medal Trends by Year**
4. **Athlete Gender Analysis**
5. **Athlete Participation by Sport**
6. **Average Medal Efficiency by Region**
7. **Average Medal Count by Investment Category**
8. **Medal Performance by Host Country**

## Dashboards
### 1. Global Olympic Performance Analysis
Combines country medal rankings, yearly medal trends, and gold/silver/bronze comparisons. Year and season filters support exploration of different time periods and Olympic seasons.

### 2. Athlete & Regional Insights
Combines sport-wise athlete participation, gender distribution, and regional medal-efficiency comparisons. Filters include year, season, and sport, where applicable.

### 3. Host & Investment Insights
Compares medal totals associated with host countries and average medal counts across the available investment categories. Filters allow exploration by year, season, and sport, where applicable.

## Tableau Story
The workbook includes a four-part Story:
1. **Global Olympic Games: Performance & Trends** — introduces country rankings, medal categories, and yearly trends.
2. **Athlete & Regional Insights** — explores participation, gender distribution, and regional measures.
3. **Host Advantage & Investment Patterns** — compares host-country performance and investment categories.
4. **Key Findings & Conclusion** — summarizes the main patterns and notes limitations.

## Key Observations
- The United States and China appear among the leading countries in the displayed total-medal ranking.
- Recorded medal totals fluctuate across the years represented in the dataset.
- Sport participation and gender-distribution charts provide an overview of athlete representation.
- The regional-efficiency chart highlights differences in the measure used in the workbook.
- Host-country and investment-category charts support comparisons, but do not by themselves prove that hosting or investment causes medal success.

These observations describe the displayed analysis and should be interpreted in the context of the supplied datasets, field definitions, filters, and time coverage.

## Repository Contents
The repository includes project documentation, datasets, and the Tableau workbook. Depending on the uploaded folder structure, it may contain:
- Project planning and documentation PDFs.
- The four source CSV datasets.
- `Global_Olympic_Performance_Analysis.twbx` — packaged Tableau workbook.

## How to View the Project
1. Clone or download this repository.
2. Open `Global_Olympic_Performance_Analysis.twbx` in Tableau Desktop.
3. If Tableau requests file locations, reconnect the data sources to the CSV files included in the repository.
4. Open the worksheets, dashboards, and Story points to explore the analysis.
5. Use available filters to investigate different years, seasons, and sports.

A compatible Tableau installation may be required to open or edit the packaged workbook.

## Limitations
- Findings depend on the supplied datasets and the definitions of their fields and measures.
- Investment categories should not be interpreted as verified financial expenditure unless confirmed by the source data.
- Visual comparisons show patterns and associations; they do not establish causation.
- A separate web application is not included in the current Tableau implementation.

## Future Scope
- Add more recent and consistently documented Olympic datasets.
- Include deeper sport-wise and country-wise comparisons.
- Validate and document the definitions of medal-efficiency and investment measures.
- Add statistical analysis to test patterns observed in the visualizations.
- Explore a web-based interface for sharing the dashboards.

## Project Links
- **GitHub Repository:** https://github.com/Aanshi-00/Global-Olympic-Sports-Performance-Analysis
- **Dataset Folder:** https://drive.google.com/drive/folders/1FUnbqjwH1Apyb2NjwW-D-NIEONIEL1ig
- **Demonstration video link:** https://drive.google.com/file/d/1bwXhvH2OnmpVhI8SPT0YyffthtNTwLma/view?usp=drivesdk

## Project Information
- **Project Name:** Global Olympic Sports Performance Analysis
- **Team ID:** EN25CS3010016
- **Date:** 28 October 2026

---
*Academic data analytics project using Tableau and Olympic datasets.*
