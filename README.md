# OpenMetrics_XCP_Grafana

This is a Grafana dashboard for XCP-ng/XOA using the OpenMetrics plugin (Prometheus exporter).

This dashboard is my own version of an infrastructure overview.  
All dashboards include recurring views for VM, SR, Host, and Pool if they are connected to the XOA Prometheus telemetry source.

It is currently in development to add more metrics and improvements.

Documentation: https://docs.xen-orchestra.com/advanced#openmetrics--prometheus-integration  
Forum link: https://xcp-ng.org/forum/topic/11856/openmetrics-powered-grafana-dashboards-for-xen-orchestra


## Cluster Overview 

![Cluster](/Assets/cluster_view.png)

Download the dashboard : [Xoa_cluster_overview.json](/Dashboard/Xoa_cluster_overview.json)

## Host Overview 

![Host](/Assets/host_view.png)

Download the dashboard : [Xoa_host_overview.json](/Dashboard/Xoa_host_overview.json)

## VM Overview 

![VM](/Assets/vm_view.png)

Download the dashboard : [Xoa_vm_overview.json](/Dashboard/Xoa_vm_overview.json)

## Storage Overview 

![Storage](/Assets/sr_overview.png)

Download the dashboard : [Xoa_sr_overview.json](/Dashboard/Xoa_sr_overview.json)

# Features currently in progress

- Collect uptime from hosts & VMs
- Collect storage capacity from VMs
- Add network name information for VMs with multiple interfaces
- More features coming in the future

If you have any other ideas, feel free to ping me 🙂