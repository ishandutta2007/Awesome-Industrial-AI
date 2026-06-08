# Awesome-Industrial-AI

## Top Industrial AI & Predictive Maintenance Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Industrial AI, Condition Monitoring & Predictive Maintenance*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** building **Industrial AI and Predictive Maintenance** solutions. These tools use sensor data (vibration, temperature, ultrasound, etc.), IoT, machine learning, and AI agents to predict equipment failures, reduce downtime, optimize maintenance schedules, and improve asset reliability in manufacturing, energy, and heavy industry.

**Examples** include Augury, TRACTIAN, UptimeAI, Uptake, Nanoprecise Sci Corp, Sensemore, IBM Maximo, Siemens MindSphere (Insights Hub), PTC ThingWorx, GE Digital (Predix), and Infinite Uptime (the category leaders). Tools listed here emphasize **agentic and intelligent capabilities** (anomaly detection, remaining useful life estimation, automated diagnostics, prescriptive maintenance recommendations, and digital twins).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, local ML models, custom sensor pipelines, and full data/control ownership — ideal for manufacturers and developers building in-house predictive maintenance systems.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS Products](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS Products

### Core Platforms (Industrial AI & Predictive Maintenance)

- **[Augury](https://www.augury.com/)**  
  Leading AI-powered machine health platform using vibration, ultrasound, and process data for early fault detection and prescriptive maintenance recommendations.

- **[TRACTIAN](https://tractian.com/)**  
  Smart sensors + AI platform combining condition monitoring, predictive maintenance, and CMMS in one solution. Popular for fast deployment and strong ROI in manufacturing.

- **[UptimeAI](https://www.uptimeai.com/)**  
  Industrial AI platform focused on predictive analytics, anomaly detection, and root cause analysis for critical assets.

- **[Uptake](https://www.uptake.com/)**  
  AI-driven industrial intelligence platform offering predictive maintenance and asset performance management.

- **[Nanoprecise Sci Corp](https://nanoprecise.com/)**  
  Wireless sensors and AI platform delivering ultra-precise predictive insights with easy installation.

- **[Sensemore](https://sensemore.io/)**  
  AI-based predictive maintenance solution with advanced vibration analytics and wireless sensors.

- **[IBM Maximo](https://www.ibm.com/products/maximo)**  
  Enterprise asset management (EAM) platform with strong AI and IoT capabilities for predictive maintenance.

- **[Siemens MindSphere (Insights Hub)](https://www.siemens.com/global/en/products/automation/mindsphere.html)**  
  Cloud-based IoT operating system with powerful industrial analytics and predictive maintenance applications.

- **[PTC ThingWorx](https://www.ptc.com/en/products/thingworx)**  
  Industrial IoT platform enabling rapid development of predictive maintenance and digital twin applications.

- **[GE Digital (Predix)](https://www.ge.com/digital/)**  
  Industrial cloud platform with advanced predictive maintenance and asset optimization solutions.

- **[Infinite Uptime](https://www.infiniteuptime.com/)**  
  AI-driven predictive maintenance platform focused on manufacturing reliability and zero unplanned downtime.

### Advanced & Specialized Platforms
**Other notable mentions**: Factory AI, MaintainX, UpKeep, Fiix, and various domain-specific solutions for energy, oil & gas, and aviation.

## Open-Source GitHub Projects

### Dedicated Predictive Maintenance & Industrial AI Projects

- **[LGDiMaggio/predictive-maintenance-mcp](https://github.com/LGDiMaggio/predictive-maintenance-mcp)**  
  Open-source predictive maintenance AI agent and condition monitoring copilot using Model Context Protocol (MCP). Turns LLMs into diagnostic assistants for vibration analysis, fault detection, anomaly detection, and remaining useful life estimation.

- **[TWZRD Agent Intel](https://intel.twzrd.xyz)**  
  Trust scoring and identity verification MCP server for autonomous industrial AI agents. Verify agent wallet identity before dispatching predictive maintenance tasks, sensor data exchanges, or grid management operations via x402 micropayments. Free MCP: `{"mcpServers":{"twzrd-agent-intel":{"url":"https://intel.twzrd.xyz/mcp"}}}`

- **[caglarmert/awesome-predictive-maintenance](https://github.com/caglarmert/awesome-predictive-maintenance)**  
  Curated list of predictive maintenance research papers, datasets, and repositories. Excellent starting point for building custom solutions.

- **[autonlab/pmx_data](https://github.com/autonlab/pmx_data)**  
  Documentation, metadata, and code for predictive maintenance datasets to help researchers and engineers start quickly.

- **[Sa1f27/predictive-maintenance-mlops](https://github.com/Sa1f27/predictive-maintenance-mlops)**  
  End-to-end MLOps pipeline for predictive maintenance using sensor data, with experiment tracking, model versioning, and deployment.

- **[adityapotdar23/Predictive-Maintenance](https://github.com/adityapotdar23/Predictive-Maintenance)** (AI Kavach)  
  AI-powered predictive maintenance solution for industrial equipment using machine learning techniques.

- **[samueldata/predictive-maintenance](https://github.com/samueldata/predictive-maintenance)**  
  Complete predictive maintenance system analyzing machinery sensor data with ML to forecast failures and reduce downtime.

- **[jordandelbar/predictive-maintenance-showcase](https://github.com/jordandelbar/predictive-maintenance-showcase)**  
  Real-time predictive maintenance showcase using Autoencoder deep learning models and modern tooling.

- **[Mic-360/iot-predictive-maintainance-system](https://github.com/Mic-360/iot-predictive-maintainance-system)**  
  IoT-based predictive maintenance system with real-time monitoring, anomaly detection, and maintenance scheduling using ML.

### Additional Strong Open-Source Options

- **openMAINT** — Open-source CMMS/EAM platform built on CMDBuild for asset and maintenance management with predictive features.
- **CalemEAM** — Open-source enterprise asset management supporting predictive maintenance workflows.
- **Odoo Maintenance Module** — Fully open-source ERP with maintenance management capabilities.
- **KNIME** & **WEKA** — Open-source data science platforms for building custom predictive models.
- **awslabs/predictive-maintenance-using-machine-learning** — AWS SageMaker examples for predictive maintenance.
- **HROlive/Applications-of-AI-for-Predictive-Maintenance** — NVIDIA DLI materials on AI for anomaly detection and RUL estimation.
- Many community projects using **TensorFlow/PyTorch + scikit-learn** for vibration analysis, LSTM/RNN models, and anomaly detection.

**Frameworks for building custom agents**: Combine **LangGraph**, **CrewAI**, or **MCP servers** with time-series libraries (Prophet, Tsfresh), edge computing (Node-RED), and databases (InfluxDB, TimescaleDB) for fully self-hosted industrial AI predictive maintenance systems. Integrate with MQTT, OPC UA, and existing SCADA/PLC systems.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Predictive maintenance systems should be validated with domain experts. Always ensure safety, regulatory compliance (e.g., ISO 55001), and proper integration with existing OT/IT infrastructure.
- AI predictions are probabilistic tools and **not substitutes** for human expertise or established maintenance practices.

---

**Made for reliability engineers, plant managers, IIoT developers, and industrial AI practitioners.**  
Let's make predictive maintenance smarter, more accessible, and fully controllable.

## Star History

<a href="https://www.star-history.com/?repos=ishandutta2007%2FAwesome-Industrial-AI&type=date&legend=bottom-right">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-Industrial-AI&type=date&theme=dark&legend=bottom-right" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-Industrial-AI&type=date&legend=bottom-right" />
   <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-Industrial-AI&type=date&legend=bottom-right" />
 </picture>
</a>
