# raycarehealthmonitor
Template to monitor Raycare by Raysearch Laboratories.

# Install
Import Raycare_Monitoring.xml file into Zabbix and set the AGGREGATEDREPORTURL to your Raycare aggregated health report URL.

# Working logic
Zabbix queries the aggregated health url, uses dependant items for the aggregated health of the entire system, LLD to populate items with information about each node.
