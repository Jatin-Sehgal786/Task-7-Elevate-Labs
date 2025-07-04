# 🔐 Browser Extension Security Audit Report

This repository contains a detailed security audit report of two browser extensions installed in a Chromium-based browser. The purpose of this audit is to evaluate the permissions, potential risks, and overall safety of each extension from a cybersecurity perspective.

## 📝 Overview

Two extensions were reviewed during this audit:

1. **FoxyProxy**
2. **CyberGhost VPN – Proxy for Chrome**

Both extensions were examined based on:
- Permissions granted
- Site access level
- Observed behavior and potential impact
- General cybersecurity risks

## 📊 Report Summary

| Extension Name           | Version | Size   | Key Permissions                                         | Risk Level |
|--------------------------|---------|--------|----------------------------------------------------------|------------|
| FoxyProxy                | 9.2     | < 1 MB | - Read and change all data on all websites  <br> - Manage downloads <br> - Display notifications | High       |
| CyberGhost VPN           | 9.2.2   | 3.2 MB | - Read and change all data on all websites               | High       |

> ⚠️ **Note:** Both extensions have elevated permissions that can pose serious security/privacy threats if misused or compromised.

## 🔎 Observations & Recommendations

- Both extensions require **full access to all websites**, which enables monitoring and altering of all web traffic.
- While this access is necessary for proxy/VPN functionality, it also introduces **high risk** if the extension is malicious or hijacked.
- **No performance issues** were observed after disabling and reviewing the extensions.
- **Best Practices**:
  - Only install extensions from trusted sources.
  - Avoid unnecessary permissions.
  - Periodically review and audit extensions.
  - Limit site access scope to specific URLs when possible.

## 📷 Included Screenshots

Screenshots of the extensions’ settings and permissions pages are included in the PDF report to provide visual verification of the analysis.

## 📄 Report PDF

You can find the full report with screenshots in this repository:

- `Extension_Security_Audit_Report_with_Screenshots.pdf`

## 📌 License

This audit was created for educational and awareness purposes. You are free to reuse, modify, and share it with attribution.

---

**Author**: Devil_Pikachu  
**Date**: July 2025
# Task-7-Elevate-Labs
