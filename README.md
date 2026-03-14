# Cloud Security Audit – Chevy Health Tech Solutions (HealthTech)

*This project reflects the type of work I support in real-world engagements. The documentation consolidates insights from that experience alongside my ongoing self-directed study. All materials use synthetic data—no client information is reproduced—and the templates are either self-developed or properly licensed and are not proprietary to any organisation.*

---

Assisted on a cloud security [audit](https://drive.google.com/drive/folders/1F6qncYgKzWQNEucJqvQND_PzTDbfWHYb?usp=sharing) of a healthtech provider processing patient health information (PHI). The assessment evaluated security controls against the **Cloud Security Alliance Cloud Controls Matrix (CCM) v4.1.0** and **Nigeria Data Protection Act (NDP Act)** requirements to determine overall cloud security posture and regulatory readiness.

----

## Approach
*   Defined [security requirements](https://docs.google.com/document/d/1t8ejj8LWExG3SzfWUBmfsEs7NvtD_KBu/edit?usp=sharing&ouid=101134501969411208830&rtpof=true&sd=true) aligned with CCM and NDP Act.
  
*   Administered a structured audit [checklist](https://docs.google.com/spreadsheets/d/1jglVGEDf6M_dVjexjHUZmlDCK2x_cotD/edit?usp=drive_link&ouid=101134501969411208830&rtpof=true&sd=true) covering key domains including logging, data security, incident response, vulnerability management, and network security.
  
*   [Performed](https://docs.google.com/document/d/18_ucb1WXBi-SAywe4euLWugzCRlbQVMw/edit?usp=sharing&ouid=101134501969411208830&rtpof=true&sd=true) evidence-based testing through AWS configuration reviews, CloudTrail log analysis, security group assessments, and verification of key management and backup practices.

---

## Key Findings & Recommendations

*   **Untested Incident Response (Critical):** Breach response procedures were incomplete and had never been tested. *Recommendation*: Implement and test an NDPA-compliant incident response plan with defined roles and communication protocols.

*   **Third-Party Risk Gaps (High):** No formal review of cloud provider audit reports or documented shared responsibility model existed. *Recommendation*: Establish a vendor risk management program and conduct annual reviews of CSP assurance reports.

*   **Data Exposure Risk (High):** Production PHI was present in staging environments without adequate controls. *Recommendation*: Enforce strict data segregation policies and implement data masking for all non-production environments.

*   **Incomplete Vulnerability Coverage (High):** Security scanning excluded serverless assets, and no defined patch SLAs were in place. *Recommendation*: Expand vulnerability scanning to all workload types and implement risk-based patch timelines with clear SLAs.

---

## Outcome & Reflection

Identified strong foundational security controls but critical governance gaps, particularly in incident response and vendor risk management. The highest risks stemmed from procedural and oversight gaps rather than technical failures. Delivered a prioritised remediation roadmap to leadership, enabling targeted risk reduction and strengthened regulatory compliance.

---

## Linked Project Documents

[Cloud Security Audit – Chevy Health Tech Solutions (HealthTech)](https://drive.google.com/drive/folders/1F6qncYgKzWQNEucJqvQND_PzTDbfWHYb?usp=sharing)
