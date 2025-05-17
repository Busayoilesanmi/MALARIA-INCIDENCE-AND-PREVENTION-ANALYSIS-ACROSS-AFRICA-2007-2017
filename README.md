# MALARIA INCIDENCE AND PREVENTION ANALYSIS ACROSS AFRICA (2007-2017)

[Introduction](#Introduction)

[Objective](#Objective)

[Story of Data](#StoryofData)

[Data Splitting and Preprocessing](#DataSplittingandPreprocessing)

[Pre-Analysis](#Pre-Analysi)

[In-Analysis](#In-Analysis)

[Post-Analysis and Insights](#Post-AnalysisandInsights)

[Data Visualizations & Charts](#DataVisualizations&Charts)

[Recommendations and Observations](#RecommendationsandObservations)

[Conclusion](#Conclusion)

[References & Appendices](#References&Appendices)

## Introduction
This dashboard presents a comprehensive visual analysis of malaria incidence trends and public health interventions across Africa from 2007 to 2017. It leverages various data visualization tools in Microsoft Excel like line graphs, bar charts, and pie charts, to explore patterns, correlations, and effectiveness of malaria control measures over time and across different African countries.

### Objective of the Project

The objective of this analysis is to investigate the incidence and trends of malaria across African countries over the period of 2007 to 2017. The goal is to assess the impact of public health interventions including insecticide-treated nets (ITNs), sanitation, clean water access, and antimalarial drug distribution.

### Problem Being Addressed

Malaria remains a major public health issue in Africa, with substantial health and economic burdens. This analysis aims to identify patterns and effective prevention strategies to support evidence-based health planning and resource allocation.

### Key Datasets and Methodologies

Datasets: Malaria in Aftrica on kaggle.com (https://www.kaggle.com/datasets/lydia70/malaria-in-africa)

Methodologies: Use of Excel functions including PivotTables, line/bar/pie charts,

## Story of Data

### Data Source

The data was presumably sourced from kaggle.com 
Link to the the dataset: (https://www.kaggle.com/datasets/lydia70/malaria-in-africa)

### Data Collection Process

Data was gathered via national surveys, health monitoring systems, and institutional reporting over a span of 11 years.

### Data Structure

Rows: Represent individual records for years or country-wise statistics.

Columns: Capture malaria cases, net usage (%), sanitation metrics, water access, drug distribution, rural/urban demographics.

### Important Features and Their Significance

Malaria Incidence: Measures disease burden.

Insecticide-Treated Net Usage: Core preventative intervention.

Sanitation/Clean Water: Environmental factors influencing disease.

Drug Distribution: Reflects treatment accessibility.

Urban vs. Rural Areas: Socio-geographical determinants.

### Data Limitations or Biases

Regional reporting inconsistencies.

Limited granularity at sub-national levels.

Missing or delayed updates in some health intervention indicators.

## Data Splitting and Preprocessing

### Data Cleaning

* Removed duplicate records

* Standardized units across datasets

* Corrected inconsistencies (e.g., percentage rounding)

### Handling Missing Values

Used interpolation and mean substitution for numerical gaps

### Data Transformations

Calculated percentage impact of variables

Generated incidence rates normalized by population

Created binary indicators for intervention effectiveness

### Data Splitting

Dependent Variable: Malaria Cases

Independent Variables: ITN usage, sanitation levels, clean water access, drug distribution percentage, urban/rural share

Industry Context
The data used in the malaria dashboard directly serves the public health industry, particularly stakeholders engaged in disease surveillance, vector control, healthcare delivery, and resource allocation across Africa. Each dataset element offers valuable insights that can guide national and international health interventions.

### Stakeholders

Ministries of Health (MoH): Primary bodies responsible for national malaria surveillance and intervention policy implementation. It use the insights to allocate national resources efficiently, develop targeted malaria eradication programs, and meet public health goals.

World Health Organization (WHO): Provides global guidance, technical support, and funding for malaria control programs. It uses regional data to shape continental strategies, monitor progress toward Sustainable Development Goals (SDGs), and produce annual malaria reports.

Non-Governmental Organizations (NGOs): Malaria No More, PATH, The Global Fund. It delivers on the ground programs, awareness campaigns, and distribute resources like ITNs and antimalarial drugs. It Identify where interventions are most needed, justify funding requirements, and demonstrate program impact.

Public Health Policy Researchers and Analysts: Academics and consultants analyzing trends, evaluating policy effectiveness, and recommending improvements.It extract causal relationships, publish findings, and influence both national and international health policies.

Affected Communities and Local Leaders: It participate in prevention strategies, educate residents, and help in community-level implementation. It advocate for better infrastructure, support behavior change, and ensure equitable distribution of resources.

### Value to the Industry

This analysis informs policy-level decisions, supports resource optimization, and guides targeted intervention planning to improve malaria control outcomes.

## Pre-Analysis

### Identify Key Trends

* Malaria incidence steadily declined from 208 cases in 2007 to 176 in 2017

* Strong alignment between higher ITN usage and reduced cases

* Clean water and sanitation improvements show measurable reductions in malaria incidence

### Potential Correlations

* Drug distribution coverage appears inversely correlated with malaria cases

* Rural area exposure shows significantly higher impact than urban regions

### Initial Insights

* The year 2007 had the highest average malaria incidence

* Congo, Dem. Rep. reported the highest cumulative malaria cases

## In-Analysis

### Unconfirmed Insights

* Urban area impact appears less significant despite population density

* Drug distribution at 35.1% coverage had the lowest malaria incidence (551 cases)

### Recommendations

* Scale up ITN distribution in rural and high-incidence countries

* Increase sanitation and clean water coverage, especially in poorly served regions

* Prioritize rural-specific intervention frameworks

### Analysis Techniques Used in Excel

* PivotTables for geographical aggregation

* Bar and pie charts to show impact distribution

* Line charts to reveal long-term trends

* Cross-tab analysis for variable comparisons (e.g., net usage vs. incidence)

## Post-Analysis and Insights

### Key Findings

* A general downward trend in malaria cases over the decade

* Maximum net usage (62%) corresponded to the lowest malaria cases (9,385,132)

* Highest rural exposure (29%) associated with 83.8 malaria cases

* Antimalarial drug distribution correlates with steep reduction in cases

### Comparison with Initial Findings

* Initial expectations about net and drug efficacy were validated

* Urban areas had marginally less influence on malaria outcomes than expected

## Data Visualizations & Charts

![Dashboard5](https://github.com/user-attachments/assets/7b34675a-f1c1-453e-bcd5-f79de0f3dd3a)

### Link to Excel Document:

https://drive.google.com/drive/folders/1fFoToa0S9pa_6TPVrWM16thAbi6teK58?usp=drive_link

### Charts and Graphs

Line Chart: Malaria incidence trend (2007-2017)

Bar Charts:

ITN usage vs. malaria cases

Drug distribution vs. incidence

Top 6 countries with highest cases

Pie Charts:

Urban and rural area impact

Bar Graphs:

Sanitation and clean water impact on incidence

### Explanation of Visualizations

* Line Chart: Malaria Incidence Trend (2007–2017)

Purpose: Visualizes the year-over-year trend in malaria cases across Africa.

Insight: Shows a steady decline from 208 cases in 2007 to 176 cases in 2017, indicating the effectiveness of long-term intervention strategies.

* Bar Chart: ITN Usage vs. Malaria Cases

Purpose: Compares percentage of insecticide-treated net (ITN) usage with the number of malaria cases.

Insight: A negative correlation is apparent; higher net usage corresponds to fewer malaria cases.

* Bar Chart: Drug Distribution vs. Malaria Incidence

Purpose: Displays the effect of drug coverage (% of population receiving antimalarial drugs) on malaria incidence.

Insight: Incidence drops significantly even at moderate drug distribution levels (~35%), emphasizing the critical role of accessible treatment.

* Bar Chart: Top 6 Countries with Highest Malaria Cases

Purpose: Highlights countries with the largest cumulative malaria burden during the analysis period.

Insight: Congo (DRC), Nigeria, and Mozambique consistently top the list, confirming the need for concentrated interventions in these nations.

* Pie Chart: Urban vs. Rural Area Impact

Purpose: Illustrates the distribution of malaria impact based on location.

Insight: Rural areas account for a disproportionately higher share of cases (~29%), due to poor infrastructure, healthcare access, and water management.

* Bar Graph: Sanitation and Clean Water Impact

Purpose: Demonstrates how access to clean water and improved sanitation correlates with malaria incidence.

Insight: Areas with better WASH (Water, Sanitation, and Hygiene) indicators exhibit markedly lower malaria rates, confirming the indirect but vital role of environmental interventions.

## Recommendations and Observations

### Actionable Insights

* Expand ITN distribution in top-affected countries

* Improve water and sanitation systems in rural regions

* Enhance drug accessibility, even modest distribution levels yield strong results

### Optimizations or Business Decisions

* Prioritize interventions in Congo, Mozambique, and Nigeria

* Increase public health education campaigns in rural zones

### Unexpected Outcomes

* High urban density didn’t correlate with higher malaria incidence

* Even low drug distribution percentages showed significant improvements

## Conclusion

### Key Learnings

* Integrated health interventions (nets, water, sanitation) are key to reducing malaria

* Rural demographics play a critical role in shaping malaria exposure

* Strategic use of Excel dashboards enables data-driven decision-making

### Limitations

* Data availability and completeness vary across countries

* Lack of seasonal or climate-related data limits environmental correlation analysis

### Future Research

* Include meteorological data to assess climate impact

* Explore behavioral and educational factors in malaria prevention

* Evaluate cost-effectiveness of each intervention strategy

## References & Appendices

### References

Dataset - https://www.kaggle.com/datasets/lydia70/malaria-in-africa

Microsoft Excel Documentation- https://docs.google.com/spreadsheets/d/1b4wMG-lN_H9MhSY7nv1y2fzbDlJI6ih8/edit?usp=drive_link&ouid=104478848167416604596&rtpof=true&sd=true

Screenshot- https://drive.google.com/file/d/11dZR27T9lbKdKHTe6XET9qh_S5-kboJO/view?usp=drive_link

Peer-reviewed public health journals

### Appendices

Raw Excel Tables

Pivot Table Summaries

Dashboard Image (attached)

Advanced Formulas and Calculation Logic


