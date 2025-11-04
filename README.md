# VLC Media Player Security Case Study

This repository contains a comprehensive security analysis of **VLC Media Player**, a widely used open-source multimedia platform. Our research examines VLC’s internal architecture, historical vulnerabilities, and secure development practices to understand how security issues arise and are mitigated in large-scale open-source systems.

---

## Overview

### Areas of Focus
- **System Architecture Analysis**
  - Input, Demuxer, Decoder, Networking, and Interface subsystems
- **Threat Modeling**
  - Asset identification, trust boundaries, and attack surfaces
- **Vulnerability History Investigation**
  - Deep analysis of notable CVEs, tracing issues from introduction to fix
  - Examined issues including buffer overflows, arbitrary code execution, memory mismanagement, and input-handling flaws
- **Attack Scenarios**
  - Examples demonstrating risks through malicious media files, plugins, and network streams
- **Secure Engineering Principles**
  - Boundary checking & safe memory practices
  - Secure input handling
  - Incremental development and code review discipline
  - Defense-in-depth & distrustful decomposition

---

## Key Insights
- Open-source media software faces unique risks from untrusted media and extensible plugins.
- Vulnerabilities can persist for years due to subtle coding assumptions or limited review.
- Strong engineering practices — including thorough input validation, fuzz testing, and peer reviews — are critical to reducing exposure.
- Defense-in-depth and modular security help contain potential exploit paths.

---

## Authors

| **Helena Lynd** |
| **Coray Bennett** |
| **Hunter White** |
| **Abiel Yemane** |

---

## 📂 Contents

- Full case study PDF
- Supporting notes & references
- Breakdown of key CVEs and commit history

