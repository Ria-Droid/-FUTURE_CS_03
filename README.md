# -FUTURE_CS_03
Professional API Security Risk Analysis of JSONPlaceholder test API with evidence-backed findings
# API Security Risk Analysis

## Overview
This project demonstrates a professional API security audit of the [JSONPlaceholder](https://jsonplaceholder.typicode.com/) public test API.  
The goal was to identify potential vulnerabilities related to authentication, access control, data exposure, and rate limiting, and provide clear remediation recommendations.  

The project simulates a real-world SaaS API security audit, reflecting the workflow of security consultants and AppSec teams.

---

## Tools Used
- **Postman** – Endpoint testing and inspection  
- **Browser Developer Tools** – Header and response analysis  
- **JSONPlaceholder** – Public test API  

---

## Methodology
The assessment was conducted ethically and followed a structured approach:

1. Reviewed API documentation to understand endpoints and expected behavior  
2. Tested endpoints using read-only requests in Postman  
3. Inspected HTTP headers and response payloads for sensitive data  
4. Tested endpoint behavior for rate limiting and predictable resource identifiers  
5. Identified security weaknesses and classified risks by severity  
6. Provided practical remediation recommendations  

> This workflow mirrors professional API security audits performed by SaaS security teams.

---

## Key Findings
| Risk | Severity | Business Impact | Recommended Action |
|------|---------|-----------------|------------------|
| Missing Authentication | High | Unauthorized access to sensitive user data | Implement token-based authentication (JWT/OAuth) |
| Excessive Data Exposure | Medium | Increases risk of phishing and privacy violations | Return only necessary fields and enforce least privilege |
| No Rate Limiting | Medium | API abuse, DoS risk | Implement request throttling and rate limiting mechanisms |
| Predictable Resource IDs | Low | Allows data enumeration and scraping | Use non-sequential UUIDs and enforce authorization |

---


## Ethical Note
All testing was performed on a **public test API** for educational purposes only.  
No private or production APIs were accessed, and no exploitation or bypass techniques were used.  

---

## How to Use This Repo
1. Clone or download the repository  
2. Review the `API_Security_Report.pdf` for a detailed professional assessment   
3. Review methodology and findings to understand common API security risks  

---

## Optional: Portfolio Showcase
This project can be included in a professional portfolio to demonstrate:

- Realistic API security analysis skills  
- Understanding of authentication, authorization, and data exposure risks  
- Ability to produce evidence-backed professional reports  
- Familiarity with tools like Postman and DevTools
