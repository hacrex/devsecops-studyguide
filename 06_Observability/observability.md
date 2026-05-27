# Observability + Incident Layer

Focuses on monitoring, tracing, and effective incident handling.

## Core Topics

- **Logs**: Centralized logging, log formats, log aggregation (ELK, Loki), query languages.
- **Metrics**: Prometheus, OpenTelemetry, custom instrumentation, alerts based on thresholds.
- **Tracing**: Distributed tracing (Jaeger, Zipkin), span concepts, correlation IDs.
- **Alerts & Dashboards**: Alerting rules, on‑call rotation, PagerDuty/Opsgenie, Grafana dashboards.
- **Root Cause Analysis (RCA)**: Systematic investigation, post‑mortem templates, blameless culture.
- **On‑Call Practices**: Rotation schedules, escalation policies, incident communication.
- **Failure Recovery**: Backup & restore strategies, chaos engineering basics.
- **Post‑mortems**: Writing effective post‑mortems, action items, learning loops.

## Study Tips

1. **Instrument** – Add Prometheus metrics and OpenTelemetry tracing to a sample app.
2. **Log Exploration** – Use Kibana or Loki to search logs for specific error patterns.
3. **Run a Drill** – Simulate an outage, trigger alerts, run through an on‑call run‑book.
4. **Post‑mortem Practice** – Document a mock incident using the [GitHub Incident Template](https://github.com/github/template).

## Study Material References
- **Prometheus**: Prometheus Documentation – https://prometheus.io/docs/introduction/overview/
- **OpenTelemetry**: OpenTelemetry Docs – https://opentelemetry.io/docs/
- **Google SRE Book**: Monitoring Distributed Systems – https://sre.google/sre-book/monitoring-distributed-systems/
- **Grafana**: Getting Started with Grafana – https://grafana.com/docs/grafana/latest/getting-started/
