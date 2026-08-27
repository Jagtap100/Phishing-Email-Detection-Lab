
# 🗺️ MITRE ATT&CK Mapping

## Scenario

The simulated phishing email was analyzed and mapped to the relevant MITRE ATT&CK technique.

## Technique Mapping

| Tactic | Technique | ID | Description |
|---|---|---|---|
| Initial Access | Phishing | T1566 | Adversaries may use phishing techniques to gain initial access. |
| Initial Access | Spearphishing Link | T1566.002 | A phishing message may attempt to direct a user to a malicious or suspicious link. |

## Analyst Assessment

The simulated scenario demonstrates characteristics associated with phishing-based initial access.

The mapping is based on the behavior represented in this training scenario and does not indicate that a real attack occurred.

## Detection Opportunities

- Monitor suspicious email activity.
- Analyze sender and domain characteristics.
- Detect unusual links and user interaction.
- Correlate email activity with authentication and endpoint logs.
- Investigate related alerts in the SIEM.

## SOC Response

If confirmed as malicious:

1. Block confirmed malicious indicators.
2. Search for related activity across the environment.
3. Identify potentially affected users.
4. Monitor authentication and endpoint activity.
5. Escalate according to the incident response process.

> This MITRE ATT&CK mapping is created for cybersecurity training purposes using a simulated phishing scenario.
