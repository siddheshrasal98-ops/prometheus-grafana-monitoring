# Prometheus Grafana Monitoring

## Project Overview

This project demonstrates monitoring a Dockerized environment using Prometheus, Grafana, and Node Exporter.

## Technologies

- Prometheus
- Grafana
- Docker
- Docker Compose
- Node Exporter

## Architecture

Node Exporter → Prometheus → Grafana Dashboard

## Project Structure

```text
prometheus-grafana-monitoring/
├── docker-compose.yml
├── prometheus.yml
├── grafana/
│   ├── dashboards/
│   │   └── sample-dashboard.json
│   └── provisioning/
│       ├── dashboards/
│       │   └── dashboard.yml
│       └── datasources/
│           └── datasource.yml
├── .gitignore
├── README.md
└── LICENSE
```

## Features

- Prometheus Metrics Collection
- Grafana Dashboards
- Node Exporter Monitoring
- Docker Compose Deployment
- Automatic Datasource Provisioning
- Dashboard Provisioning

## How to Run

```bash
docker-compose up -d
```

Open:

- Prometheus: http://localhost:9090
- Grafana: http://localhost:3000

Default Grafana Login

Username:

```
admin
```

Password:

```
admin
```

## Future Improvements

- Alertmanager
- Email Alerts
- Slack Notifications
- Kubernetes Monitoring
- Blackbox Exporter
- Loki Integration

## Author

Siddhesh Rasal
