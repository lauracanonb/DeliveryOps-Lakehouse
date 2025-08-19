# DeliveryOps-Lakehouse
End-to-end data engineering project that simulates a food delivery company using Azure and databricks.it integrates Batch and streaming data into a Lakehouse architecture (Bronze, Silver, Gold), applies data quality checks, handles CDC and SCD2, Delivers Kpis through Power Bi dashboards 

Business context:

A delivery company wants to:
-Monitor operacional Kpis: delivery times, courier, utilization, cancellations, restaurants SLA compliance
-Provide real-time & historical dashboards to management

Architecture 
-Azure data lake storage gen 2
-Databricks and Delta lake 
-Event hubs
-batch data
-Data quality
-CDC+SCD2
-Power bi

Data Model
dim_customer
dim_restaurant
dim_courier
fact_order 

streaming events 
evt_order_status
telemetry_courier

enrichment
lkp_weather
