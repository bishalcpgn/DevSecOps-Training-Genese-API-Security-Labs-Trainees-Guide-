# APISec Training · OWASP API Security Labs

A trainee-side workbook for hands-on **OWASP API Security Top 10 (2023)** workshops using crAPI and Burp Suite Community Edition.

## What this is

A single-page HTML workbook covering all 10 OWASP API Security categories (API1–API10), each mapped to real crAPI challenges with the vulnerability summary, affected endpoints, and recon hints to get you started. The exploit is intentionally left for you to figure out — that's where the learning happens.

**Trainee-only material.** This platform gives hints and recon guidance. Full reproduction steps and solutions are with the trainer.

## Lab modules

| # | OWASP Category | crAPI Challenges |
|---|---|---|
| API1 | Broken Object Level Authorization | #1 |
| API2 | Broken Authentication | #3 |
| API3 | Broken Object Property Level Authorization | #8, #9 |
| API4 | Unrestricted Resource Use | #6 |
| API5 | Broken Function Level Authorization | #7 |
| API6 | Sensitive Business Flows | #9 (automated) |
| API7 | Server-Side Request Forgery | #11 |
| API8 | Security Misconfiguration | #14 |
| API9 | Improper Inventory Management | #3 (embedded) |
| API10 | Unsafe API Consumption | #12 |

## Project structure

```
.
├── index.html       # Main trainee workbook
├── css/
│   ├── style.css    # Layout and component styles
│   └── themes.css   # Light/dark theme variables
└── js/              # Progress tracking, lab timers, and certificate
```

## Quick start

**Live:** [bishalcpgn.github.io/DevSecOps-Training-Genese-API-Security-Labs-Trainees-Guide-](https://bishalcpgn.github.io/DevSecOps-Training-Genese-API-Security-Labs-Trainees-Guide-/#welcome)


## References

- [OWASP API Security Top 10 (2023)](https://owasp.org/API-Security/editions/2023/en/0x11-t10/)
- [OWASP crAPI](https://github.com/OWASP/crAPI)
- [crAPI Challenge List](https://github.com/OWASP/crAPI/blob/develop/docs/challenges.md)
- [Burp Suite Community Edition](https://portswigger.net/burp/communitydownload)
