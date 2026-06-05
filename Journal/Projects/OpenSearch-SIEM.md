# OpenSearch SIEM Project

## Overview

This project documents the deployment of an OpenSearch-based Security Information and Event Management (SIEM) platform within my cybersecurity engineering lab.

The objective is to centralize logs, improve visibility, develop detection capabilities, and gain hands-on experience with enterprise security monitoring technologies.

---

## Technologies Used

- Ubuntu Server 24.04
- OpenSearch
- OpenSearch Dashboards
- rsyslog
- pfSense
- Kali Linux
- VMware Workstation
- GitHub

---

## Lab Architecture

### Components

| System | Purpose |
|----------|----------|
| pfSense | Firewall and network gateway |
| Ubuntu Agentic Server | OpenSearch and Dashboards |
| Kali Linux | Security testing workstation |
| GitHub | Project documentation |

---

## Project Goals

- Centralized log management
- Security monitoring
- Dashboard development
- Incident visibility
- SIEM engineering experience
- Portfolio development

---

## Progress Log

### June 5, 2026

#### Completed

- Installed OpenSearch
- Installed OpenSearch Dashboards
- Expanded Ubuntu storage
- Configured JVM memory settings
- Enabled OpenSearch audit logging
- Built initial SOC dashboard
- Configured rsyslog listener on UDP 514
- Verified Kali Linux syslog ingestion

#### In Progress

- pfSense log ingestion

#### Next Steps

- Complete pfSense integration
- Build firewall dashboard
- Build authentication dashboard
- Build alerting workflows
- Integrate n8n automation

---

## Lessons Learned

OpenSearch deployment requires coordination between ingestion, storage, and visualization layers. Packet captures using tcpdump are critical when troubleshooting log forwarding issues.

---

## Future Enhancements

- Wazuh integration
- Sigma rule testing
- Detection engineering workflows
- Threat hunting dashboards
- Azure log integration
- Palo Alto Networks integration
