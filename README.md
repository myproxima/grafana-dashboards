# Grafana Dashboards

A collection of dashboards created by us specifically to monitor our Proxima products.

## Dashboards

* proxima-all-nodes: It is a dashboard reporting System, SIP, Chat, PHP and nginx data. Use Host parameter to select the machine you are interested in;
* proxima-single-node: It is a dashboard reporting only machine's essential data, so that it can be used on a display monitor. Before importing you must replace the `###FQDN###` and `###LABEL###` strings with the monitored machine's data.
* proxima-cc-queue: This is an example dashboard, reporting some metrics among those exposed by the Call Center's Advanced Statistics module. Before importing you must replace the `###FQDN###`, `###EXTQUEUE###` and `###LABEL###` strings with the monitored machine's data. If you want to build a custom stack, designed specially for call center, you can refer to this repo: https://github.com/myproxima/openmetrics-docker/tree/call-center
