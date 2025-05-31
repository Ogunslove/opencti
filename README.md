# 🛡️ Threat Intelligence Integration: OpenCTI + AlienVault OTX  
**A Case Study from Exke Corporation**

## 📘 Overview

This project demonstrates the integration of the **AlienVault OTX** connector into the **OpenCTI** platform to build a centralized and automated **Threat Intelligence** capability at **Exke Corporation** (HQ: USA).  
The integration enhances our ability to detect, enrich, and respond to emerging cyber threats using real-time intelligence.

---

## 🧩 Objectives

- Automate ingestion of Indicators of Compromise (IOCs) from AlienVault OTX  
- Enable contextual enrichment within OpenCTI using STIX 2.1 format  
- Visualize and correlate relationships between threat entities  
- Support SOC operations with actionable threat insights

---

## ⚙️ Tools & Technologies

| Tool/Platform     | Purpose                          |
|------------------|----------------------------------|
| **OpenCTI**       | Threat Intelligence Platform     |
| **AlienVault OTX**| Threat Feed Provider             |
| **STIX 2.1 / TAXII** | Threat Data Standard         |
| **Docker**         | Containerized Deployment        |
| **Python**         | Connector Configuration         |
| **Neo4j** / **Elasticsearch** | Data backends       |

---

## 🛠️ Key Features

- ✅ **AlienVault OTX connector setup and configuration**  
- ✅ **Scheduled and real-time IOC ingestion**  
- ✅ **Threat actor and campaign enrichment via OTX pulses**  
- ✅ **Graph-based correlation and visual threat mapping in OpenCTI**

---

## 🧱 Architecture

```mermaid
graph TD
  A[AlienVault OTX] --> B[OpenCTI Connector]
  B --> C[OpenCTI Platform]
  C --> D[Neo4j]
  C --> E[Elasticsearch]
