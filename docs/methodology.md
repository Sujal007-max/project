# 📋 Assessment Methodology

## Overview

This document describes the methodology used to conduct the Network Security Assessment for TechSoft Solutions Pvt. Ltd.

> **Important:** This is an academic, passive assessment. No active scanning or exploitation was performed.

---

## Assessment Phases

### Phase 1 — Planning

**Objective:** Define what will and will not be assessed.

- Identify the organization's size and type
- Define assessment goals and success criteria
- Establish ethical boundaries (no live system testing)
- Create assessment timeline

**Output:** Scope definition document

---

### Phase 2 — Discovery

**Objective:** Map out all network components.

Activities:
- Document all network hardware (routers, switches, APs, servers)
- Identify IP address ranges and network topology
- List all active services and protocols in use
- Identify all user groups and access levels

**Output:** Network component inventory table

---

### Phase 3 — Vulnerability Analysis

**Objective:** Identify weaknesses in the network.

Activities:
- Review network configuration for common misconfigurations
- Check for open ports and unnecessary services
- Review password and authentication policies
- Assess wireless security configurations
- Evaluate physical security controls
- Check patch management status

**Output:** Vulnerability list with initial risk ratings

---

### Phase 4 — Risk Assessment

**Objective:** Rate each vulnerability by severity.

Risk Rating Formula:
```
Risk = Likelihood × Impact

Likelihood:  High (3) | Medium (2) | Low (1)
Impact:      High (3) | Medium (2) | Low (1)

Score 7-9 = Critical
Score 5-6 = High
Score 3-4 = Medium
Score 1-2 = Low
```

---

### Phase 5 — Reporting

**Objective:** Document all findings and recommendations clearly.

- Write structured report with all 6 required sections
- Include evidence and explanation for each finding
- Provide prioritized, actionable recommendations
- Reference industry frameworks (NIST, CIS, OWASP)

**Output:** Final security assessment report (.docx)

---

## Standards & Frameworks Referenced

| Framework | Purpose |
|-----------|---------|
| NIST CSF 2.0 | Overall cybersecurity framework |
| CIS Controls v8 | Technical security controls |
| OWASP Top 10 | Web application security risks |
| ISO/IEC 27001 | Information security management |
| India IT Act 2000 | Legal compliance reference |
