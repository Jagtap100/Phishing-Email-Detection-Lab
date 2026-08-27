# 🔎 IOC Analysis

## Objective

Identify and document potential Indicators of Compromise (IOCs) from the simulated phishing email.

## Identified Indicators

| Indicator | Type | Observation | Risk |
|---|---|---|---|
| example-training.com | Domain | Simulated sender domain | Medium |
| Urgent verification request | Email characteristic | Creates urgency | Medium |
| Generic greeting | Email characteristic | No personalized identification | Low |
| Account verification request | Social engineering indicator | Attempts to influence user action | Medium |

## Analyst Assessment

The simulated email contains multiple characteristics commonly associated with phishing activity.

The indicators should be investigated and correlated with available email and SIEM logs before determining whether malicious activity occurred.

## Recommended Investigation

- Search SIEM for related email activity.
- Check whether other users received similar messages.
- Review sender and domain reputation using approved security tools.
- Search for related authentication activity.
- Document confirmed IOCs for incident response.

## Status

Classification: Suspicious / Potential Phishing

Severity: Medium

> All indicators in this project are simulated for cybersecurity training purposes.
