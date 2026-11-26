# Wazuh SOC Home lab

Welcome to my portfolio documentation for my Wazuh SOC Home lab! This repository chronicles the deployment, configuration, and practical investigation workflows performed inside an on-premise Security Operations Center (SOC) lab environment.

## 1. Architecture

- **Hypervisor:** VMware Workstation Pro
- **SIEM / XDR Server:** Ubuntu Server VM running Wazuh (Manager, Indexer, and Dashboard)
- **Monitored Endpoints:** Windows and Linux virtual machines enrolled with Wazuh agents and Sysmon/host telemetry
  
![Lab Architecture](lab-architecture.png)

## 2. Detections & Telemetry Tuning

- **Telemetry Sources:** Windows Sysmon process/network/file events, authentication logs, and Wazuh File Integrity Monitoring (FIM) on critical paths.
- **Custom Detection Logic:** Added tailored Wazuh rules to flag suspicious command-line activity, unexpected persistence/file changes, or repeated authentication failures.
- **False-Positive Tuning:** Documented noisy baseline activity filtered out during testing and explained why exclusions were scoped narrowly so high-signal alerts were not suppressed.

---

### Skills Learned

- Advanced understanding of SIEM concepts and practical application.
- Proficiency in analyzing and interpreting network logs.
- Ability to generate and recognize attack signatures and patterns.
- Enhanced knowledge of network protocols and security vulnerabilities.
- Development of critical thinking and problem-solving skills in cybersecurity.


