---
layout: post
title: Sales Leads Pipeline
description: Data Engineering, SQL and Visualisations project
image: "assets/images/imgsmall/Small_Sales_Pipeline_p2.png"
href: d_salespipeline.html
---

This Sales Leads Pipeline Dashboards project was prepared for the C-level executives, Sales Team (Manager, Sales and Technical Representatives). A streamlined method was necessary to easily track the current leads in the pipeline, along with historical data and conversion rates. The project required change management, UX/UI workshops and significant data manipulation. All company data and any PII is edited out.

Sales Reps initially input the data about their leads in Atlassian Jira for reporting purposes. Data had to be then ingested into Google BigQuery and for this to be possible on a daily basis I used an app from the Jira Marketplace called "BigQuery Connector for Jira". Transformations of the data were then done directly in BigQuery using SQL with several goals in mind: (1) cleaning the data (removing negative values, wrong deal amounts, resolving missing data), (2) creating the necessary KPIs (i.e. pipeline size over time, performance of Sales and Technical Representatives, lead and opportunity closure rates, conversion rates), (3) introducing different time granularity like week and months. Data was then connected with Looker Studio (formerly Google Data Studio) to visualise the KPIs and actual leads. Multiple versions of the dashboards were created after feedback from the UI/UX sessions with the Stakeholders in order to accomplish precision and drive adoption.

The project introduced better sales leads KPIs tracking through the interactive dashboards. This aided in the vertical control of the Sales team, allowing Sales and Technical Representatives, Managers and C-level executives to understand the pipeline and forecast company growth. Monitoring the daily updated information through the dashboards provides a better understanding of next month's financial outcomes and revenue prediction, leading to better informed strategic decisions. The project also increased the visibility into the Sales Representatives performance, improving accountability and motivation.
