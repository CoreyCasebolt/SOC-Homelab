# Wazuh – SOC Homelab Implementation

This directory documents my hands-on work building and validating a Wazuh-based SIEM deployment in my SOC homelab.

The focus of this section is to:

- Deploy and validate a working Wazuh environment
- Onboard endpoints and confirm log ingestion
- Build and test detection logic
- Document troubleshooting and lessons learned

---

## Project Structure

### `baseline/`
Initial verified deployment state of Wazuh.

Includes:
- Service validation
- Index verification
- Initial dashboard confirmation
- Environment screenshots

---

### `agent-deployment/`
Onboarding endpoints and validating log ingestion.

Includes:
- Installing agents
- Registering endpoints
- Confirming log forwarding
- Reviewing security events

---

### `detections/`
Detection-focused projects built on top of the validated deployment.

Includes:
- Failed login detection (Event ID 4625)
- Brute force threshold detection (3 failed logons in 1 minute)
- Alert configuration and validation
- Dedicated troubleshooting documentation

---

This section represents the progression from deployment → validation → detection engineering within a structured SOC lab environment.
