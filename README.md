# elastic-dashboards
Useful set of Elasticsearch Dashboards

The dashboard has two visualizations.

1. Total Ingestion during specified Time range
2. Ingestion by Day

# How to use this Dashboard

1. Enable stack monitoring in Elasticsearch, this Dashboards uses data of Elasticsearch stack monitoring data
2. Import the Dashboard using Kibana -> Saved Objects (included related objects)
3. After import, we have a Data Ingestion Dashboard and a Kibana Data View created.
4. Open the dashboard and select the time frame that needs to be used for calculating ingest volume. For example 23-Jue-2023 00:00:00.00 to 23-Jue-2023 23:59:59.99
5. If the data range spans across multiple days, the visualization in the bottom will have columns by day.

# Supported Versions

Elasticsearch 8.x and above.

# Screenshots
<img width="1415" alt="Screenshot 2023-07-13 at 11 00 44 PM" src="https://github.com/SquareShiftTech/elastic-dashboards/assets/86217509/0d6b7abb-43ac-422d-8ad3-c7311e207a63">
<img width="1419" alt="Screenshot 2023-07-13 at 11 00 52 PM" src="https://github.com/SquareShiftTech/elastic-dashboards/assets/86217509/8c97fdfe-f3c6-46c9-b504-05fd8278dceb">
