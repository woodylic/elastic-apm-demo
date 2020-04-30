# Demo of Elastic APM with Jaeger

## Setup

```bash
docker-compose up -d
```

## Test

1. Access hotrod at http://localhost:8080, click buttons to generate spans.

2. Access kibana at http://localhost:5601, enter APM page and play.

## Cleanup

```bash
docker-compose down
```