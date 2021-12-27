### Implementing Lakehouse Architecture to analyse health device data

> Lakehouse provides many additional features on top of data lake like transaction support (ACID properties), schema enforcement and governance, end-to-end streaming, BI support etc.

Goal of this project is to:
* Build pipeline adhering to multi-hop architecture for our health tracker data i.e. Bronze table for data ingestion, Silver table for filter, cleaned and augmented data and Gold table for aggregated data.
* Practice features of lakehouse like Updates, time-travel.
* Handling data quality and missing data.
