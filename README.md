# vuln_discovery_0

# Responsible Vulnerability Disclosure Documentation

This repository documents the process of responsibly disclosing a security vulnerability discovered in an Android app of a famous bank in Bangladesh. The name is mutually undisclosed as it's a financial organization and the authority agreed to this. It aims to outline the steps taken to identify, verify, and report the vulnerability to the appropriate parties without exposing sensitive information or compromising the security of the bank's systems and its customers.

## Discovery Process

The vulnerability was discovered during a routine security review of publicly available banking applications.

- Extracted the `APK` file using `MT Manager`
- Decompiled the `APK` file using `jadx` for static analysis.
- Dynamic analysis using `MobSF`

## Reporting Process

1. **Identification of Reporting Channels**: The report was done to the CEO, CTO and the Security team.
2. **Preparation of the Report**: What sensetive keys I found and how it impacts the users' privacy
3. **Submission of the Report**: An official mail was sent.
4. **Follow-Up**: The initial response was prompt and from the CEO himself. Later, the security team acknowledged the exposed key and quickly relocated the key in the next update.

## Communication Log

- **First Submission Date**: Fri, Mar 8, 2024
  <p align="center">
    <img src="1.png" alt="First_Report" width="800" height="300">
  </p>
- **Initial Response from CEO**: Yes. Fri, Mar 9, 2024
  <p align="center">
    <img src="2.png" alt="First_Report" width="800" height="300">
  </p>
- **Security Team's Response**: Yes. Mar 11, 2024
  <p align="center">
    <img src="3.png" alt="First_Report" width="800" height="300">
  </p>
- **My recommendation**:
  <p align="center">
    <img src="4.png" alt="First_Report" width="800" height="300">
  </p>
- **Update Notice**: Yes. Mar 13, 2024
  <p align="center">
    <img src="5.png" alt="First_Report" width="700" height="100">
  </p>

## Conclusion

Responsible vulnerability disclosure is crucial in the collaborative effort to secure digital assets and protect users. This documentation aims to contribute to the broader community's understanding and practice of ethical vulnerability research and reporting.
