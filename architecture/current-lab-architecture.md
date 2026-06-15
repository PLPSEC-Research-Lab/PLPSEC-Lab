# Current Laboratory Architecture
## Overview
The Water Treatment Plant MQTT Telemetry Security Laboratory is deployed as a virtualized research environment designed for industrial cybersecurity experimentation, monitoring, and detection engineering.

The laboratory consists of four primary systems connected through two network segments:

* NAT Network (external communication and inter-system connectivity)
* Host-Only Network (isolated management and research network)

# Laboratory Components
## ICS Environment
Purpose:

Industrial process simulation

Telemetry generation

MQTT communications

Water treatment process research

Network Configuration:

### Interface	IP Address
NAT	192.168.133.129
Host-Only	192.168.100.20
## Grafana
Purpose:

* Telemetry visualization
* Operational dashboards
* Security monitoring dashboards

Network Configuration:

### Interface	IP Address
NAT	192.168.133.130
Host-Only	192.168.100.30
## Wazuh SIEM
Purpose:

* Log collection
* Event correlation
* Threat detection
* Security monitoring

Network Configuration:

### Interface	IP Address
NAT	192.168.133.133
Host-Only	192.168.100.40
## Kali Linux
Purpose:

* Security testing
* Attack simulation
* Detection validation
* Research activities

Network Configuration:

### Interface	IP Address
NAT	192.168.133.131
Host-Only	192.168.100.131
# Network Architecture
## NAT Network
Network Range:

192.168.133.0/24

Purpose:

* Connectivity between laboratory systems
* Software updates
* Service communication
* Research environment integration

Connected Systems:

* ICS Environment (192.168.133.129)
* Grafana (192.168.133.130)
* Kali Linux (192.168.133.131)
* Wazuh SIEM (192.168.133.133)

## Host-Only Network
Network Range:

192.168.100.0/24

Purpose:

* Isolated management network
* Secure laboratory administration
* Internal testing and validation

Connected Systems:

* ICS Environment (192.168.100.20)
* Grafana (192.168.100.30)
* Wazuh SIEM (192.168.100.40)
* Kali Linux (192.168.100.131)

# Logical Data Flow
ICS Environment
↓
MQTT Telemetry
↓
Monitoring Layer
↓
Wazuh SIEM
↓
Grafana Dashboards

Security Validation:

Kali Linux
↓
Attack Simulation
↓
Detection Monitoring
↓
Wazuh Alerts
↓
Grafana Visualization

# Current Laboratory Status
Phase 1: Core Infrastructure Completed

Available Components:

* ICS Environment
* Grafana Platform
* Wazuh SIEM
* Kali Linux Research System

Planned Next Steps:

* MQTT Telemetry Integration
* Attack Scenario Development
* Detection Rule Engineering
* Modbus Security Laboratory
* OPC UA Security Laboratory
* DNP3 Security Laboratory

# Research Scope
This laboratory supports research in:

* Industrial Cybersecurity
* Operational Technology (OT) Security
* MQTT Security Monitoring
* Critical Infrastructure Protection
* Detection Engineering
* Security Operations Center (SOC) Research
