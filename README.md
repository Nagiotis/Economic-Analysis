# Economic Analysis 📊

## Project Overview

The [Economic Analysis](https://github.com/Nagiotis/Economic-Analysis/tree/main) project leverages **Tableau** to analyze **GDP**, **Unemployment**, and **Inflation** metrics over time. It uses **2021 constant values** and the **"International $" method** for GDP calculations. The main objective is to uncover valuable insights into GDP, unemployment, and inflation trends, explore potential correlations, visualize data on maps, and categorize findings effectively.

---

## Dashboards & Metrics 📈

### 1. Main Analysis
- **GDP - Unemployment (%) Correlation:**  
  Examine the relationship between GDP and unemployment rate over time. Metrics are categorized using the **Inflation (%) Meter**:
  - **Deflation:** Inflation rate < 0%.
  - **Low Inflation:** Inflation rate between 0% and 2%.
  - **Normal Inflation:** Inflation rate between 2% and 5%.
  - **High Inflation:** Inflation rate between 5% and 10%.
  - **Inflation Shock:** Inflation rate > 10%.
  - **Null Values:** Indicated in yellow.

- **Countries' GDP:**  
  Investigate GDP trends over time and identify countries with the highest GDP rankings.

---

### 2. Trend Analysis
- **GDP Growth (%), Average Unemployment (%), and Average Inflation (%):**  
  Compare these three key metrics over time to reveal trends.
- Additional charts for detailed metric comparisons:
  - Pairwise metric visualizations for better clarity.
- **Measure Selector:** Simplifies the selection of specific measures.
- **Polynomial Trend Lines:** Enhance trend analysis with precision and sensitivity.

---

### 3. Map Analysis
- **GDP - Inflation (%) Map:**  
  Visualize GDP changes on a map, with **Inflation rates** categorized using the same color scheme as in **Main Analysis**.
- **GDP Growth (%) Map:**  
  - **Negative Growth:** Indicated in red.  
  - **Positive Growth:** Indicated in green.  
  - **Stable Growth:** Indicated in purple.  
  - For the year 2000, all values are purple as it marks the baseline.
- **Unemployment (%) Map:**  
  Classified using the **Unemployment (%) Meter**:
  - **Inflation Check:** Unemployment rate < 3%. Low unemployment rates might signal wage pressures, labor shortages, and product price increases.
  - **Normal Unemployment:** Unemployment rate between 3% and 8%.
  - **Recession Check:** Unemployment rate > 10%. High unemployment rates often indicate recessionary environments.

---

## Interactive Features 🛠️

- **Filters:** Enables detailed data exploration.  
- **Navigation Buttons:** Easily switch between **Main Analysis**, **Trend Analysis**, and **Map Analysis** dashboards.  
- **Key Performance Indicators (KPIs):**  
  - Includes **Total GDP**, **Average Unemployment (%)**, and **Average Inflation (%)**.
  - KPIs are **independent of year selection**, enabling easy comparison between overall KPIs and specific charted values.

---

## Key Insights 🔍

### 1. Main Analysis
- **GDP Trends:**  
  The United States held the highest GDP values for most of the recorded period, but China surpassed the US between 2016 and 2023. India, ranking third in GDP in 2023, is showing promising growth.  
  *Note:* All GDP values are calculated using the **"International $" method** and **2021 constant values**.
  
- **Unemployment and GDP Correlation:**  
  Countries with **Unemployment rates** between **3%-10%** generally perform better in GDP, especially in the **4%-8%** range.  
  - In 2023, the **Top 10 GDP countries** had an average unemployment rate of **6.41%** and an average inflation rate of **3.89%**.

---

### 2. Trend Analysis
- **Global Unemployment Trends:**  
  The global **Average Unemployment (%)** is around **8%**, but in 2023 it dropped to its lowest value of **6.77%**.

- **GDP Growth and Unemployment:**  
  - During periods of steep GDP growth decline (e.g., 2009 and 2020), **Average Unemployment (%)** was observed to decrease in the preceding years.  
  - GDP typically declined first (e.g., in 2009 and 2020), followed by an uptick in unemployment rates.

- **Inflation and GDP Interaction:**  
  - In 2008, **Average Inflation (%)** spiked drastically, followed by a sharp GDP decline in 2009 during the financial crisis.  
  - During the 2020 pandemic, inflation increased after a significant GDP drop.

- **Inflation and Unemployment Comparison:**  
  - Historically, **Average Inflation (%)** has been lower than **Average Unemployment (%)**, but this dynamic shifted around 2020.

- **China's Divergence:**  
  China exhibited distinctive trends compared to other **Top 10 GDP countries** and global averages.

---

### 3. Map Analysis
- The financial crisis in 2008 and the 2020 pandemic significantly impacted global economies.  
  - In both events, **GDP Growth (%)** turned negative across many countries, especially in Europe.  
  - **Unemployment (%)** increased, and deflationary pressures were noted during these periods.  
  - The pandemic appeared to have a more globally widespread negative impact.
- **South Africa** has had a persistently high **Unemployment (%)** rate over an extended period.  
- **China** maintained positive GDP Growth (%) throughout, despite experiencing low inflation and occasional deflationary pressures.  
- **Egypt, Turkey, Iran, and Pakistan** have faced prolonged high inflationary pressures.  
- **Indonesia** has demonstrated economic improvements since 2010, with significant growth from 2015 to 2023.

---

## Notes
- In the **GDP - Unemployment (%) Correlation** chart (Main Analysis) and **Unemployment (%) Map** (Map Analysis), tooltips display both **Inflation (%) Meter** and **Unemployment (%) Meter**.  
  This dual view enables further investigation into whether high inflation correlates with low unemployment in affluent countries. These insights could tie into the **Penn Effect** and the **Balassa-Samuelson Effect**.

---

## Datasets / Data Sources 🌱
- The [`gdp-worldbank.csv`](https://github.com/Nagiotis/Economic-Analysis/blob/main/gdp-worldbank.csv) dataset used in this project originates from the [Gross domestic product (GDP)](https://ourworldindata.org/grapher/gdp-worldbank) data, hosted by *Our World in Data*. It provides historical GDP data for countries worldwide, compiled from multiple sources by the World Bank (2025) with minor processing by *Our World in Data*.  

For citation and licensing details, refer to the official [Citation Guide gdp-worldbank.csv](https://ourworldindata.org/grapher/gdp-worldbank#reuse-this-work).

- The [`inflation-of-consumer-prices.csv`](https://github.com/Nagiotis/Economic-Analysis/blob/main/inflation-of-consumer-prices.csv) dataset used in this project comes from the [Inflation of Consumer Prices](https://ourworldindata.org/grapher/inflation-of-consumer-prices) data, hosted by *Our World in Data*. It provides historical inflation data sourced from *International Monetary Fund* (via World Bank) (2025) – processed by *Our World in Data*.

For citation and licensing details, refer to the official [Citation Guide inflation-of-consumer-prices.csv](https://ourworldindata.org/grapher/inflation-of-consumer-prices#reuse-this-work).
  
- The [`unemployment-rate.csv`](https://github.com/Nagiotis/Economic-Analysis/blob/main/unemployment-rate.csv) dataset used in this project comes from the [Unemployment Rate](https://ourworldindata.org/grapher/unemployment-rate) data, hosted by *Our World in Data*. It provides historical inflation data sourced from *International Labour Organization* (via World Bank) (2025) – processed by Our World in Data

For citation and licensing details, refer to the official [Citation Guide unemployment-rate.csv](https://ourworldindata.org/grapher/unemployment-rate#reuse-this-work).

---

## Future Exploration Ideas 💡
- Combine primary energy consumption and electricity generation analysis to examine their impacts on economic activity. Investigate potential correlations, such as **GDP vs. Primary Energy Consumption**.  
- Further breakdown energy sources (e.g., fossil fuels, solar, hydroelectric) to analyze their share in primary energy consumption and electricity generation. Look for correlations or diverse impacts.  
- Integrate Exports and Imports data for each country and analyze their relationships with GDP.
