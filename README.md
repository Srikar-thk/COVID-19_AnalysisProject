# COVID-19 Data Exploration and Dashboard Development

## Overview

The COVID-19 Data Exploration and Dashboard Development project provides critical insights into the global impact and spread of COVID-19 through detailed analytics. This project facilitates clear and interactive visibility into infection rates, mortality statistics, vaccination progress, and trends over time. These insights support informed decision-making by healthcare authorities, policymakers, and the general public.

## Purpose

The project's primary objective was to create interactive dashboards that accurately depict essential metrics such as global case totals, death rates, infection rates relative to population size, and vaccination progress. These dashboards enable rapid assessment of COVID-19 trends and comparative analysis between regions, aiding targeted interventions and policy-making.

## Problems Addressed

The project effectively:

* Delivered precise global and regional COVID-19 case and mortality tracking.
* Enabled detailed visualization of infection rates relative to population.
* Provided insights into vaccination efforts and their effectiveness.

## Technology Stack

* **SQL:** Utilized for complex data queries involving aggregation, conditional logic, window functions, joins, temporary tables, and Common Table Expressions (CTEs).
* **Excel:** Employed for initial data cleaning, including formatting cells, addressing NULL values, filtering datasets, and exploratory analysis.
* **Tableau:** Selected for creating clear, interactive visualizations that improve stakeholder understanding.

## Project Execution

### Step-by-Step Technical Process

1. **Data Acquisition and Domain Understanding**

   * Collected COVID-19 datasets and analyzed data attributes including total cases, deaths, vaccinations, and population metrics.

2. **SQL Query Development and Data Extraction**

   * Developed comprehensive SQL queries to extract and analyze critical data, including:

     * **Aggregation Queries:** Calculated total cases, total deaths, and mortality rates globally and by region.
     * **GROUP BY Queries:** Used to aggregate and summarize data by continent, country, and date, facilitating regional comparisons and trend analysis.
     * **Conditional Logic and Joins:** Leveraged conditional logic and join operations to correlate vaccination data with infection and population metrics.
     * **Window Functions:** Employed to calculate rolling totals of vaccinations, providing insights into vaccination progress over time.
     * **CTEs and Temporary Tables:** Created temporary structures to simplify complex calculations and enhance query readability and performance.

3. **Data Preparation and Analysis in Excel**

   * Imported and cleaned SQL query outputs in Excel, performing:

     * Cell formatting to enhance data readability and presentation.
     * NULL value treatment through data cleaning techniques.
     * Initial data filtering and exploratory analysis to verify accuracy and completeness.

4. **Interactive Dashboard Development with Tableau**

   * Designed intuitive dashboards in Tableau to clearly present insights through:

     * Global summary metrics, including overall cases, deaths, and death percentage.
     * Bar charts for visualizing total deaths by continent.
     * Line charts illustrating monthly population infection rates.
     * Filled maps for visualizing country-specific infection rates.

5. **Dashboard Validation and User Interaction**

   * Conducted extensive validation and integrated interactive features in Tableau dashboards, ensuring data accuracy, responsiveness, and user-friendly interaction.

## Key Findings

* Clearly identified Europe and North America as regions heavily impacted by COVID-19 deaths.
* Highlighted high infection rates in the United States, the United Kingdom, and India relative to their populations.
* Provided comprehensive visualization of vaccination progress, emphasizing the correlation between vaccinations and reduced infection rates.

## Real-world Implications

This analysis empowers health authorities and policymakers to:

* Effectively monitor and respond to COVID-19 outbreaks.
* Implement precise and targeted public health strategies.
* Enhance public awareness and communication of COVID-19 risks and preventive measures.
* Optimize resource allocation and improve emergency preparedness through informed, data-driven decisions.
