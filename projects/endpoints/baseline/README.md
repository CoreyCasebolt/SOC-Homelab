# 🖥️ Endpoint Baseline Documentation

## 🎯 Purpose

Before deploying monitoring agents or generating attack traffic, I documented the clean baseline state of internal endpoints within my SOC homelab.

Establishing a known-good baseline allows for:

- Comparing pre- and post-agent system state
- Identifying changes introduced by monitoring tools
- Understanding normal operating behavior
- Supporting structured detection engineering
- Providing evidence of clean environment configuration

This step mirrors real-world SOC practice where baseline system states are documented before introducing telemetry collection or security tooling.

---

# Ubuntu Desktop Baseline

## System Identity
- Hostname documented
- OS version and kernel version captured

## Network Configuration
- LAN IP address verified
- Default gateway confirmed (pfSense LAN)
- Routing table validated
- DNS server verified

## Connectivity Validation
- Successful outbound connectivity
- DNS resolution functioning correctly

## Installed Packages
- Default package list recorded
- No Wazuh agent installed

## Listening Services
- Active listening ports documented
- No additional monitoring services present

## Firewall Status
- UFW state recorded

Screenshots available in: https://github.com/CoreyCasebolt/SOC-Homelab/tree/main/projects/endpoints/baseline/Screenshots/ubuntu-desktop

---

# 🟦 Windows 10 Baseline

## System Identity
- OS version and build recorded
- Hostname documented

## Network Configuration
- IPv4 address
- Default gateway (pfSense)
- DNS server confirmed
- DHCP enabled

## Installed Programs
- Default installed software list captured

## Running Services
- Full services list documented
- No Wazuh service present

## Event Viewer – Security Log
- Baseline security event log state captured
- No monitoring agent activity

## Windows Defender Status
- Protection state recorded

Screenshots available in: https://github.com/CoreyCasebolt/SOC-Homelab/tree/main/projects/endpoints/baseline/Screenshots/windows-10
