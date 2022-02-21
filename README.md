# Jenkins traces/metrics example

Just start all components to transmit job metrics/traces from Jenkins to Prometheus/OpenSearch:

```
docker-compose up
```

and run jobs in [Jenkins](http://localhost:8080/) - as is or replay with error instead of echo in pipeline.

Next see results in:

* [Prometheus](http://localhost:9090)
* [OpenSearch/Observability](http://localhost:5601/app/observability-dashboards#/trace_analytics/traces)
* [OpenSearch/Jaeger](http://localhost:16686/search)
