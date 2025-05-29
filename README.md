# 📄 Task 3 of the Elevate Labs Cybersecurity Internship
# Nessus Vulnerability Scan Report

**Host Scanned:** 127.0.0.1  
**Date of Scan:** *29/5/2025*  
**Total Vulnerabilities Identified:** 33
**Report link:** https://github.com/shivdev729/elevate_task_03/blob/main/TASK-3%20Elevate%20Lab.pdf

---

## 1. Vulnerability Summary by Severity

| Severity   | Count |
|------------|-------|
| Critical   | 0     |
| High       | 0     |
| Medium     | 2     |
| Low        | 0     |
| Info       | 31    |

> ⚠️ While there are no critical or high-severity issues, the presence of medium and multiple informational findings indicates potential risks, especially if exploited in combination.

---

## 2. Fixes and Mitigations

Below are remediation steps for selected findings:

- **SSL Certificate Cannot Be Trusted (Plugin ID: 51192)**  
  *Remediation:* Use an SSL certificate issued by a trusted Certificate Authority (CA).

- **SMB Signing Not Required (Plugin ID: 57608)**  
  *Remediation:* Enable SMB signing through Group Policy to mitigate man-in-the-middle (MITM) attacks.

> ℹ️ It is also advisable to review informational findings and disable any unnecessary or exposed services to reduce the overall attack surface.

---

## 3. Medium Severity Vulnerabilities

| Vulnerability                      | CVSS Score | Description / Remediation |
|-----------------------------------|------------|----------------------------|
| **SSL Certificate Cannot Be Trusted** | 6.5        | Replace with a certificate signed by a trusted CA. |
| **SMB Signing Not Required**         | 5.3        | Configure SMB to require signing for added security. |

---

_Prepared by:_  Shivang Shukla 
