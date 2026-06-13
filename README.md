## Water Treatment Plant MQTT Telemetry Security Lab
# 1. Overview
This laboratory simulates a real-world Water Treatment Plant using MQTT-based telemetry communication to study cybersecurity risks, attack vectors, and detection mechanisms in Industrial Control Systems (ICS) and Operational Technology (OT) environments.
The lab is designed for research in industrial cybersecurity, anomaly detection, and critical infrastructure protection.

# 2. Objectives
* Study MQTT protocol behavior in industrial telemetry systems
* Simulate cyber attacks on MQTT communication channels
* Detect anomalies in sensor data streams
* Integrate telemetry data with SIEM systems (Wazuh)
* Visualize industrial processes using Grafana dashboards

# 3. System Architecture
Industrial Sensors (simulated)
Water Level Sensors
Pressure Sensors
Flow Rate Sensors
Communication Layer
MQTT Broker (Mosquitto)
Security & Monitoring Layer
Wazuh SIEM
Grafana Dashboards
Attack Simulation Layer
Traffic manipulation
Replay attacks
Unauthorized topic subscription
Data spoofing

# 4. Research Focus Areas
MQTT protocol security in ICS environments
Telemetry data integrity verification
Detection of abnormal sensor behavior
MITRE ATT&CK mapping for ICS environments
Real-time monitoring of industrial processes

# 5. Threat Scenarios
MQTT Topic Spoofing Attack
Sensor Data Manipulation
Replay Attack on Telemetry Streams
Unauthorized Broker Access
Data Injection into Control Channels

# 6. Technology Stack
MQTT (Mosquitto Broker)
Python (Sensor Simulation)
Wazuh SIEM
Grafana
Linux (Kali / Ubuntu)
Optional: Raspberry Pi / Arduino

# 7. Use Cases
Academic research in ICS cybersecurity
EU-funded research projects (Horizon Europe / Digital Europe)
SOC training environments
Industrial threat detection testing

# 8. Status
Active Research Laboratory (Phase 1)

# 9. Contact
PLPSEC Research & Training Lab
https://plpsec.com
