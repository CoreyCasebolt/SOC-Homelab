# Wazuh Agent Deployment – DC01 (Windows Server)

## Purpose

This project documents deploying a Wazuh agent to my Windows Server domain controller (DC01) in my SOC homelab.

The goal was to:
- Connect DC01 to the Wazuh manager
- Confirm agent registration
- Verify initial log ingestion from the server

---

## Agent Installation

The deployment command was generated from the Wazuh dashboard and executed on DC01.

### Deployment Page
![Deployment Page](screenshots/dc01-agent-deploy-page.png)

### Generated Install Command
![Deployment Command](screenshots/dc01-agent-deploy-command.png)

### Installation Command Execution
![Install Execution](screenshots/dc01-wazuh-agent-install-command.png)

---

## Service Verification

After installation, the Wazuh agent service was started and confirmed running.

### Service Start
![Service Start](screenshots/dc01-start-wazuh-agent.png)

### Service Running
![Service Running](screenshots/dc01-wazuh-agent-running.png)

---

## Agent Registration

DC01 successfully registered and reported as active in the Wazuh dashboard.

![Agent Registered](screenshots/dc01-agent-registered-dashboard.png)

---

## Log Ingestion Verification

Initial logs from DC01 were visible in Wazuh after enrollment.

![Initial Logs](screenshots/dc01-initial-logs-verification.png)

---

## Result

DC01 is now integrated with Wazuh and generating telemetry.

This expands visibility to include domain controller activity for future authentication and AD-focused detections.
