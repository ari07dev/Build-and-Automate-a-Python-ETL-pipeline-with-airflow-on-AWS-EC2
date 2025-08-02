# 🌤 Data Engineering Project – OpenWeatherMap API + Airflow ETL + AWS

This project demonstrates an **end-to-end data engineering pipeline** that extracts weather data from the **OpenWeatherMap API**, transforms it for analytics, and loads it into AWS cloud storage/warehouse for long-term storage and visualization.

## 🚀 Overview

The pipeline follows the **ETL** approach:

1. **Extract**: Pull raw weather data (current, hourly, and daily forecasts) from the OpenWeatherMap API.
2. **Transform**: Clean, normalize, and enrich the data into analytics-friendly formats.
3. **Load**: Store transformed datasets in AWS S3 (data lake) and load into AWS Redshift or RDS for querying.

Orchestration and automation are handled via **Apache Airflow**, ensuring scheduled, reliable execution.

