# Wazuh Detections – SOC Homelab

This directory contains detection-focused projects built in my SOC homelab using Wazuh and OpenSearch.

Each project documents the detection logic, implementation steps, validation process, and troubleshooting details.

---

## Detection Projects

### Failed Login Detection – Windows Event ID 4625
Generates and analyzes a Windows failed login event to validate log ingestion and event review.

📂 `failed-login-detection/`

---

### Windows Brute Force Threshold Detection (3 Failed Logons in 1 Minute)
Implements a threshold-based alert to detect repeated failed logon attempts within a short timeframe.

📂 `brute-force-threshold/`

---

These projects are part of my hands-on SOC learning path focused on building, testing, and validating SIEM detections.
