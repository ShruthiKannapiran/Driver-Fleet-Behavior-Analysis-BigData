# Driver-Fleet-Behavior-Analysis-BigData

A Big Data–driven project analyzing driver and fleet behavior to detect risks, improve efficiency, and enable predictive maintenance with machine learning and dashboards.

# Project Overview: Driver & Fleet Behavior Analysis

This project analyzes truck telematics, mileage, and driver behavior data using a Big Data ecosystem combined with machine learning models. The objective is to proactively identify unsafe driving behavior, predict maintenance risks, and optimize fleet performance.


# Tools & Technologies

Data Storage & Processing: HDFS, Hive, Impala, Spark, Pig
Machine Learning & Analytics: Python, R (K-Means, Random Forest, Regression)
Visualization: Tableau, Power BI

# Project Flow

Data is ingested from telematics, mileage, and driver logs into HDFS via Flume, then processed with Hive, Impala, Spark, and Pig for cleaning, querying, and feature engineering. The refined data is used in Python/R machine learning models (K-Means, Random Forest, Regression) and visualized in Tableau/Power BI dashboards for actionable insights.

Phase 1 – Data Sources

Telematics logs (overspeeding, harsh braking, idling events)
Vehicle mileage and fuel consumption data
Driver performance logs

Phase 2 – Data Ingestion & Storage

Data ingested using Flume for real-time streaming.
Stored in HDFS (Hadoop Distributed File System) for scalability and fault tolerance.

Phase 3 – Processing & Analysis

Hive & Impala: Queried large datasets to compute event counts, driver risk metrics, and city-level trends.
Spark & Pig: Cleaned, transformed, and aggregated telematics data.
Python & R: Applied ML algorithms for predictions and classifications:
K-Means Clustering → Classified drivers into Low, Medium, High risk.
Random Forest → Predicted maintenance issues.
Regression (R) → Modeled MPG (fuel efficiency) based on mileage & idling.

Phase 4 – Visualization

Built interactive dashboards in Tableau and Power BI to show:
High-risk drivers (risk ≥ 7.0)
City-wise abnormal driving event heatmaps
MPG vs. idling & mileage performance
Maintenance risk per truck model
Cluster-based driver segmentation

Phase 5 – Integration

Insights designed to feed into:
Insurance alerts for high-risk drivers
Fleet management systems for proactive maintenance scheduling
Operational dashboards for daily monitoring

Phase 6 – Outcomes

Early identification of unsafe driver behavior (reducing accidents & insurance costs).
Predictive insights into fuel efficiency and maintenance risks.
Data-driven decision-making for fleet health management.
Actionable dashboards for managers to monitor performance and intervene quickly.


# Key Business Questions Addressed

High-risk drivers: Which drivers have a risk factor ≥ 7.0?
Fuel efficiency prediction: Can truck MPG be predicted from mileage and idling behavior?
Maintenance risk detection: Which truck models are most likely to face maintenance issues?
Driver classification: Can we segment drivers into Low, Medium, High risk clusters?
Operational inefficiencies: Where do abnormal driving events occur most frequently across cities?

# Machine Learning Insights

K-Means Clustering: Classified drivers into risk categories → enabling targeted training, safety interventions, and insurance tiering.
Random Forest: Predicted truck maintenance risks → helping plan proactive servicing and reduce downtime.
Regression (R): Modeled MPG performance → showing that longer idle durations and high mileage reduce efficiency.

# Visualization

Interactive dashboards built with Tableau and Power BI present:
Lists of risky drivers
City-wise abnormal driving event patterns
Fuel efficiency and idling trends
Truck models with highest predicted maintenance risks
Driver segmentation by cluster

# Project Outcomes

Reduced insurance and compliance risks through early detection of unsafe driver behavior.
Improved operational efficiency with predictive fuel and maintenance analysis.
Delivered scalable ML-driven insights to support data-driven fleet management.
Provided actionable dashboards for real-time monitoring and decision-making.
