# Scenario 01: Baseline Monitoring

## Objective
Establish normal MQTT telemetry behavior.

## Description
The laboratory operates without attacks.

Sensor telemetry is transmitted through MQTT and monitored by Wazuh and Grafana.

## Expected Results

* Stable telemetry values
* No security alerts
* Normal communication patterns
* Consistent dashboard metrics

## Detection Goal
Create a baseline profile of normal system behavior.
This baseline will later be used for anomaly detection.
