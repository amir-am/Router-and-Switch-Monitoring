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
- Port Summary (Name, Index, Alias, Status, IP Address, Network Mask, Bandwidth, Type, In Errors, Out Errors)

Stackwise [Switches Only]
- Switch Info (Number, Role, Power Budget, Power Allocated, State)
- Stack Port Info (Index, Neighbor, Oper Status)
- Stack Power Info (Name, Type, Mode)

In the pictures below, you can see the dashboard visualizations:
![image](https://user-images.githubusercontent.com/43276746/178444483-7cf863a2-3af5-4c9b-bfdd-bb367a5f4854.png)
![image](https://user-images.githubusercontent.com/43276746/178444649-03fab14f-4246-4440-a495-d7246e71372e.png)
![image](https://user-images.githubusercontent.com/43276746/178444945-299d39c8-0096-4ad1-a365-1320509a30d1.png)
![image](https://user-images.githubusercontent.com/43276746/178445059-51c4339b-3004-4550-a214-ded6d839e919.png)


Requirements:
- Grafana: https://grafana.com/grafana/download
- InfluxDB & Telegraf: https://portal.influxdata.com/downloads/

Remember:
- At first you need to apply your informations in both of dashoboard and configuration (YOUR-IP, YOUR-NAME, USERNAME, YOUR-AUTH-PASSWORD, YOUR-PRIV-PASSWORD)
- To use snmp configurations you need to load their mib files
