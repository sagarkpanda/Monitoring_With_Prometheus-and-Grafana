# Monitoring with Prometheus and Grafana
Monitoring Linux Server with Prometheus and Grafana. Node and Blackbox exporter. Alert Manager.

<p align="center">
<img alt="Prometheus" width="270px" src="https://raw.githubusercontent.com/devicons/devicon/develop/icons/prometheus/prometheus-original.svg " style="padding-right:10px ;"/> &nbsp
<img alt="Grafana" width="270px" src="https://raw.githubusercontent.com/devicons/devicon/develop/icons/grafana/grafana-original.svg" style="padding-right:10px;" />
</p>
</br>

# Introduction:
Prometheus is a open-source platform for monitoring hardware and services. It collects metrics from the system of any other services that we configured.

## Setup:
In this article we are going to see how to setup monitoring of a linux machine.

I’m going to use Docker to setup this process, however you can install binaries as usual. The docker compose consists of multiple components.

- First setup - Prometheus with Grafan. Viewing Server resources usgae using Node Exporter.
- Second setup - Prometheus alert manager for mail alerts for server usage.
- Third setup - Prometheus Blackbox exporter setup to view and monitor website metrics. Also sendd alerts.
</br>
<h3> <strong> Read the full articles on: </strong> </h3> <a href = "https://medium.com/devops-dev/setup-monitoring-prometheus-and-grafana-2431b26cd757" target ="_blank">

<picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://github.com/sagarkrp/sagarkrp/blob/main/images/Medium-white1x.png" width="160px" height="35px">
   <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/sagarkrp/sagarkrp/main/images/Medium-dark.svg" width="160px" height="35px">
   <img alt="Medium Alternative Theme." src="https://raw.githubusercontent.com/sagarkrp/sagarkrp/main/images/Medium-dark.svg" width="160px" height="35px">
</picture> </a> </br> &nbsp

# Node Exporter Dashboard:
![image](https://github.com/sagarkrp/Prometheus_Grafana/assets/42873729/096fb27b-af85-4fdb-95bd-655c2a77463f)

# Blackbox Dashboard
![blackbox](https://github.com/sagarkrp/Monitoring_With_Prometheus-and-Grafana/assets/42873729/2dbc07a8-bc27-4866-a293-646420df3d44)
