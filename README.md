# foundation-ai-detection-response-poc
# Foundation AI for Incident Detection & Response (POC)

This project explores how Cisco Foundation AI can be leveraged to enrich and correlate detections from multiple security tools, improving SOC efficiency, reducing false positives, and enabling faster response.  

**Note:** This repository is a sanitized portfolio demo.  
All data, logs, and outputs are mock or simulated. No proprietary or company-specific information is included.  

---

## Objectives
- Improve incident detection and triage using AI-enriched threat intelligence  
- Correlate detections across different tools (e.g., EDR + NDR)  
- Tag events with MITRE ATT&CK tactics & techniques 
- Generate actionable analyst recommendations 

---

##   Key Features
- Multi-Tool Ingestion → Normalizes alerts from different platforms  
- AI-Driven Enrichment → Tags detections with MITRE tactics & techniques  
- Risk Scoring → Generates normalized risk scores (0–100)  
- Recommendations → Produces analyst-ready remediation steps  
- Demo Dashboard → Incident list, correlation view, MITRE mapping, and timeline  

---

##  Example Workflow
1. Collect sample alerts from EDR and NDR sources  
2. Parse JSON → normalize into a common schema  
3. Correlate alerts by shared indicators (IP, device ID, user ID)  
4. Apply AI enrichment:  
   - MITRE mapping  
   - Risk scoring  
   - Confidence banding  
   - One-line recommendation  
5. Visualize in a dashboard (demo included)  

---

##  Tech Stack
- Python 3**  
- Cisco Foundation AI (open model)  
- MITRE ATT&CK Framework  
- Replit / Web dashboard for demo 

---

##  References
- [Cisco Foundation AI – Building the Intelligent Future of Cybersecurity](https://blogs.cisco.com/security/foundation-ai-building-the-intelligent-future-of-cybersecurity)  
- [Cisco FoundationSec – First Open-Source Security Model](https://blogs.cisco.com/security/foundation-sec-cisco-foundation-ai-first-open-source-security-model)  
- MITRE ATT&CK: https://attack.mitre.org  

---

##  About This Project
This proof-of-concept was developed as part of an internship project to showcase how AI can be operationalized in SOC workflows.  
The repo is intended for learning, portfolio demonstration, and discussion only.  


