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

Screenshots available in:

