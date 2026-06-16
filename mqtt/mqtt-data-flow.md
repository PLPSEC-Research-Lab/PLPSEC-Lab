# MQTT Data Flow
## Overview
This document describes the telemetry flow within the Water Treatment Plant MQTT Telemetry Security Laboratory.

The objective is to simulate industrial telemetry generation, transmission, monitoring, and security analysis.

## Telemetry Sources
The ICS environment generates simulated industrial data.

Examples:

* Water Level
* Pressure
* Flow Rate
* Pump Status
* Valve Status

## MQTT Broker
The MQTT broker acts as the communication hub.

Functions:

* Topic management
* Message distribution
* Client communication
* Telemetry transport

## Monitoring Pipeline
Telemetry Flow:

ICS Environment
→ MQTT Broker
→ Wazuh Monitoring
→ Grafana Dashboards

## Security Monitoring
Wazuh performs:

* Log analysis
* Event correlation
* Anomaly detection
* Alert generation

## Visualization
Grafana provides:

* Operational dashboards
* Security dashboards
* Telemetry visualization
* Alert monitoring

## Research Objectives
Study MQTT behavior

* Monitor industrial telemetry
* Detect abnormal activity
* Evaluate security controls
* Develop detection rules
