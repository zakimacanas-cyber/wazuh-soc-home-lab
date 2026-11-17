# On-Premise Wazuh SIEM & XDR Lab

Welcome to my portfolio documentation for my Wazuh SOC Home Lab! This repository chronicles the deployment, configuration, and practical investigation workflows performed inside an on-premise Security Operations Center (SOC) lab environment.

---

## 🛠️ Lab Architecture & Components
* **SIEM / XDR Platform:** Wazuh Server (deployed on-premise / virtual machine)
* **Endpoints Monitored:** 
  * Windows Virtual Machine (Endpoint Telemetry & Security Logs)
  * Linux Virtual Machine (Syslog, FIM, & Active Response)
* **Key Capabilities Implemented:**
  * Endpoint Telemetry Ingestion (Windows & Linux agents)
  * Custom Dashboard Creation & Visualization Panels
  * File Integrity Monitoring (FIM) & Custom Alert Rules
  * Automated Remediation via Wazuh Active Response
  * End-to-End Threat Investigation & Reporting

---

## 📊 Deliverables & Highlights

### 1. Custom Dashboard
* **Objective:** Build tailored visualization panels to monitor security events.
* **Artifact:** Located in `docs/dashboard_myf_analyst.png`. *(Note: Tagged with `myf-analyst` to verify ownership for the challenge).*

### 2. Custom Detection Rules & Active Response
* **FIM & Custom Rules (`configs/custom_rules.xml`):** Configured monitoring on critical directories to detect unauthorized modifications.
* **Active Response (`configs/active_response.sh`):** Automated script configured on the Linux endpoint to take immediate defensive action upon triggering specific alert criteria.

### 3. Incident Investigation Report
* **Objective:** Complete a full security incident lifecycle investigation.
* **Report:** Read the full breakdown in `reports/incident_report_01.md`.

---

## 🚀 Key Learnings & Takeaways
* Gained hands-on experience deploying open-source SIEM infrastructure from scratch.
* Mastered agent deployment, log collection pipelines, and parser configuration across multi-OS environments.
* Developed practical skills in writing custom detection rules and executing automated threat response workflows.
