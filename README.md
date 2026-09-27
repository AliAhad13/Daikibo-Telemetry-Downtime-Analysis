# Daikibo-Telemetry-Downtime-Analysis


## Project Overview

Analyzed machine telemetry data using Tableau to identify unhealthy-event patterns across factories and device types. Developed an interactive Tableau dashboard to identify high-impact factories and device types for further maintenance investigation.

## Objectives

* Analyze unhealthy machine events across manufacturing facilities.
* Compare factory-level and device-level performance.
* Identify high-impact factory and device combinations.
* Build an interactive Tableau dashboard for data-driven analysis.

## Tools & Technologies

* Tableau
* Data Analysis
* Data Visualization
* Business Intelligence
* Interactive Dashboarding

## Dashboard

![Daikibo Telemetry Dashboard](dashboard.png)

## Key Metrics

| Metric                 | Result |
| ---------------------- | -----: |
| Total Devices          |     36 |
| Total Unhealthy Events |  1,030 |
| Highest Factory Events |    480 |
| Highest Device Events  |    480 |

## Key Insights

* **1,030 unhealthy events** were recorded across **36 devices**.
* **daikibo-factory-seiko** recorded the highest number of unhealthy events with **480 events**.
* **LaserWelder** recorded the highest number of unhealthy events with **480 events**.
* **900 of 1,030 events (87.4%)** were concentrated across daikibo-factory-seiko and daikibo-shenzhen.
* The factory-device heatmap highlighted **Seiko + LaserWelder (480)** and **Shenzhen + LaserCutter (390)** as major concentrations of unhealthy events.

## Dashboard Features

* KPI cards
* Downtime/unhealthy-event analysis by factory
* Unhealthy-event analysis by device type
* Factory × Device Type heatmap
* Factory filter
* Device Type filter
* Interactive dashboard actions

## Project Workflow

**Dataset → Data Exploration → Aggregation → Visualization → Interactive Dashboard → Business Insights**

## Project Outcome

The dashboard provides an interactive view of machine health events and helps identify factories and device types that may require further operational or maintenance investigation.

> Note: The analysis uses the dataset's **Unhealthy** event measure. These values should not be interpreted as confirmed downtime duration unless supported by a separate duration field.
