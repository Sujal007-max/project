# ✅ Network Security Hardening Checklist

> Use this checklist to track implementation progress of all security recommendations.
> Mark each item as `[x]` when completed.

---

## 🔴 Phase 1 — Immediate Actions (Week 1–4)

### Network Architecture
- [ ] Design VLAN plan (Corporate / Servers / Guest / IoT / Management)
- [ ] Upgrade to managed network switch that supports 802.1Q VLANs
- [ ] Configure VLANs on switch and layer-3 routing
- [ ] Apply ACLs to restrict inter-VLAN traffic
- [ ] Verify guest Wi-Fi is isolated from corporate network

### Credentials & Access Control
- [ ] Change default admin password on all routers
- [ ] Change default admin password on all switches
- [ ] Change default admin password on all Wi-Fi access points
- [ ] Change default admin password on printers and IP cameras
- [ ] Enforce password policy: 12+ chars, upper+lower+numbers+symbols
- [ ] Remove all unused admin accounts

### Patch Management
- [ ] Audit all workstations — list OS version and pending updates
- [ ] Enable automatic Windows security updates on all PCs
- [ ] Apply all critical patches to servers immediately
- [ ] Update firmware on all network devices
- [ ] Create monthly patch review calendar with assigned IT owner

### Port & Firewall Hardening
- [ ] Audit all open ports on servers and firewalls
- [ ] Disable Telnet (Port 23) — enable SSH (Port 22) instead
- [ ] Disable FTP (Port 21) — enable SFTP instead
- [ ] Restrict RDP (Port 3389) to VPN access only
- [ ] Disable port 8080 — redirect all HTTP to HTTPS (443)
- [ ] Implement "deny all, allow specific" firewall policy
- [ ] Document all approved firewall rules

---

## 🟠 Phase 2 — Short-Term Actions (Month 2–3)

### Authentication
- [ ] Select MFA solution (Google Auth / Microsoft Auth / YubiKey)
- [ ] Enable MFA on all administrator accounts
- [ ] Enable MFA on all employee email accounts
- [ ] Enable MFA on VPN access
- [ ] Enable MFA on server login access
- [ ] Train all staff on how to use MFA

### Intrusion Detection
- [ ] Research and select IDS solution (Snort / Suricata / Wazuh)
- [ ] Install and configure IDS on network perimeter
- [ ] Configure detection rules for common attacks (port scan, brute force, SQLi)
- [ ] Set up real-time alert notifications
- [ ] Assign security personnel to review alerts daily
- [ ] Test IDS by simulating a controlled port scan

### Encryption
- [ ] Obtain TLS certificates for all web applications (Let's Encrypt)
- [ ] Install and configure HTTPS on web server
- [ ] Configure HTTP-to-HTTPS redirect (301)
- [ ] Disable SSL 3.0, TLS 1.0, TLS 1.1 on all servers
- [ ] Enable TLS 1.2 and TLS 1.3 only
- [ ] Verify encryption with SSL Labs test

### Backup & Recovery
- [ ] Define data criticality (what must be backed up)
- [ ] Select backup solution (Veeam / Acronis / Windows Backup)
- [ ] Configure daily incremental backups
- [ ] Configure weekly full backups
- [ ] Store one copy offsite or in cloud (3-2-1 Rule)
- [ ] Document RTO = 4 hours and RPO = 24 hours
- [ ] Perform first test restore to verify backup works
- [ ] Schedule monthly restore tests

---

## 🟡 Phase 3 — Long-Term Actions (Month 3+)

### Wi-Fi Security
- [ ] Audit all access points — document model, firmware, encryption type
- [ ] Update firmware on all APs to latest version
- [ ] Switch all WPA2-TKIP networks to WPA2-AES minimum
- [ ] Plan upgrade path to WPA3 for next hardware refresh
- [ ] Configure separate SSIDs: Corp, Guest, IoT
- [ ] Enable client isolation on guest SSID
- [ ] Disable WPS (Wi-Fi Protected Setup) on all APs
- [ ] Change default AP admin passwords (if not done in Phase 1)

### IoT Security
- [ ] Create inventory of all IoT devices (printers, cameras, etc.)
- [ ] Move all IoT devices to VLAN 40
- [ ] Update firmware on all IoT devices
- [ ] Disable UPnP on all IoT devices
- [ ] Disable remote management unless required
- [ ] Apply MAC address filtering for IoT VLAN
- [ ] Block IoT devices from accessing corporate VLAN

### Employee Training
- [ ] Create or purchase cybersecurity awareness training content
- [ ] Schedule and deliver training to all staff (2+ hours)
- [ ] Focus on: phishing recognition, password hygiene, social engineering
- [ ] Run first simulated phishing campaign
- [ ] Measure results and identify high-risk users for extra training
- [ ] Schedule next training session (every 6 months)
- [ ] Display security awareness posters in office

### Security Policies
- [ ] Draft Acceptable Use Policy (AUP)
- [ ] Have legal or management review the AUP
- [ ] Distribute AUP to all employees for signature
- [ ] Include AUP in new employee onboarding process
- [ ] Draft Incident Response Policy
- [ ] Define roles and responsibilities in case of a breach
- [ ] Create Clean Desk Policy
- [ ] Enforce screen lock after 5 minutes of inactivity
- [ ] Schedule quarterly security audits

---

## 📈 Progress Tracker

| Phase | Total Tasks | Completed | % Done |
|-------|------------|-----------|--------|
| Phase 1 — Immediate | 25 | 0 | 0% |
| Phase 2 — Short-Term | 31 | 0 | 0% |
| Phase 3 — Long-Term | 37 | 0 | 0% |
| **Total** | **93** | **0** | **0%** |

> Update this table as you complete each task!
