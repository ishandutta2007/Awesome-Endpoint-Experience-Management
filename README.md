# Awesome-Endpoint-Experience-Management

# Top Endpoint Experience Management Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Digital Employee Experience (DEX), Endpoint Performance, Application Experience, Proactive Remediation & IT Visibility*
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Endpoint Experience Management** (also called Digital Employee Experience / DEX). These systems collect deep endpoint and application telemetry, score employee experience, detect issues, and enable proactive remediation across physical and virtual desktops.

**Examples** include Nexthink, ControlUp, Lakeside SysTrack, Aternity, UberAgent, SysTrack, DexCare, 1E Tachyon, Riverbed Aternity, and VMware Workspace ONE Intelligence (the category leaders).

**Open-source emphasis**: Full DEX platforms with rich experience scoring, employee sentiment, and automated remediation are predominantly commercial. Practical open building blocks include **osquery**, **Prometheus + node exporters**, logging stacks, and custom telemetry pipelines. This section expands those options and is realistic about the commercial gap.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[Nexthink](https://www.nexthink.com/)**  
  Leading digital employee experience platform with real-time endpoint visibility, experience scoring, employee engagement, and automated remediation at scale.

- **[ControlUp](https://www.controlup.com/)**  
  DEX and endpoint monitoring platform strong in physical, virtual, and cloud desktop environments—with synthetic tests, remediation, and operational insights.

- **[Lakeside SysTrack](https://www.lakesidesoftware.com/)**  
  Deep endpoint, application, and infrastructure telemetry platform widely used for troubleshooting, capacity planning, and experience analytics.

- **[Aternity (Riverbed)](https://www.riverbed.com/)**  
  End-user experience and application performance monitoring focused on business transactions and digital employee experience.

- **[UberAgent](https://uberagent.com/)**  
  Endpoint experience and security-oriented monitoring agent that feeds detailed telemetry into Splunk and other analytics platforms.

- **[SysTrack](https://www.lakesidesoftware.com/)**  
  Core Lakeside technology for continuous endpoint and workspace analytics (often referenced alongside the broader SysTrack suite).

- **[DexCare and related DEX solutions](https://www.example.com/)**  
  Additional platforms focused on digital experience scoring and IT service improvement.

- **[1E Tachyon](https://www.1e.com/)**  
  Real-time endpoint management and instruction platform used for visibility, compliance, and rapid remediation across large estates.

- **[Riverbed Aternity](https://www.riverbed.com/)**  
  Application and end-user experience monitoring within the Riverbed portfolio.

- **[VMware Workspace ONE Intelligence / Omnissa and related EUEM tools](https://www.omnissa.com/)**  
  Workspace and endpoint intelligence capabilities for experience insights within broader digital workspace platforms.

## Open-Source GitHub Projects
- **[osquery](https://github.com/osquery/osquery)**  
  Open-source endpoint instrumentation framework that exposes operating system data as a high-performance relational database—foundational for custom DEX-style telemetry.

- **[Prometheus + node_exporter / Windows exporter](https://github.com/prometheus/node_exporter)**  
  Industry-standard open metrics collection for hosts and endpoints; commonly paired with Grafana for performance and availability dashboards.

- **[Grafana](https://github.com/grafana/grafana)**  
  Open-source visualization and dashboarding platform used to build endpoint and experience-oriented views from metrics and logs.

- **[Elastic Stack (Beats, Elasticsearch, Kibana)](https://github.com/elastic)**  
  Open observability components frequently used for endpoint logs, metrics, and search-driven troubleshooting.

- **[OpenTelemetry](https://github.com/open-telemetry)**  
  Vendor-neutral open standard and SDKs for collecting metrics, logs, and traces—usable for application and endpoint experience data.

- **[Fleet (osquery manager)](https://github.com/fleetdm/fleet)**  
  Open-source device management and osquery orchestration platform for querying and managing large endpoint fleets.

- **[Wazuh](https://github.com/wazuh/wazuh)**  
  Open-source security and endpoint visibility platform that can contribute inventory, configuration, and health signals.

- **[Custom RUM and desktop telemetry open collectors](https://github.com/)**  
  Community agents and scripts for collecting application launch times, resource usage, and user-perceived performance.

- **[Logging and SIEM open pipelines](https://github.com/)**  
  Fluent Bit, Vector, and similar tools for shipping endpoint telemetry into analysis systems.

- **[Documentation and DIY DEX open playbooks](https://github.com/)**  
  Guides for combining osquery, Prometheus, Grafana, and log pipelines into lightweight endpoint experience monitoring.

### Additional Strong Open-Source Options
- Building a basic DEX-style stack with **osquery + Fleet + Prometheus + Grafana** for inventory, performance, and custom experience metrics.
- Using **OpenTelemetry** and logging agents to capture application and desktop signals without commercial DEX agents.
- Accepting that enterprise experience scoring, employee sentiment surveys, AI-driven remediation, large-scale correlation, and polished IT workflows still require commercial platforms (Nexthink, ControlUp, Lakeside SysTrack, Aternity, 1E, etc.).
- Focusing open-source efforts on data ownership, cost control, and targeted visibility for security and platform teams.

**Frameworks for building custom systems**: Deploy osquery/Fleet for endpoint queryability → collect metrics with Prometheus exporters → centralize logs → visualize and alert in Grafana → optionally add OpenTelemetry for app-level signals. Suitable for engineering-led IT teams. Most large organizations adopt commercial DEX platforms for comprehensive employee experience programs.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Endpoint monitoring collects sensitive device and user activity data. Open-source deployments require strong privacy, security, and governance practices. This list is not IT operations or privacy advice.

---
**Made for digital workplace, IT operations, and open observability advocates.**
Let's keep endpoints visible, experiences measurable, and monitoring as open as practical.
