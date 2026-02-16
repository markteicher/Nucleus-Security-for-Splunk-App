![Nucleus Logo](docs/images/nucleus_logo.jpg)

# Nucleus Security for Splunk App


# Overview
Nucleus integrates all your vulnerability, threat, and asset data to effectively prioritize critical exposures with business context and threat intelligence.

The Nucleus Security for Splunk App is a single Splunk application that ingests events from a Nucleus Security instancd using the Nucleus Security REST API. The app ingests data into a user-specified Splunk index and assigns the correct sourcetype to each event. All events are ingested in JSON format to preserve the original structure and content of the Nucleus data.

The Splunk app provides dashboards, reports, and search logic for analyzing data ingested from a Nucleus Security instance.


The Splunk App is intended to surface Nucleus Security data directly inside Splunk so that Asset Owners and operational teams can view, analyze and action Nucleus Security results without requiring access to the Nucleus Security user interface.



![Python](https://img.shields.io/badge/python-3.10%2B-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Status](https://img.shields.io/badge/status-active%20development-yellow.svg)



---

⚠️ Disclaimer

These tools are not official Nucleus Security products or utilities

Use of this software is not covered by any license, warranty, or support agreement you may have with Nucleus Security.



---

## Key Functions & Features

- **Exposure Aggregation**: Consolidates vulnerability data across scanners into a unified exposure model.
- **Risk-Based Prioritization**: Applies business context and threat intelligence to rank critical exposures.
- **Threat Intelligence Correlation**: Integrates EPSS, Mandiant, CISA BOD 22-01, Shadowserver, and custom threat feeds.
- **Asset Context Mapping**: Aligns vulnerabilities with asset ownership and organizational units.
- **Platform & API Access**: Secure REST API ingestion with structured JSON preservation.

---

## Supported Asset and Intelligence Types

- Vulnerabilities
- Assets
- Asset Groups
- Threat Intelligence
- EPSS Scores
- Mandiant Intelligence
- CISA BOD 22-01 Tracking
- Custom Threat Feeds
- Shadowserver Data
- Insights
- VIP Monitors
- Users
- Roles and Permissions
- Teams
- Email Notifications
- System Use Notifications
- License Information

---

## Features

### 🛡️ Core Capabilities

| Feature | Description |
|----------|------------|
| 🎯 Risk-Based Exposure | Prioritize exploitable vulnerabilities |
| 🧠 Threat Intelligence Overlay | EPSS and Mandiant enrichment |
| 🏢 Business Context | Asset ownership and organizational alignment |
| 📦 JSON Event Preservation | Raw API responses retained |
| 🔗 Multi-Scanner Normalization | Unified exposure model |
| 📊 Operational Dashboards | Exposure analytics inside Splunk |

---

### 📈 Analytics and Visibility

| Feature | Description |
|----------|------------|
| 📊 Risk Trends | Exposure tracking over time |
| 🔄 First-Seen Detection | Identify newly observed exposures |
| 🧱 Asset Risk Distribution | Exposure by asset group |
| 🔐 EPSS Score Analysis | Exploit probability visibility |
| 🧠 Investigative Pivoting | Pivot across assets and vulnerabilities |

---

### ⚙️ Operational Excellence

| Feature | Description |
|----------|------------|
| 📡 Modular Input Framework | Secure API-based ingestion |
| 🔑 Credential Management | Encrypted credential storage |
| 🌐 Proxy Support | Enterprise proxy compatibility |
| 🩺 Health Monitoring | API reachability validation |
| 📋 Operational Logging | Full ingestion traceability |
| ⏱️ Polling Controls | Rate-limit aware data collection |

---

## 📊 Dashboards

- Overview  
- Insights  
- Vulnerabilities  
- Assets  
- Asset Groups  
- EPSS Score  
- Mandiant Intelligence  
- CISA BOD 22-01  
- Threat Data  
- VIP Monitors  
- Users  
- Roles & Permissions  
- Teams  
- Notifications  
- Licenses  
- Operations  
- Health  

---

## Sourcetype → Dashboard Mapping

### Core Exposure Data

| Sourcetype | Dashboards |
|------------|------------|
| `nucleus:vulnerability` | Overview, Vulnerabilities |
| `nucleus:asset` | Assets |
| `nucleus:asset_group` | Asset Groups |
| `nucleus:insight` | Insights |
| `nucleus:threat` | Threat Data |
| `nucleus:epss` | EPSS Score |

---

### Threat Intelligence

| Sourcetype | Dashboards |
|------------|------------|
| `nucleus:mandiant` | Mandiant Intelligence |
| `nucleus:cisa_bod_22_01` | CISA BOD 22-01 |
| `nucleus:shadowserver` | Threat Data |
| `nucleus:custom_threat` | Threat Data |

---

### Users Roles Permissions Teams VIP Monitor Licenses

| Sourcetype | Dashboards |
|------------|------------|
| `nucleus:user` | Users |
| `nucleus:role` | Roles & Permissions |
| `nucleus:team` | Teams |
| `nucleus:vip` | VIP Monitors |
| `nucleus:license` | Licenses |

---

### Operations & Health

| Sourcetype | Dashboards |
|------------|------------|
| `nucleus:notification` | Notifications |
| `nucleus:system_usage` | Operations |
| `nucleus:health` | Health |
| `nucleus:error` | Error Tracking |

---


## Requirements

Splunk Enterprise or Splunk Cloud
Network connectivity to a Nucleus Security instance
Valid Nucleus Security credentials



---
✅ AppInspect Compliance

Proper Splunk directory structure
Inputs disabled by default
No hardcoded credentials
Secure credential storage
Raw JSON ingestion

# License


Nucleus Security
https://nucleussec.com

#Copyright (c) 2026 Mark Teicher

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

