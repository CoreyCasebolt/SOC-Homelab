# Wazuh Agent Deployment – Windows 10

## Purpose

This project documents deploying a Wazuh agent to a Windows 10 endpoint in my SOC homelab.

The goal was to:
- Connect the endpoint to the Wazuh manager
- Confirm agent registration
- Verify security event ingestion

---

## Pre-Deployment Verification

Before installing the agent, I confirmed it was not already present and verified connectivity to the Wazuh server.

### Service Check (No Agent Installed)
![Pre-Agent Service Check](screenshots/windows10-pre-agent-service-check.png)

### Connectivity Test to Wazuh Server
![Connectivity Test](screenshots/windows10-wazuh-connectivity-test.png)

---

## Agent Installation

The deployment command was generated from the Wazuh dashboard.

### Deployment Page
![Deployment Page](screenshots/wazuh-dashboard-agent-deploy-page.png)

### Generated Install Command
![Deployment Command](screenshots/wazuh-dashboard-agent-deploy-command.png)

### Installation Output
![Install Output](screenshots/windows10-agent-install-output.png)

---

## Service Verification

After installation, the Wazuh service was started and confirmed running.

![Agent Service Running](screenshots/windows10-agent-service-running.png)

---

## Agent Registration

The Windows 10 endpoint successfully registered in the Wazuh dashboard.

![Agent Registered](screenshots/wazuh-dashboard-agent-registered.png)

---

## Log Ingestion Verification

Initial security events from the Windows endpoint were visible in Wazuh.

![Initial Logs](screenshots/wazuh-dashboard-windows-initial-logs.png)

---

## Result

The Windows 10 endpoint is now fully integrated with Wazuh and generating telemetry.  

This sets the foundation for future detection and investigation exercises.

