# Energy Consumption in Scottish Council Areas (2005–2020)

<p align="right">
  <img src="Asset/Image/Datakirk logo.jpg" alt="Datakirk logo" width="150">
</p>
<h1 align="center">SALAWUDEEN IBRAHIM</h1>

## Introduction

The Scottish Government publishes annual energy consumption data for all 32 council areas in Scotland. This dataset spans the years 2005 to 2020 and includes various energy types—such as electricity, gas, coal, and petroleum products—across multiple consumption sectors including domestic, transport, public sector, and industrial & commercial use.

The dataset includes several energy sources such as:

- **Electricity**
- **Gas**
- **Coal**
- **Manufactured Fuels**
- **Petroleum Products** (e.g., diesel, petrol, heating oil)
- **Bioenergy & Wastes** (where available)

It also categorizes energy consumption by sector, including:

- **Domestic** – energy used in households for heating, lighting, and appliances
- **Agriculture**
- **Rail**
- **Road Transport** – fuel used in road transport and other transportation modes
- **Public Sector** – energy consumed by government and public services
- **Industrial & Commercial** – usage by manufacturing, construction, services, and other businesses


## Objective

The primary objective of this project is to analyze and interpret the Scottish Government’s annual energy consumption data from 2005 to 2020 across all 32 council areas in Scotland. The aim is to gain a deeper understanding of how energy is used across different regions, energy types, and economic sectors.

Specifically, the project seeks to:

- **Identify trends** in energy consumption over time.
- **Compare consumption patterns** across different council areas.
- **Evaluate sector-specific usage** such as domestic, transport, public sector, and industrial & commercial.
- **Assess the impact of policy changes** or external factors (e.g., economic shifts, climate goals) on energy use.
- **Support climate action planning** by providing data-driven insights to local authorities and policymakers.
- **Monitor progress toward sustainability goals**, including Scotland’s commitment to net-zero carbon emissions.

By achieving these goals, the project contributes to a better-informed energy strategy, encourages energy efficiency, and supports the broader transition to a low-carbon economy in Scotland.

## Aim 
This project aims to uncover meaningful insights into Scotland’s energy usage, sectoral demand, and changes over time. The outcome will support policy recommendations, sustainability planning, and energy efficiency assessments.

## Problem Statement

As Scotland moves toward its ambitious climate goals such as achieving net-zero greenhouse gas emissions by 2045—understanding how, where, and why energy is consumed at the local level is critical. However, the challenge lies in:

- **Fragmented data**: Energy consumption data is often large, technical, and difficult to interpret without specialized tools or analysis.
- **Regional disparities**: Different council areas have unique energy usage patterns influenced by geography, infrastructure, population density, and industrial activity.
- **Lack of actionable insights**: Raw data alone does not provide the clear insights needed by policymakers, planners, and stakeholders to implement effective energy efficiency strategies or decarbonization plans.

Without a structured analysis of long-term energy consumption trends across Scotland's 32 council areas, it becomes difficult to:

- Benchmark progress against national energy and climate targets.
- Identify high-consumption areas or sectors requiring intervention.
- Tailor local energy strategies based on real-world data.
- Monitor the effectiveness of policies over time.

## Data Sources

The primary data source used in this project is:

- **Scottish Government Energy Statistics Hub**  
  [https://www.gov.scot/collections/energy-statistics/](https://www.gov.scot/collections/energy-statistics/)  
  This dataset provides detailed local authority-level energy consumption data from 2005 to 2020. It includes breakdowns by fuel type and end-use sector.

Additional supporting references may include:

- UK Department for Energy Security and Net Zero (DESNZ)
- Scottish Environmental Protection Agency (SEPA)
- Local authority climate action reports
- National Records of Scotland (for population and household context)

## Methodology

The following structured methodology was adopted to carry out this energy consumption analysis project. Each step builds upon the previous one to ensure a clean, insightful, and actionable outcome.

📂 Energy Data Analysis Project
├── 📁 1. Convert CSV to Excel Format
│
├── 📁 2. Data Cleaning and Preprocessing
│ ├── 🔍 Check for null or missing values
│ ├── ✏️ Rename columns
│ └── 🧹 Remove:
│ ├── "Scotland" from FeatureName
│ ├── "All" from Energy Type and Sector
│ └── "Industrial & Commercial" combined category
│
├── 📁 3. Exploratory Data Analysis (EDA)
│ ├── 📈 Understand sector and energy trends
│ └── 🧐 Detect anomalies and data patterns
│
├── 📁 4. Visual Analysis and Graphical Insights
│ ├── 📊 Line and bar charts
│ ├── 🌡️ Heatmaps
│ └── 🗺️ Geographic comparisons (council areas)
│
├── 📁 5. Predictive Modeling with Linear Regression
│ ├── 🔢 Train regression model
│ ├── 📉 Test and validate predictions
│ └── 🔮 Forecast next 5 years of energy use
│
├── 📁 6. Dashboard Development
│ ├── 💻 Create interactive views
│ ├── 🎛️ Add filters by region, sector, and fuel type
│ └── 📤 Share insights with stakeholders
│
└── 📁 7. Key Findings and Conclusion
├── ✅ Summarize insights and trends
├── 📌 Highlight areas for improvement
└── 📍 Align with Scotland’s climate goals

### ➤ 1. Convert CSV to Excel Format
The original dataset, provided in CSV format, is first converted to Excel format (`.xlsx`) for easier manipulation, documentation, and integration with visualization tools like Excel, Power BI, or Python (via pandas and openpyxl).

### ➤ 2. Data Cleaning and Preprocessing
Data cleaning is crucial to ensure the dataset is accurate, reliable, and analysis-ready.

- **Check for null or missing values**: Identify and address any gaps or inconsistencies in the data.
- **Rename columns**: Standardize column names for readability and consistency.
- **Remove unnecessary data**:
  - Drop rows where `FeatureName` includes "Scotland" as they represent national aggregates.
  - Exclude generic entries such as "All" from both `Energy Type` and `Energy Consuming Sector`.
  - Remove "Industrial & Commercial" as a combined category to avoid duplication, since the sectors also exist as stand-alone entries.

### ➤ 3. Exploratory Data Analysis (EDA)
Perform an initial examination of the dataset to understand:

- The structure and types of energy consumed
- Distribution across council areas
- Sector-wise and time-based trends
- Any notable anomalies or outliers

### ➤ 4. Visual Analysis and Graphical Insights
Create visualizations (bar charts, line graphs, heatmaps, etc.) to better understand and communicate trends, comparisons, and sectoral shifts in energy consumption.

Visualization tools may include:

- **Excel**

### ➤ 5. Predictive Modeling with Linear Regression
Use **linear regression** to forecast energy consumption trends over the next five years. This involves:

- Selecting key variables (e.g., year, sector, fuel type)
- Training and testing a regression model
- Evaluating the model's performance
- Making future predictions based on historical trends

### ➤ 6. Dashboard Development
Build an interactive **dashboard** to display:

- Council-level and sector-level energy consumption
- Trendlines, comparisons, and filters
- Forecasting results

### ➤ 7. Key Findings and Conclusion
Summarize the major insights derived from the analysis, including:

- Long-term consumption patterns
- Regional and sectoral highlights
- Forecasted energy use and potential areas for intervention



