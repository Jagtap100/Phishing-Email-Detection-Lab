# 🔐 Phishing Email Detection & Investigation Lab

A practical SOC lab for analyzing a simulated phishing email, extracting Indicators of Compromise (IOCs), classifying severity, mapping activity to MITRE ATT&CK, and documenting recommended incident response actions.

## 🎯 Objective

To demonstrate the end-to-end workflow followed by a SOC analyst when investigating a suspected phishing email alert.

## 📁 Project Contents

- phishing_email_sample.txt — Simulated phishing email used for analysis
- investigation_report.md — Investigation findings and analyst assessment
- ioc_analysis.md — Extracted indicators and analysis
- mitre_mapping.md — MITRE ATT&CK technique mapping
- README.md — Project overview and documentation

## 🔎 Investigation Workflow

1. Email Collection — Received the simulated phishing email for analysis.
2. Header Analysis — Reviewed sender and email characteristics.
3. Content Analysis — Checked subject, body, urgency, and suspicious requests.
4. IOC Extraction — Identified suspicious domains, keywords, and artifacts.
5. Threat Assessment — Evaluated the indicators and potential impact.
6. Severity Classification — Assigned an appropriate severity level.
7. MITRE ATT&CK Mapping — Mapped the activity to relevant techniques.
8. SOC Response — Documented recommended containment and mitigation actions.

## 🚨 Key Findings

- Suspicious sender characteristics were identified.
- Urgent language and account verification requests were observed.
- The email demonstrated common phishing indicators.
- Relevant indicators were documented for further investigation.
- The simulated scenario was mapped to T1566.002 – Phishing: Spearphishing Link.
- Overall severity: Medium.

## 🛡️ Recommended SOC Actions

1. Block or investigate identified suspicious indicators.
2. Search SIEM for related events and similar activity.
3. Review email security and delivery logs.
4. Check whether other users received similar messages.
5. Monitor affected accounts for suspicious follow-up activity.
6. Escalate the incident if malicious activity is confirmed.

## 🛠️ Tools & Skills

- SIEM / Splunk
- Email Header Analysis
- IOC Analysis
- Log Analysis
- Security Monitoring
- Incident Investigation
- MITRE ATT&CK
- SOC Alert Triage

## ⚠️ Disclaimer

This project is created for educational and cybersecurity training purposes only.

All email content, domains, and indicators used in this repository are simulated. No real credentials, personal information, or malicious infrastructure are used.

## 👤 Author

Jagtap100

Aspiring SOC Analyst | Cybersecurity Enthusiast
