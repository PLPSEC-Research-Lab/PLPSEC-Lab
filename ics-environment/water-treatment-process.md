# Water Treatment Process

## Overview
This laboratory simulates a water treatment plant environment for industrial cybersecurity research and telemetry monitoring.
The environment generates operational telemetry data transmitted through MQTT and monitored by Wazuh and Grafana.

## Monitored Parameters
### Temperature
Description:

Water temperature measurement used to monitor operational conditions.

Unit:
°C

Research Purpose:

  * Telemetry monitoring
  * Anomaly detection
  * Data integrity validation

## Pressure
Description:

Pressure monitoring within the water treatment process.

Unit:
bar

Research Purpose:

  * Process monitoring
  * Detection of abnormal values
  * Operational state analysis

## Chlorine
Description:

Chlorine concentration monitoring for water treatment quality control.

Unit:
mg/L

Research Purpose:

  * Telemetry validation
  * Data integrity monitoring
  * Sensor behavior analysis

## Pump Status
Description:

Operational state of the water treatment pump.

Values:

  * ON  (1)
  * OFF (0)

Research Purpose:

  * Process state monitoring
  * Event correlation
  * Detection engineering

## Telemetry Workflow
Sensors
↓
MQTT Broker
↓
Wazuh SIEM
↓
Grafana Dashboards

## Research Objectives
  * Industrial telemetry monitoring
  * MQTT security research
  * Detection engineering
  * Security event correlation
  * Critical infrastructure cybersecurity research

## Current Status
Phase 1 Laboratory Environment

Active Components:

  * ICS Environment
  * MQTT Telemetry
  * Wazuh SIEM
  * Grafana
  * Kali Linux
