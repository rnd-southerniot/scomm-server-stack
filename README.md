# scomm-server-stack

This repository contains the server-side components for the ChirpStack deployment and the IoT data pipeline.

## Contents

- ChirpStack Network Server stack: `network-server/chirpstack-docker/`
- IoT data pipeline (Node-RED / InfluxDB / Grafana): `application/iot-app/`
- Multi Node-RED instances: `application/nodered-8/`

## Quick start

- ChirpStack stack: follow `network-server/chirpstack-docker/README.md`
- IoT pipeline: use `application/iot-app/docker-compose.yml`
- Telegraf + Influx: use `application/iot-app/compose-telegraf-influx.yml`
- Multi Node-RED: use `application/nodered-8/docker-compose.yml`
