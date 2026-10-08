# Threat Intelligence Report: Modern Cybersecurity Threats (2024-2025)

**Cybersecurity Internship, Task 1** | Maincrafts Technology
**Author:** Surya | **Role:** Cybersecurity Analyst Intern (simulation)

A research report that analyzes five major cybersecurity threats from 2024-2025, each backed by a real-world incident, an impact analysis, a SOC detection note mapped to MITRE ATT&CK, and practical preventive measures.

**[Read the report (PDF)](./Cybersecurity_Threat_Report_Task1_Surya.pdf)**

---

## Threats covered

| # | Threat | Case study | Date | Headline impact |
|---|--------|------------|------|-----------------|
| 1 | Software supply chain attacks | XZ Utils backdoor (CVE-2024-3094) | Mar 2024 | CVSS 10.0 backdoor in the SSH path, caught before wide rollout |
| 2 | Ransomware on critical services | Change Healthcare | Feb 2024 | About 190 million people affected; $22M ransom paid |
| 3 | Infostealers and cloud account takeover | Snowflake customer breaches | 2024 | About 165 organizations notified; targeted accounts lacked MFA |
| 4 | Help-desk social engineering | Marks & Spencer | Apr 2025 | About GBP 300M hit to operating profit |
| 5 | Zero-day exploitation | SharePoint "ToolShell" (CVE-2025-53770) | Jul 2025 | Hundreds of victim organizations; patching alone was not enough |

## What is inside the report

1. **Introduction:** what cybersecurity is, why it matters, and current data from the FBI IC3 2025 Internet Crime Report (losses of about $20.9B, up 26% year on year)
2. **Threat analysis:** for each threat, an overview, impact on individuals vs. organizations, a case study, a SOC detection note with ATT&CK technique IDs, and three preventive measures
3. **Conclusion and future scope:** the common thread across the cases and where the threat landscape is heading
4. **References:** all sources used

## Key takeaway

In three of the five cases (Change Healthcare, Snowflake, Marks & Spencer), attackers did not break the technology. They logged in, or talked their way into a login. The gap was identity: missing MFA, stale credentials and weak reset procedures. The other two cases show the risk of trusted software (XZ Utils) and the speed of mass exploitation after a vulnerability is found (ToolShell).

## Skills demonstrated

- Threat research and analysis using public sources (CISA, Mandiant, FBI IC3, vendor and news reporting)
- Mapping incidents to MITRE ATT&CK techniques
- Writing detection ideas from a SOC analyst's perspective
- Presenting technical findings in a professional report format

## Repository structure

```
.
├── README.md
└── Cybersecurity_Threat_Report_Task1_Surya.pdf
```

## Sources

Full source list is in the References section of the PDF. Main sources include the FBI IC3 2025 Internet Crime Report, CISA advisories, Mandiant, KrebsOnSecurity, The Hacker News and the MITRE ATT&CK knowledge base.

## Disclaimer

This is an educational, simulated internship deliverable. All incidents discussed are publicly documented events. Figures come from public reporting and may be revised as investigations continue.

## Connect

- LinkedIn: _add your profile link here_
