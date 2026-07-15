# 📊 Risk Rating Matrix

## Risk Calculation

Each identified vulnerability is rated using the following formula:

```
Risk Level = Likelihood × Impact
```

---

## Likelihood Scale

| Score | Level | Description |
|-------|-------|-------------|
| 3 | **High** | Attack is easy, tools are publicly available, commonly exploited |
| 2 | **Medium** | Requires some skill or specific conditions to exploit |
| 1 | **Low** | Difficult to exploit, requires insider knowledge or rare conditions |

---

## Impact Scale

| Score | Level | Description |
|-------|-------|-------------|
| 3 | **High** | Major data breach, system compromise, or financial loss |
| 2 | **Medium** | Limited data exposure, temporary disruption of services |
| 1 | **Low** | Minor issue, no significant business impact |

---

## Risk Matrix

```
         │  LOW Impact (1) │ MEDIUM Impact (2) │ HIGH Impact (3) │
─────────┼─────────────────┼───────────────────┼─────────────────┤
HIGH     │     Medium (3)  │     High (6)      │  Critical (9)   │
Like.(3) │                 │                   │                 │
─────────┼─────────────────┼───────────────────┼─────────────────┤
MED.     │      Low (2)    │    Medium (4)     │   High (6)      │
Like.(2) │                 │                   │                 │
─────────┼─────────────────┼───────────────────┼─────────────────┤
LOW      │      Low (1)    │     Low (2)       │  Medium (3)     │
Like.(1) │                 │                   │                 │
─────────┴─────────────────┴───────────────────┴─────────────────┘
```

---

## Risk Level Definitions

| Score | Level | Color | Required Action |
|-------|-------|-------|----------------|
| 7–9 | 🔴 **Critical** | Red | Immediate action — fix within 24–72 hours |
| 5–6 | 🟠 **High** | Orange | Fix within 30 days |
| 3–4 | 🟡 **Medium** | Yellow | Fix within 90 days |
| 1–2 | 🟢 **Low** | Green | Fix as resources allow |

---

## Applied Risk Ratings

| Vuln ID | Vulnerability | Likelihood | Impact | Score | Rating |
|---------|--------------|-----------|--------|-------|--------|
| V-01 | Flat network topology | H(3) | H(3) | 9 | 🔴 Critical |
| V-02 | Unpatched systems | H(3) | H(3) | 9 | 🔴 Critical |
| V-03 | Unsecured Guest Wi-Fi | H(3) | H(3) | 9 | 🔴 Critical |
| V-04 | Default/weak passwords | H(3) | M(2) | 6 | 🟠 High |
| V-05 | No MFA | H(3) | M(2) | 6 | 🟠 High |
| V-06 | Open ports | M(2) | H(3) | 6 | 🟠 High |
| V-07 | No IDS/IPS | M(2) | H(3) | 6 | 🟠 High |
| V-08 | Unencrypted HTTP | M(2) | M(2) | 4 | 🟡 Medium |
| V-09 | No backup policy | L(1) | H(3) | 3 | 🟡 Medium |
| V-10 | Outdated WPA2/TKIP | M(2) | M(2) | 4 | 🟡 Medium |
| V-11 | No security training | H(3) | M(2) | 6 | 🟡 Medium |
| V-12 | Unsegmented IoT | M(2) | M(2) | 4 | 🟡 Medium |
| V-13 | Physical access | L(1) | M(2) | 2 | 🟢 Low |
| V-14 | No AUP policy | L(1) | L(1) | 1 | 🟢 Low |
