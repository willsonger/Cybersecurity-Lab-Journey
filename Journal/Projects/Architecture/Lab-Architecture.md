# Cybersecurity Lab Architecture

## Overview

This document describes the architecture of my cybersecurity engineering lab.

## Components

### pfSense Firewall
- Primary gateway
- Network segmentation
- DNS and DHCP services
- Syslog forwarding

### Ubuntu Agentic Server
- OpenSearch
- OpenSearch Dashboards
- n8n Automation
- rsyslog

### Kali Linux
- Security testing
- Vulnerability assessment
- Network analysis

## Data Flow

pfSense → Syslog → Ubuntu Server → OpenSearch → Dashboards

## Future Expansion

- Wazuh
- Azure integration
- Palo Alto Networks
- Detection engineering workflows
