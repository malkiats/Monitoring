InfluxDB
- InfluxDB is an open-source time series database developed written in Go by InfluxData.  
- InfluxDB optimized for fast, high-availability storage and retrieval of time series data for metrics analysis  

Telegraf
- Telegraf is an agent written in Go for collecting, processing, aggregating, and writing metrics.  
- It is installed on all devices that need to be monitored, and all metrics collected by Telegraf are pushed stored on InfluxDB.  

Grafana
- Grafana is an open source, feature rich metrics dashboard and graph editor for Graphite, Elasticsearch, OpenTSDB, Prometheus, and InfluxDB.   
- Data stored on InfluxDB will be visualized using Grafana.  

Prometheus
- Prometheus is a tool used for systems and service monitoring.  
- It collects metrics from configured targets at given intervals, evaluates rule expressions, displays the results.  
- It can trigger alerts. Metrics stored on Prometheus can be visualized using Grafana.
