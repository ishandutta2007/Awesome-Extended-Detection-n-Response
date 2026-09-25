# Awesome-Extended-Detection-n-Response

# Top Extended Detection & Response (XDR) Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Cross-Layer Detection, Correlation, Investigation & Automated Response Across Endpoint, Identity, Email, Network & Cloud*
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Extended Detection & Response (XDR)**. These systems collect and correlate telemetry from endpoints, identity, email, network, and cloud, surface high-fidelity incidents, and support investigation and automated response.

**Examples** include Microsoft Defender XDR, CrowdStrike Falcon XDR, SentinelOne Singularity XDR, Palo Alto Cortex XDR, Trend Vision One, Trellix XDR, Fortinet FortiXDR, Cisco XDR, Sophos XDR, Check Point Infinity XDR, and Bitdefender GravityZone XDR (the category leaders).

**Open-source emphasis**: Full commercial-grade XDR is vendor-centric, but strong open building blocks exist. **Wazuh**, **Velociraptor**, **TheHive + Cortex**, Elastic Security / Security Onion, and related projects enable self-hosted detection, hunting, and incident response. This section expands those options and remains realistic about the commercial gap for native multi-layer correlation and managed scale.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[Microsoft Defender XDR](https://www.microsoft.com/)**  
  Unified Microsoft security platform correlating endpoint, identity, email, cloud apps, and more—especially powerful (and often included) for Microsoft 365 E5 environments.

- **[CrowdStrike Falcon XDR](https://www.crowdstrike.com/)**  
  Cloud-native XDR built on the Falcon agent with strong threat intelligence, graph-based investigation, and high detection accuracy.

- **[SentinelOne Singularity XDR](https://www.sentinelone.com/)**  
  AI-native XDR platform emphasizing autonomous response, rollback, open architecture, and cross-domain correlation.

- **[Palo Alto Cortex XDR](https://www.paloaltonetworks.com/)**  
  XDR platform that pioneered the category—deep fusion of endpoint, network (NGFW), cloud, and identity telemetry within the Cortex ecosystem.

- **[Trend Vision One](https://www.trendmicro.com/)**  
  Extended detection and response platform with strong coverage across endpoint, email, server, and cloud workloads.

- **[Trellix XDR](https://www.trellix.com/)**  
  Enterprise XDR offering combining endpoint, network, and additional telemetry for detection and response.

- **[Fortinet FortiXDR](https://www.fortinet.com/)**  
  XDR solution integrated with the Fortinet Security Fabric for coordinated detection and automated response.

- **[Cisco XDR](https://www.cisco.com/)**  
  Cisco’s extended detection and response platform leveraging telemetry across Cisco and third-party security products.

- **[Sophos XDR](https://www.sophos.com/)**  
  XDR capability within the Sophos ecosystem focused on synchronized detection and response for mid-market and enterprise.

- **[Check Point Infinity XDR, Bitdefender GravityZone XDR and related platforms](https://www.example.com/)**  
  Additional XDR offerings from Check Point, Bitdefender, and other vendors providing cross-layer detection and response capabilities.

## Open-Source GitHub Projects
- **[Wazuh](https://github.com/wazuh/wazuh)**  
  Leading open-source security platform often described as SIEM/XDR—unified agent for endpoint telemetry, log analysis, file integrity, vulnerability detection, intrusion detection, active response, and compliance.

- **[Velociraptor](https://github.com/Velocidex/velociraptor)**  
  Powerful open-source endpoint visibility and digital forensics/incident response tool using VQL for live hunts, artifact collection, and fleet-wide investigation.

- **[TheHive](https://github.com/TheHive-Project/TheHive)**  
  Scalable open-source Security Incident Response Platform for case management, observables, collaboration, and tight integration with analysis engines.

- **[Cortex (TheHive Project)](https://github.com/TheHive-Project/Cortex)**  
  Open observable analysis and active response engine that pairs with TheHive for automated enrichment and response actions.

- **[Elastic Security / OpenSearch Security analytics](https://github.com/elastic)**  
  Open detection and response capabilities built on the Elastic / OpenSearch stack—rule-based detection, timeline investigation, and endpoint integration options.

- **[Security Onion](https://github.com/Security-Onion-Solutions/securityonion)**  
  Free and open platform for threat hunting, enterprise security monitoring, and log management that bundles multiple open detection components.

- **[OSSEC and related HIDS projects](https://github.com/)**  
  Host-based intrusion detection foundations that many open security platforms (including Wazuh) build upon.

- **[osquery](https://github.com/osquery/osquery)**  
  SQL-powered endpoint instrumentation for inventory, compliance, and detection engineering pipelines.

- **[Sigma rules and detection-as-code open repos](https://github.com/SigmaHQ/sigma)**  
  Community detection rules that can be converted and deployed across open and commercial detection backends.

- **[Shuffle and open SOAR / automation helpers](https://github.com/)**  
  Open workflow automation tools used to orchestrate response actions alongside open detection stacks.

### Additional Strong Open-Source Options
- Assembling a practical open XDR-style stack: **Wazuh** (or Elastic Security) for detection + **Velociraptor** for deep IR + **TheHive/Cortex** for case management and enrichment.
- Using Security Onion as an all-in-one open monitoring and hunting platform.
- Accepting that native multi-layer correlation across endpoint + identity + email + network + cloud at commercial scale, managed detection quality, and vendor threat intelligence still favor platforms such as Microsoft Defender XDR, CrowdStrike Falcon, SentinelOne, Cortex XDR, and Trend Vision One.
- Focusing open-source efforts on transparency of detection logic, data ownership, and cost control for security engineering teams.

**Frameworks for building custom systems**: Deploy endpoint agents (Wazuh/osquery/Velociraptor) → centralize logs and alerts in an open SIEM/indexer → correlate with Sigma or custom rules → manage incidents in TheHive → automate enrichment/response with Cortex or Shuffle. Suitable for organizations with security engineering capacity. Most mid-to-large enterprises adopt commercial XDR for coverage, detection fidelity, and operational scale.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Detection and response systems protect organizations from active threats. Misconfigured tools can miss attacks or generate operational risk. Open-source stacks require skilled operation, continuous tuning, and clear incident processes. This list is not security or legal advice.

---
**Made for SOC teams, detection engineers, and open-source security advocates.**
Let's keep threats visible, investigations faster, and core detection as open as practical.
