# Monitoring Stack

A monitoring and observability project for learning how to collect metrics, visualize systems health, and detect operational issues.

## Overview

This project demonstrates a basic observability stack that helps track infrastructure and application health. It is built as a practical learning project for Infrastructure/Ops and cloud operations.

## Goals

- Learn observability basics.
- Collect and visualize metrics.
- Practice alerting concepts.
- Build a reusable lab.
- Create a portfolio-ready project.

## Tech Stack

- Prometheus
- Grafana
- Linux
- Docker or Docker Compose
- Optional: Node Exporter
- Optional: Alertmanager

## What This Stack Does

- Collects metrics from systems or applications.
- Stores time-series data.
- Displays dashboards.
- Supports alerting and operational visibility.

## Repository Structure

```text
.
├── README.md
├── docker-compose.yml
├── prometheus/
├── grafana/
├── dashboards/
├── alerts/
├── notes/
└── docs/
```

## Setup

1. Install Docker and Docker Compose.
2. Configure Prometheus targets.
3. Start the stack.
4. Open Grafana.
5. Import or build dashboards.

```bash
docker compose up -d
```

## Usage

Use this stack to monitor a lab system, app, or containerized service.

## Validation

- Confirm Prometheus is scraping targets.
- Confirm Grafana dashboards load correctly.
- Verify alerts trigger as expected.
- Check metric trends over time.

## Lessons Learned

- Why observability matters.
- How metrics help with troubleshooting.
- How dashboards support operations.
- How alerts should stay actionable.

## Next Steps

- Add custom dashboards.
- Add alert rules.
- Monitor more services.
- Add logs and traces.
- Improve operational response.

## Notes

Use `notes/` for dashboard design notes, alerting strategy, and troubleshooting records.

## License

Add a license if needed.
