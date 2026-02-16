# Wazuh Agent Deployment – Windows 10

## Purpose

This project documents the deployment of a Wazuh agent on a Windows 10 endpoint within my SOC homelab.

The goal was to:

- Connect the endpoint to the Wazuh manager
- Confirm agent registration
- Verify log ingestion into the SIEM

This marks the first step in collecting endpoint telemetry.

---

## Pre-Deployment Verification

Before installation:

- Confirmed Wazuh service was not installed
- Verified connectivity to Wazuh server

Screenshots:
- windows10-pre-agent-service-check.png
- windows10-wazuh-connectivity-test.png

---

## Installation

The agent installation command was generated from the Wazuh dashboard.

Screenshots:
- wazuh-dashboard-agent-deploy-page.png
- wazuh-dashboard-agent-deploy-command.png
- windows10-agent-install-output.png

After installation, the Wazuh service was started and confirmed running.

Screenshot:
- windows10-agent-service-running.png

---

## Registration Confirmation

The agent successfully registered in the Wazuh dashboard and began sending events.

Screenshots:
- wazuh-dashboard-agent-registered.png
- wazuh-dashboard-windows-initial-logs.png

---

## Result

The Windows 10 endpoint is now successfully integrated with Wazuh and generating security event telemetry.

This sets the foundation for future detection and investigation exercises.

