# Router and Switch Monitoring

In order to control the performance of a project and maintain its status, it is necessary to monitor different layers of the project. One of the most important part of network hardwares is routers and switches that must be controlled instantly and the device information displayed on the dashboard.

It should be noted that the SNMP V3 protocol has been used to monitor these devices over Grafana platform.

The mentioned dashboard includes the following item:
- Hostname
- Uptime
- Power Supply Status
- Temperature Status
- Fans Status
- OS Version
- CPU Usage
- Memory Usage
- Input / Output Data Rate
- Errors
- Discards
- Port Summary

In the pictures below, you can see the dashboard visualizations:
![image](https://user-images.githubusercontent.com/43276746/172161239-28cdf6ca-5508-4b25-a9cb-21c9361de346.png)
![image](https://user-images.githubusercontent.com/43276746/172160329-6c4bc997-12b6-460a-8366-090bfd68d355.png)
![image](https://user-images.githubusercontent.com/43276746/172161564-317c8e18-5c82-4aa5-b0b7-22b6a4c11801.png)

Requirements:
- Grafana: https://grafana.com/grafana/download
- InfluxDB & Telegraf: https://portal.influxdata.com/downloads/
- 
Remember:
- At first you need to apply your informations in both of dashoboard and configuration (YOUR-IP, YOUR-NAME, USERNAME, YOUR-AUTH-PASSWORD, YOUR-PRIV-PASSWORD)
- To use snmp configurations you need to load their mib files
