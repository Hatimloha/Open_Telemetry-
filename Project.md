# Otel Astronomy Shop Demo App

## Prerequisites:
- AWS Cloud
### Steps:
Create EC2 instance with the following configurations:
- Ubuntu 22
- T2.xlarge (More than 6GB ram required)
- 15GB storage


```shell
git clone https://github.com/open-telemetry/opentelemetry-demo.git
cd opentelemetry-demo/
```

> As a DevOps Engineer you should understand what this project is doing and how things are happening so let’s understand the docker compose file responsible for deploying the app.

## Understanding the docker compose file structure!

This Docker Compose file is designed to set up an observability demo environment using various microservices. If you're new to observability, here's how you can understand this setup:

https://github.com/open-telemetry/opentelemetry-demo/blob/main/docker-compose.yml
