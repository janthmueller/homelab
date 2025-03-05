For monitoring homelab’s Docker containers and overall hardware usage (RAM, CPU, disk, and network):

- **Prometheus**: Scrapes and stores time-series data from containers.
- **cAdvisor (Container Advisor)**: Collects container-level metrics such as CPU, memory, network, and disk usage.
- **Node Exporter**: Gathers host-level system stats (RAM, CPU, etc.).
- **Grafana**: Creates dashboards to visualize everything.

Resources:
- https://medium.com/@varunjain2108/monitoring-docker-containers-with-cadvisor-prometheus-and-grafana-d101b4dbbc84
- https://github.com/solo5star/dashboard