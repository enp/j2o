# Jenkins traces/metrics example

Just start all components to transmit job traces/metrics from Jenkins to OpenSearch/Prometheus:

```
docker-compose up
```

and run jobs in [Jenkins](http://localhost:8080/) - as is or replay with error instead of echo in pipeline.

Next open [OpenSearch](http://localhost:5601/app/observability-dashboards#/trace_analytics/traces) and [Prometheus](http://localhost:9090) to see results
