# Nucleus Security for Splunk App
Nucleus Security for Splunk App

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

Use of this software is not covered by any license, warranty, or support agreement you may have with Nucleus
Security.

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

