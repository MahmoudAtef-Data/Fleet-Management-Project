Fleet Management Project: End-to-End Data Analysis
Project Concept

Fleet Management is the cornerstone of operational efficiency in logistics. This project aims to centralize fragmented data to monitor vehicle performance, maintenance cycles, and overall operational efficiency. The goal is to transform raw data into strategic insights that reduce downtime and operational costs.
End-to-End Methodology

    Data Cleaning & Preparation:

        Initiated the process by cleaning raw datasets in Excel, handling missing values, and standardizing data formats to ensure consistency.

        Utilized SQL for data extraction and preliminary cleaning, ensuring the dataset was optimized for the analysis phase.

    Data Modeling:

        Transformed flat, unstructured tables into a professional Star Schema.

        Defined clear Fact tables (operational events) and Dimension tables (vehicles, drivers, dates), establishing robust relationships to ensure accuracy in multi-dimensional reporting.

    DAX & Business Logic:

        Developed custom DAX measures to calculate complex metrics such as vehicle utilization rates and maintenance intervals.

        Performed rigorous troubleshooting on functions like DATEDIFF to calculate precise operational durations, ensuring that "downtime" was tracked accurately.

    Dashboarding & Visualization:

        Designed an interactive Power BI dashboard to provide a high-level overview of fleet health, with deep-dive capabilities into individual vehicle metrics.

      ### Dashboard Preview

<img src="Freight%20Revenue.jpeg" width="800">

<img src="Fleet%20Cost.jpeg" width="800">

<img src="Vehicle%20Analysis.jpeg" width="800">
Analysis: Strengths & Limitations

    Strengths:

        High scalability due to the optimized Star Schema model.

        Fast dashboard performance and intuitive navigation for stakeholders.

    Limitations:

        Dependence on static datasets, which limits real-time decision-making.

        Current model lacks integration with external environmental data (e.g., fuel price fluctuations, traffic congestion impact).

Future Improvements & Strategic Recommendations

    Predictive Maintenance: Integrate historical breakdown data to build predictive models that forecast vehicle failures before they occur.

    Live Connectivity: Transition from static data sources to live API connections with vehicle telematics for real-time fleet tracking.

    Cost Optimization: Incorporate fuel consumption modeling against route efficiency to identify the most cost-effective operational paths.

Tools & Technologies

    Excel: Data cleaning and initial exploration.

    SQL: Data extraction, querying, and structural preparation.

    Power BI: Data modeling, advanced DAX, and end-to-end visualization.
