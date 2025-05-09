# Open Metrics Hub

This project collects host operating system metrics and integrates with **Prometheus** for visualization.

## How to Run the Project

1. Clone the repository:

    ```bash
    git clone https://github.com/mateusdata/open-metrics-hub.git
    cd open-metrics-hub
    ```

2. Start the containers with `docker-compose`:

    ```bash
    docker-compose up
    ```

## Accessing Metrics

- **Prometheus UI**: [http://localhost:9090](http://localhost:9090)

## Project Structure

- **docker-compose.yml**: Orchestrates the OpenTelemetry Collector and Prometheus containers.
- **otel-collector-config.yaml**: Configuration for the OpenTelemetry Collector.
- **prometheus.yml**: Configuration for Prometheus.

---

Project developed for collecting operating system metrics.
